# 📄 OpenBVE CSV Object Prefix List

List of available prefixes for the CSV object format (`.csv`).

| Prefix | Command | Description |
| :--- | :--- | :--- |
| `cmb` | `CreateMeshBuilder` | Marks beginning of new section of faces. |
| `av` | `AddVertex` | Creates new vertex with position and optional normals. |
| `avv` | `AddVertex4x` | Insert AddVertex command 4 times. |
| `af` | `AddFace` | Creates face from vertex indices (clockwise order). |
| `aff` | `AddFace 4x` | Insert AddFace command 4 times with unique placeholders. |
| `af2` | `AddFace2` | Creates double-sided face. |
| `af22` | `AddFace2 4x` | Insert AddFace2 command 4 times with unique placeholders. |
| `cb` | `Cube` | Creates centered cube. |
| `cy` | `Cylinder` | Creates frustum/prism. |
| `tl` | `Translate` | Translates current section vertices. |
| `tll` | `TranslateAll` | Translates all vertices in object. |
| `sc` | `Scale` | Scales current section vertices. |
| `scc` | `ScaleAll` | Scales all vertices in object. |
| `rt` | `Rotate` | Rotates current section vertices around axis (X,Y,Z) by Angle degrees. |
| `rtt` | `RotateAll` | Rotates all vertices in object around axis (X,Y,Z) by Angle degrees. |
| `mr` | `Mirror` | Mirrors current section vertices (1=true, 0=false for X,Y,Z). |
| `mrr` | `MirrorAll` | Mirrors all vertices in object (1=true, 0=false for X,Y,Z). |
| `sh` | `Shear` | Shear mapping for current section. |
| `shh` | `ShearAll` | Shear mapping for all vertices. |
| `scr` | `SetColor` | Sets vertex color (0-255). |
| `scra` | `SetColorAll` | Sets color for ALL faces in object. |
| `sec` | `SetEmissiveColor` | Sets emissive color (ignores lighting). |
| `seca` | `SetEmissiveColorAll` | Sets emissive color for ALL faces in object. |
| `sbm` | `SetBlendMode` | Sets blend mode and glow attenuation. |
| `swm` | `SetWrapMode` | Texture tiling behavior. |
| `lt` | `LoadTexture` | Loads texture for current section. |
| `sdtc` | `SetDecalTransparentColor` | Transparency color key for textures. |
| `ecf` | `EnableCrossfading` | Controls blending between day and night textures. |
| `stc` | `SetTextureCoordinates` | Associates texture UV (X, Y) to vertex index. |
| `stcc` | `SetTextureCoordinates 4x` | Insert SetTextureCoordinates command 4 times. |