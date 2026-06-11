# 3D Fusion Models

A small collection of original 3D models designed in Autodesk Fusion and exported for viewing, slicing, and 3D printing. This repository is meant to be a simple portfolio and download library for practice models, printable objects, and CAD experiments.

Repository URL: <https://github.com/anaygoyal09/3D-Fusion-Models>

## What's Included

| Model | Files | Notes |
| --- | --- | --- |
| 2x4 Toy Block | `models/2x4 Toy Block.stl` | A toy brick-style block model with raised studs. |
| Complex Glass Bottle | `models/Complex Glass Bottle.stl` | A detailed bottle model with a wider body and complex shape. |
| Glass Soda Bottle | `models/Glass Soda Bottle.stl` | A simple bottle form made as an early Fusion modeling exercise. |
| Paper Clip | `models/Day 3 PaperClip.stl` | A thin paper clip model focused on curves and small profile geometry. |
| Door Stop | `models/DoorStop.stl`, `models/DoorStop.step` | A wedge-style door stop available as a mesh export and a STEP CAD file. |
| Handle Bar | `models/HandleBar.stl`, `models/HandleBar.3mf` | A cylindrical grip/handle bar usable as a pull, tool grip, or replacement handle. |
| Hex Nut | `models/Hex Nut.stl`, `models/Hex Nut.3mf` | A compact hardware-style model with an inner bore and chamfered shape. |
| Ice Cube Tray | `models/IceCubeTray.stl` | A larger tray-style model with repeated cavities. |
| Light Bulb | `models/LightBulb.stl`, `models/LightBulb.3mf` | A decorative incandescent-style light bulb with a rounded body and base. |
| Saturn V Rocket | `models/Saturn V Rocket.stl`, `models/Saturn V Rocket.3mf` | A rocket model available as a raw STL export and a 3MF project/export. |
| SnowFlake | `models/SnowFlake.stl`, `models/SnowFlake.3mf` | A decorative snowflake model with intricate radial symmetry. |
| Starship | `models/Starship.stl`, `models/Starship.3mf` | A tall spacecraft model available in both STL and 3MF formats. |
| Vase | `models/vase.stl` | A vase model showcasing revolve and surface workflows. |

Files are modeled in millimeters. Check dimensions in your slicer before printing.

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
│   ├── Complex Glass Bottle.stl
│   ├── Day 3 PaperClip.stl
│   ├── DoorStop.step
│   ├── DoorStop.stl
│   ├── Glass Soda Bottle.stl
│   ├── HandleBar.3mf
│   ├── HandleBar.stl
│   ├── Hex Nut.3mf
│   ├── Hex Nut.stl
│   ├── IceCubeTray.stl
│   ├── LightBulb.3mf
│   ├── LightBulb.stl
│   ├── Saturn V Rocket.3mf
│   ├── Saturn V Rocket.stl
│   ├── SnowFlake.3mf
│   ├── SnowFlake.stl
│   ├── Starship.3mf
│   ├── Starship.stl
│   └── vase.stl
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
