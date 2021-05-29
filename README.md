# CS-MRI-Recon

### Description
Comparing outputs with state of the art  [here](https://github.com/MLI-lab/ConvDecoder). <br> 

The code works on Ubuntu 20.04.1 and Windows 10
(BART was tried on Ubuntu 20.04.1)
### Setup and requirements
    apt-get update
    apt-get install python3.6     # --> or any other system-specific command for installing python3 on your system.
	pip install jupyter
	pip install numpy
	pip install matplotlib
	pip install sigpy
	pip install h5py
	pip install scikit-image
	pip install runstats
	pip install pytorch_msssim
	pip install pytorch-lightning==0.7.5
	pip install test-tube
	pip install Pillow
Clone from https://github.com/MLI-lab/ConvDecoder for utility functions

### Dataset
all files: https://drive.google.com/drive/folders/14mrihZkUoasr1a4RGqqZ0jcVIkcYNEwr?usp=sharing

Download the .nii file from https://drive.google.com/file/d/1qQPLU0bu08WvK0bCoL6gIqzCJSPyYB9N/view?usp=sharing as input for all reconstructions

### Running Files
Place any file in the root folder of the cloned repo and execute
