# 3D Fusion Models

A small collection of original 3D models designed in Autodesk Fusion and exported for viewing, slicing, and 3D printing. This repository is meant to be a simple portfolio and download library for practice models, printable objects, and CAD experiments.

Repository URL: <https://github.com/anaygoyal09/3D-Fusion-Models>

## What's Included

| Model | Files | Approx. dimensions | Triangles | Notes |
| --- | --- | ---: | ---: | --- |
| 2x4 Toy Block | `models/2x4 Toy Block.stl` | 31.80 x 15.80 x 11.30 mm | 11,474 | A toy brick-style block model with raised studs. |
| Glass Soda Bottle | `models/Day 2 Glass Soda Bottle.stl` | 60.00 x 59.98 x 240.00 mm | 28,334 | A simple bottle form made as an early Fusion modeling exercise. |
| Paper Clip | `models/Day 3 PaperClip.stl` | 8.25 x 33.99 x 0.75 mm | 6,432 | A thin paper clip model focused on curves and small profile geometry. |
| Complex Glass Bottle | `models/Day 4 Complex Glass Bottle.stl` | 99.48 x 78.27 x 253.00 mm | 24,530 | A more detailed bottle model with a wider body and more complex shape. |
| Door Stop | `models/DoorStop.stl`, `models/DoorStop.step` | 125.84 x 51.56 x 49.00 mm | 6,132 | A wedge-style door stop available as a mesh export and a STEP CAD file. |
| Handle Bar | `models/HandleBar.stl`, `models/HandleBar.3mf` | 43.98 x 125.00 x 43.99 mm | 25,616 | A cylindrical grip/handle bar usable as a pull, tool grip, or replacement handle. |
| Hex Nut | `models/Hex Nut.stl`, `models/Hex Nut.3mf` | 23.09 x 20.00 x 10.00 mm | 5,702 | A compact hardware-style model with an inner bore and chamfered shape. |
| Light Bulb | `models/LightBulb.stl`, `models/LightBulb.3mf` | 62.97 x 62.98 x 112.50 mm | 31,558 | A decorative incandescent-style light bulb with a rounded body and base. |
| Ice Cube Tray | `models/IceCubeTray.stl` | 310.00 x 114.00 x 32.00 mm | 34,984 | A larger tray-style model with repeated cavities. |
| Saturn V Rocket | `models/Saturn V Rocket.stl`, `models/Saturn V Rocket.3mf` | STL: 104.00 x 104.00 x 601.00 mm; 3MF: 104.00 x 104.00 x 301.00 mm | 2,634 | A rocket model available as a raw STL export and a 3MF project/export. |
| Starship | `models/Starship.stl`, `models/Starship.3mf` | 191.95 x 174.20 x 1290.00 mm | 38,208 | A tall spacecraft model available in both STL and 3MF formats. |

Dimensions are taken from exported mesh bounding boxes. The files are modeled in millimeters.

## Previewing the Models

You can preview the STL and 3MF files with common 3D viewers or slicers, including:

- Autodesk Fusion
- PrusaSlicer
- Cura
- Bambu Studio
- OrcaSlicer
- MeshLab
- Windows 3D Viewer
- macOS Preview-compatible STL viewers

## Using the Files

1. Download the model file you want from the repository.
2. Open it in a slicer or 3D modeling tool.
3. Check the scale before printing, especially if your slicer imports the model in a different unit system.
4. Choose print settings based on the model shape and your printer.
5. Slice and export the G-code for your machine.

## Suggested Print Notes

- Use supports only when the slicer preview shows unsupported overhangs.
- For thin models like the paper clip, check first-layer adhesion carefully.
- For tall bottle models, use a brim or other bed-adhesion option if your printer struggles with narrow bases.
- For tall rocket models, verify the imported height and consider splitting the print if it exceeds your printer's build volume.
- For larger models like the ice cube tray, confirm the model fits your printer bed before slicing.
- These files may need orientation, scaling, or mesh repair depending on the target printer and slicer.

## Repository Structure

```text
.
├── models
│   ├── 2x4 Toy Block.stl
│   ├── Day 2 Glass Soda Bottle.stl
│   ├── Day 3 PaperClip.stl
│   ├── Day 4 Complex Glass Bottle.stl
│   ├── DoorStop.step
│   ├── DoorStop.stl
│   ├── HandleBar.3mf
│   ├── HandleBar.stl
│   ├── Hex Nut.3mf
│   ├── Hex Nut.stl
│   ├── IceCubeTray.stl
│   ├── LightBulb.3mf
│   ├── LightBulb.stl
│   ├── Saturn V Rocket.3mf
│   ├── Saturn V Rocket.stl
│   ├── Starship.3mf
│   └── Starship.stl
└── README.md
```

## About the Project

This repository tracks models made while practicing Fusion workflows such as:

- Sketching and constraining profiles
- Extruding and revolving geometry
- Building repeated features
- Creating rounded and curved objects
- Exporting printable STL meshes

The models are organized as standalone STL and 3MF exports so they can be downloaded and opened directly without needing the original Fusion project files.

## License

No license file is currently included. Until a license is added, assume the models are shared for viewing and personal reference only. Add a license if you want others to know exactly how they may use, remix, or print the files.
