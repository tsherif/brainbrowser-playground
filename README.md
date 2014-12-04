BrainBrowser Playground
=======================

A simple environment for learning how to use [BrainBrowser](https://brainbrowser.cbrain.mcgill.ca).

Read the `index.html` file's source for instructions on how to get started.

To view your application, load this repo's root over HTTP (using, for example, [nano-server](https://www.npmjs.org/package/nano-server) or Python's [SimpleHTTPServer module](https://docs.python.org/2/library/simplehttpserver.html)), and access `index.html`.

The `models` directory contains the following files for you to visualize:
- `brain-surface.obj` (Surface Viewer): a surface file in MNI OBJ format
- `cortical-thickness.txt`(Surface Viewer): a per-vertex ("intensity") data file that can be applied to `brain-surface.obj`
- `structural.mnc.header` (Volume Viewer): header file for a structural MINC file
- `structural.mnc.raw` (Volume Viewer): raw voxel data for a structural MINC file
- `spectral.txt`: a color map should be used to colorize either the `cortical-thickness.txt` data or the `structural.mnc` volume

Refer to the [BrainBrowser Website](https://brainbrowser.cbrain.mcgill.ca) and [BrainBrowser API Documentation](https://brainbrowser.cbrain.mcgill.ca/docs) for more information.
