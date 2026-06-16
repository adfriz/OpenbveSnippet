# 📄 OpenBVE Animated Object Prefix List

List of available prefixes for the Animated object format (`.animated`).

| Prefix | Command | Description |
| :--- | :--- | :--- |
| `inc` | `[Include]` | Group other objects without animating them. |
| `pos` | `Position` | Offsets objects with respect to the root. |
| `obj` | `[Object]` | Create a single animation section. |
| `st` | `States` | Loads list of CSV/B3D/X files. |
| `sf` | `StateFunction` | Formula for state changes. |
| `txd` | `TranslateXDirection` | Direction for TranslateXFunction. |
| `tyd` | `TranslateYDirection` | Direction for TranslateYFunction. |
| `tzd` | `TranslateZDirection` | Direction for TranslateZFunction. |
| `td` | `TranslateDirectionXYZ` | Inserts all TranslateDirection commands at once. |
| `txf` | `TranslateXFunction` | Moves object on X-axis based on Formula. |
| `tyf` | `TranslateYFunction` | Moves object on Y-axis based on Formula. |
| `tzf` | `TranslateZFunction` | Moves object on Z-axis based on Formula. |
| `tf` | `TranslateFunctionXYZ` | Inserts all TranslateFunction commands at once. |
| `rxd` | `RotateXDirection` | Rotational axis for RotateXFunction. |
| `ryd` | `RotateYDirection` | Rotational axis for RotateYFunction. |
| `rzd` | `RotateZDirection` | Rotational axis for RotateZFunction. |
| `rd` | `RotateDirectionXYZ` | Inserts all RotateDirection commands at once. |
| `rxf` | `RotateXFunction` | Rotation in radians (counter-clockwise). |
| `ryf` | `RotateYFunction` | Rotation in radians (counter-clockwise). |
| `rzf` | `RotateZFunction` | Rotation in radians (counter-clockwise). |
| `rf` | `RotateFunctionXYZ` | Inserts all RotateFunction commands at once. |
| `rxda` | `RotateXDamping` | Damping for X-rotation. |
| `ryda` | `RotateYDamping` | Damping for Y-rotation. |
| `rzda` | `RotateZDamping` | Damping for Z-rotation. |
| `rda` | `RotateDampingXYZ` | Inserts all RotateDamping commands at once. |
| `sxf` | `ScaleXFunction` | Scales object on X-axis based on Formula. |
| `syf` | `ScaleYFunction` | Scales object on Y-axis based on Formula. |
| `szf` | `ScaleZFunction` | Scales object on Z-axis based on Formula. |
| `scf` | `ScaleFunctionXYZ` | Inserts all ScaleFunction commands at once. |
| `tsxd` | `TextureShiftXDirection` | Texture shift direction X. |
| `tsyd` | `TextureShiftYDirection` | Texture shift direction Y. |
| `tsxf` | `TextureShiftXFunction` | Texture shift function X. |
| `tsyf` | `TextureShiftYFunction` | Texture shift function Y. |
| `tff` | `TrackFollowerFunction` | Moves object along Rail 0 path. |
| `tov` | `TextureOverride` | Timetable or None. |
| `rr` | `RefreshRate` | Update interval for functions. |
| `etxf` | `ExtractTextureXFunction` | Scales texture on X-axis. |
| `etyf` | `ExtractTextureYFunction` | Scales texture on Y-axis. |
| `sou` | `[Sound]` | Standalone sound effect section. |
| `fn` | `FileName` | Sound file name. |
| `vol` | `Volume` | Sound volume (1.0 default). |
| `pit` | `Pitch` | Sound pitch (1.0 default). |
| `rad` | `Radius` | Radius for full volume. |
| `pons` | `PlayOnShow` | 1 = play when shown. |
| `ponh` | `PlayOnHide` | 1 = play when hidden. |
| `vf` | `VolumeFunction` | Dynamic volume control. |
| `pf` | `PitchFunction` | Dynamic pitch control. |
| `scs` | `[StateChangeSound]` | Attach sounds to preceding [Object]. |
| `fns` | `FileNames` | List of sounds for states. |