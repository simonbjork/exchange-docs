

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
  | Mesh vertex         | ✓      | ✓      |

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