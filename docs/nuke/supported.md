

# 3D nodes (legacy)
   Node         | Import | Export |
 |----------------|--------|--------|
 | Camera         | ✓      | ✓      |
 | Axis           | ✓      | ✓      |
 | Card           | ✓      | ✓      |
 | Cube           | ✓      | ✓      |
 | Sphere         | ✓      | ✓      |
 | Cylinder       | ✓      | ✓      |
 | Light          | ✓      | ✓      |
 | Spotlight      | ✓      | ✓      |
 | PointLight     | ✓      | ✓      |
 | Environment    | ✓      | ✓      |
 | TransformGeo   | ✓      | ✓      |
 | ReadGeo        | ✓      | ✓      |
 | WriteGeo       | -      | ✓      |
  | Mesh vertex         | ✓      | ✓      |

# 3D nodes (new)
 | Node            | Import | Export |
 |-------------------|--------|--------|
 | Camera            | ✓      | ✓      |
 | GeoCard           | ✓      | ✓      |
 | GeoCube           | ✓      | ✓      |
 | GeoSphere         | ✓      | ✓      |
 | GeoRevolve        | ✓      | ✓      |
 | GeoCylinder       | ✓      | ✓      |
 | DirectLight       | ✓      | ✓      |
 | SpotLight         | ✓      | ✓      |
 | PointLight        | ✓      | ✓      |
 | EnvironmentLight  | ✓      | ✓      |
 | GeoTransform      | ✓      | ✓      |
 | GeoImport         | ✓      | ✓      |
 | GeoReference      | ✓      | ✓      |
 | GeoExport         | -      | ✓      |
 | GeoXForm          | -      | ✓ (as locator)      |
 | GeoConstrain       | -      | ✓ (as locator*)      |
  | Mesh vertex         | ✓      | ✓      |

* GeoConstrain only supports export if source and target are single prims.



# Read nodes
 | Node     | Import | Export |
 |------------|--------|--------|
 | Read       | ✓      | ✓      |
 | Write      | -      | ✓      |
 | DeepRead   | ✓      | ✓      |
 | DeepWrite  | -      | ✓      |

# 2D nodes
 | Node      | Import | Export |
 |-------------|--------|--------|
 | Transform   | ✓      | ✓      |
 | Tracker4    | ✓      | ✓      |
 | CornerPin2D | ✓      | ✓      |

# 2D nodes from 3D export
   Node     | Import |
 |------------|--------|
 | RotoPaint  | ✓      |
 | Tracker    | ✓      |
 | Transform  | ✓      |
 | GridWarp   | ✓      |
 | SplineWarp | ✓      |
 | CornerPin  | ✓      |


### Script
 | Knob                     | Import | Export          |
 |----------------------------|--------|-----------------|
 | Width/Height/Pixel Aspect  | ✓      | ✓               |
 | Frame range                | ✓      | ✓               |
 | Fps                        | ✓      | ✓               |