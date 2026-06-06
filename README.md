# 3D Fusion Models

A small collection of original 3D models designed in Autodesk Fusion and exported as STL files. This repository is meant to be a simple portfolio and download library for practice models, printable objects, and CAD experiments.

Repository URL: <https://github.com/anaygoyal09/3D-Fusion-Models>

## What's Included

| Model | File | Approx. dimensions | Triangles | Notes |
| --- | --- | ---: | ---: | --- |
| 2x4 Toy Block | `models/2x4 Toy Block.stl` | 31.80 x 15.80 x 11.30 | 11,474 | A toy brick-style block model with raised studs. |
| Glass Soda Bottle | `models/Day 2 Glass Soda Bottle.stl` | 60.00 x 59.98 x 240.00 | 28,334 | A simple bottle form made as an early Fusion modeling exercise. |
| Paper Clip | `models/Day 3 PaperClip.stl` | 8.25 x 33.99 x 0.75 | 6,432 | A thin paper clip model focused on curves and small profile geometry. |
| Complex Glass Bottle | `models/Day 4 Complex Glass Bottle.stl` | 99.48 x 78.27 x 253.00 | 24,530 | A more detailed bottle model with a wider body and more complex shape. |
| Ice Cube Tray | `models/IceCubeTray.stl` | 310.00 x 114.00 x 32.00 | 34,984 | A larger tray-style model with repeated cavities. |

Dimensions are taken from the exported STL bounding boxes and are likely in millimeters if exported from Fusion using the default metric workflow.

## Previewing the Models

You can preview the STL files with any common 3D viewer or slicer, including:

- Autodesk Fusion
- PrusaSlicer
- Cura
- Bambu Studio
- OrcaSlicer
- MeshLab
- Windows 3D Viewer
- macOS Preview-compatible STL viewers

## Using the Files

1. Download the STL file you want from the repository.
2. Open it in a slicer or 3D modeling tool.
3. Check the scale before printing, especially if your slicer imports the model in a different unit system.
4. Choose print settings based on the model shape and your printer.
5. Slice and export the G-code for your machine.

## Suggested Print Notes

- Use supports only when the slicer preview shows unsupported overhangs.
- For thin models like the paper clip, check first-layer adhesion carefully.
- For tall bottle models, use a brim or other bed-adhesion option if your printer struggles with narrow bases.
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
│   └── IceCubeTray.stl
└── README.md
```

## About the Project

This repository tracks models made while practicing Fusion workflows such as:

- Sketching and constraining profiles
- Extruding and revolving geometry
- Building repeated features
- Creating rounded and curved objects
- Exporting printable STL meshes

The models are organized as standalone STL exports so they can be downloaded and opened directly without needing the original Fusion project files.

## License

No license file is currently included. Until a license is added, assume the models are shared for viewing and personal reference only. Add a license if you want others to know exactly how they may use, remix, or print the files.
