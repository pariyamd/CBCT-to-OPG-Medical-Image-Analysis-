# CBCT scans to OPG



This repo includes the following two parts:

## 1. visualizing 3d CBCT scans

notebooks on 3D visualizations of a dicom series files which is read by pydicom

In both notebooks i go thruogh the process of reading every dicom file in a directory as a slice and turning the data into a 3d numpy array ready for visualization.
using itkwidgets was easier to my experience due to better visualization and easy navigation of the 3d image
here are screenshots of the result:

![itwidgets](https://github.com/pariyamd/Dicom-3D-visualization/blob/master/itkwidgets.png)

![ipyvlume](https://github.com/pariyamd/Dicom-3D-visualization/blob/master/ipyvolume.png)

## 2.mapping 3D scans to 2D opg images

A study to reconstruct the panoramic image employing the 3D CBCT image, avoiding additional exposure to X-ray.
You can read more about this conversion in [this report](https://docs.google.com/document/d/1b4a9LcAYSSPhpFcZo0yraxrTTDJxx5zol9heroRvuls/edit?usp=sharing).

![result](https://github.com/pariyamd/Dicom-3D-visualization/blob/master/conversion_sample.jpg)



