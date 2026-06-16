# 📄 OpenBVE Route CSV Prefix List

List of available prefixes for the Route CSV format (`.csv`).

| Prefix | Command | Description |
| :--- | :--- | :--- |
| `opt.len` | `Options.UnitOfLength` | Sets the unit of length conversion factor. |
| `opt.spd` | `Options.UnitOfSpeed` | Sets the unit of speed conversion factor. |
| `opt.blk` | `Options.BlockLength` | Sets the block length (default 25m). |
| `opt.vis` | `Options.ObjectVisibility` | Sets object visibility mode (Legacy, Track-based, Quad-Tree). |
| `rou.com` | `Route.Comment` | Sets the route description/comment. |
| `rou.img` | `Route.Image` | Sets the preview image for the route. |
| `rou.tt` | `Route.Timetable` | Sets the text for the default timetable. |
| `rou.amb` | `Route.AmbientLight` | Sets the ambient light color (RGB). |
| `rou.dir` | `Route.DirectionalLight` | Sets the directional light color (RGB). |
| `rou.ldir` | `Route.LightDirection` | Sets the light direction angles (Theta, Phi). |
| `trn.fld` | `Train.Folder` | Sets the default train folder. |
| `trn.vel` | `Train.Velocity` | Sets the maximum speed for preceding trains. |
| `str.rail` | `Structure.Rail.Load` | Loads a rail object. |
| `str.grnd` | `Structure.Ground.Load` | Loads a ground object. |
| `str.free` | `Structure.FreeObj.Load` | Loads a free object. |
| `str.walll` | `Structure.WallL.Load` | Loads a left wall object. |
| `str.wallr` | `Structure.WallR.Load` | Loads a right wall object. |
| `str.forml` | `Structure.FormL.Load` | Loads a left platform edge object. |
| `str.formr` | `Structure.FormR.Load` | Loads a right platform edge object. |
| `str.beac` | `Structure.Beacon.Load` | Loads a beacon object. |
| `with` | `With Track` | Prefixes subsequent commands starting with a period with 'Track'. |
| `trk.rail` | `Track.RailStart` | Starts a new rail with index, offsets, and type. |
| `trk.railu` | `Track.Rail` | Updates an existing rail's offsets or type. |
| `trk.raile` | `Track.RailEnd` | Ends the specified rail. |
| `trk.cur` | `Track.Curve` | Sets horizontal curve radius (m) and cant (mm). |
| `trk.pit` | `Track.Pitch` | Sets vertical gradient. |
| `trk.free` | `Track.FreeObj` | Places a free object relative to a rail. |
| `trk.sta` | `Track.Sta` | Defines a station stop with all parameters. |
| `trk.stop` | `Track.Stop` | Defines a stop position marker. |
| `trk.sig` | `Track.Signal` | Places a functional signal. |
| `trk.sigf` | `Track.SigF` | Places a visual signal representation for a section. |
| `trk.sec` | `Track.Section` | Starts a signalling section with aspects. |
| `trk.lim` | `Track.Limit` | Sets a speed limit. |
| `trk.beac` | `Track.Beacon` | Places a safety system beacon. |
| `trk.bri` | `Track.Brightness` | Sets the track brightness (0-255). |
| `trk.fog` | `Track.Fog` | Sets fog conditions (distances and RGB). |
| `trk.ann` | `Track.Announce` | Plays an announcement sound. |
| `trk.buf` | `Track.Buffer` | Places a bumper on Rail 0. |