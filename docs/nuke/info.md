
- When doing a vertex export with the legacy 3D system and a TransfromGeo node connected, it might export both vertex position for both the object and the transformgeo vertex. To get around this check the "Only selected nodes" in the settings and make sure to select the node before exporting the selected vertices.


- The new 3d system is still in early stages and therefore the workflow with exchange might change later on if needed.

- Sometimes in newer Nuke versions (15.0?) the world matrix knob is not updated correctly which means that 3D exports might not be correct if the Axis knob is used. Restarting Nuke seems to fix this. Hopefully this is fixed in later nuke versions.

- For transformgeo (legacy) nodes the "lookat" input is not supported. If lookat is really needed a workaround would be to duplicate the node as an axis first and then export that (as Axis does support lookat).

- For 3D primitive nodes the radius (or similar) knobs are baked into the global scale of the object. Animation is supported.

- Clipping plane for cameras is not imported by default (other than nuke to nuke). To enable clipping plane import for camera from other apps into nuke set the EXCHNAGE_IMPORT_CLIPPING_PLANE environment variable to 1.