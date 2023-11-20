# Synthetic Aperture Scatter Imaging

Official repository for [*Synthetic Aperture Scatter Imaging*]
[Paper Link](https://ieeexplore.ieee.org/abstract/document/10306269)


Core packages:
* opencv
* scikit-image
* scipy
* torch 1.9.0+cu102
* numpy

Folders & files:
* datasets: contain scatter images of targets 'usaf' (resolution chart), 'a', 'osc', and 'uoa' at positions 0~50mm on the stage.
* Demo.ipynb: a demo of experimental reconstructions. Change target_name to switch between 'usaf' (resolution chart), 'a', 'osc', or 'uoa'.
* Demo_simulation.ipynb: a demo of synthetic reconstruction of the resolution chart.
* requirements.txt: all packages on UA HPC. Note some packages are not required by the demo notebooks.
* USAF_Resolution_Chart_A1-780.jpg: simulation resolution chart. [Source](https://www.thorlabs.com/images/TabImages/USAF_Resolution_Chart_A1-780.jpg)
* RemoteSensing: demo of experimental and synthetic reconstruction including data for remote sensing.
