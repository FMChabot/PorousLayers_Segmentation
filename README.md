# X-Ray Tomography - Analysis of porous layers deformation in electrolyzer

## Image filtering and detection of porous layers surface
Two Jupyter Notebook are used:
- DeformationAnalysis.ipynb       → Process the prealigned cross section images to detect porous layers edges
- DeformationAnalysis_Plots.ipynb → Average results through the tomograph and plot data

## Pre-Process:
- Rotate cross-sections to align vertically the assembly with the PTL on the left side of images
- Crop the images to reduce the size of the tomograph
- (Optionnal) Convert it to 16 or 8 bit: increase the algorithm speed but may affects the GDL results


# Requirements: 
  - Python Libraries: Pandas, PIL, Skimage, Scipy
