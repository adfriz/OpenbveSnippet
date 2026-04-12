# 📄 OpenBVE B3D Object Prefix List

List of available prefixes for the B3D object format (`.b3d`).

| Prefix | Command | Description |
| :--- | :--- | :--- |
| `mb` | `[MeshBuilder]` | Start a new section of faces. |
| `vex` | `Vertex` | Create a vertex with spatial (v) and normal (n) coordinates. |
| `vexx` | `Vertex4x` | Insert Vertex command 4 times. |
| `fc` | `Face` | Create a face from vertex indices (clockwise order). |
| `fcc` | `Face 4x` | Insert Face command 4 times with unique placeholders. |
| `fc2` | `Face2` | Create a double-sided face. |
| `fc22` | `Face2 4x` | Insert Face2 command 4 times with unique placeholders. |
| `cb` | `Cube` | Create a centered cube. |
| `cy` | `Cylinder` | Create a frustum/prism. |
| `tl` | `Translate` | Translate vertices created so far in current section. |
| `tll` | `TranslateAll` | Translate all vertices in the file. |
| `sc` | `Scale` | Scale vertices created so far in current section. |
| `scc` | `ScaleAll` | Scale all vertices in the file. |
| `rt` | `Rotate` | Rotate vertices created so far in current section. |
| `rtt` | `RotateAll` | Rotate all vertices in the file. |
| `mr` | `Mirror` | Mirror vertices created so far in current section. |
| `mrr` | `MirrorAll` | Mirror all vertices in the file. |
| `sh` | `Shear` | Perform shear mapping on current section vertices. |
| `shh` | `ShearAll` | Shear all vertices in the file. |
| `col` | `SetColor` | Set color for faces in current section (0-255). |
| `cola` | `ColorAll` | Set color for ALL faces in object. |
| `ec` | `EmissiveColor` | Set emissive color for current section. |
| `eca` | `EmissiveColorAll` | Set emissive color for ALL faces in object. |
| `bm` | `BlendMode` | Set blend mode and glow attenuation. |
| `wm` | `WrapMode` | Texture tiling behavior. |
| `lo` | `Load` | Load texture for current section. |
| `tra` | `Transparent` | Screendoor transparency color key. |
| `coo` | `Coordinates` | Associate texture coordinates (0-1) to vertex index. |
| `cooo` | `Coordinates 4x` | Insert Coordinates command 4 times. |
