# scatterPtychography

Official repository for *Scatter Ptychography*. Passed tests on UA High Performance Computing (HPC).

Core packages:
* opencv
* scikit-image
* scipy
* torch 1.9.0+cu102
* numpy

Folders & files:
* datasets/: contain scatter images of the resolution chart at positions 0~50mm.
* Demo.ipynb: a demo of experimental reconstructions. Change target_name to switch between 'usaf' (resolution chart), 'a', 'osc', or 'uoa'.
* Demo_simulation.ipynb: a demo of synthetic reconstruction of the resolution chart.
* requirements.txt: all packages on UA HPC. Note some packages are not required by the demo notebooks.
* USAF_Resolution_Chart_A1-780.jpg: simulation resolution chart. [Source](https://www.thorlabs.com/images/TabImages/USAF_Resolution_Chart_A1-780.jpg)
