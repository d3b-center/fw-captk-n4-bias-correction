# CaPTk N4 Bias Correction

Flywheel gear that implements CaPTk's [n4 bias correction](https://cbica.github.io/CaPTk/preprocessing_biasN4.html). Gear takes one image as input and outputs the n4 corrected image.

## Dependencies:
- CaPTk (gear uses the existing Docker container 2021.03.29)

## Required inputs:
- Image (nifti)

## Optional configuration:
- output file name (defaults to image_biasCorr.nii.gz)
