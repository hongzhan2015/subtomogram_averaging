# Generatl Documentation Performing Subtomogram Averaging

Here are some quick documentation for performing subtomogram averaging using variety of programs. 

# Software
Here are well-known programs used in the Cryo-electron tomography methods for different steps and purposes:

## Preprocessing
**IMOD/etomo** Used for alignment and generate tomograms. website: [imod](https://bio3d.colorado.edu/imod/)
**ISONET** Used for missing-wedge correction by machine learning: [isonet](https://github.com/IsoNet-cryoET/IsoNet)
**DEEPICT** Used for structure segmentation by deep learning: [deepict](https://github.com/IsoNet-cryoET/IsoNet)
**PySeg** Used for membrane segmentation and template-free particle picking

## Software package
A few software packages that integrate many algorithm for easy usage.
**Scipion** CryoEM software package for data processing
**EMAN2 v2.99** CryoEM software package used for single particle and tomographic data analysis, howerver, it requires raw-tilt images. 
**Relion4** Latest softare for doing single particle analysis and subtomogram averaging
**PEET** Classic subtomogram averaging program
**emClarity** Software package using for subtomogram averaging using GPUs
**pyTom** Software package doing subtomogram averaging

## PyTom
Quick documentation to illustrate how to import data

