# QPSC Extension Catalog

QuPath extension catalog for the [QPSC (QuPath Scope Control)](https://github.com/uw-loci/qupath-extension-qpsc) microscope acquisition system, developed at [LOCI](https://eliceirilab.org/), University of Wisconsin-Madison.

## Adding This Catalog to QuPath

1. Open QuPath (v0.6.0 or later)
2. Go to **Extensions > Manage extensions**
3. Click **Manage extension catalogs**
4. Click **Add** and enter this URL:
   ```
   https://github.com/uw-loci/qupath-catalog-qpsc
   ```
5. Click **OK** to confirm

The extensions from this catalog will now appear in the extension manager.

## Available Extensions

### QPSC - QuPath Scope Control
Microscope control and automated acquisition from within QuPath via Pycro-Manager. Supports bounded acquisition, existing image workflows, and microscope alignment.

- **Repository**: https://github.com/uw-loci/qupath-extension-qpsc
- **Installation Guide**: [QPSC Installation Guide](https://github.com/uw-loci/qupath-extension-qpsc/blob/main/documentation/INSTALLATION.md)

### PPM Modality
Polarized light microscopy (PPM) modality plugin for multi-angle acquisition sequences.

- **Repository**: https://github.com/uw-loci/qupath-extension-ppm

### Tiles to Pyramid
Stitches acquired tile images into OME-TIFF pyramidal whole slide images for viewing in QuPath.

- **Repository**: https://github.com/uw-loci/qupath-extension-tiles-to-pyramid

## Requirements

- QuPath 0.6.0 or later
- For full QPSC functionality, see the [Installation Guide](https://github.com/uw-loci/qupath-extension-qpsc/blob/main/documentation/INSTALLATION.md)

## For Developers

This catalog follows the [QuPath Extension Catalog Model](https://github.com/qupath/extension-catalog-model).
