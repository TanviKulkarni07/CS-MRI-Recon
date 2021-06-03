# CS-MRI-Recon

### Description
This project was done as a part of EE5180 Machine Learning Course(Spring 2021) at IITM.

Perform Compressed Sensing Reconstruction and comparing outputs with [state of the art](https://github.com/MLI-lab/ConvDecoder). <br> 

### OS Requirements
The code works on Ubuntu 20.04.1 and Windows 10
(BART was tried on Ubuntu 20.04.1)

### Setup and python dependencies
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
Clone from [parent repo](https://github.com/MLI-lab/ConvDecoder). <br> for utility functions

### Dataset
all files: https://drive.google.com/drive/folders/14mrihZkUoasr1a4RGqqZ0jcVIkcYNEwr?usp=sharing

Download the .nii file from https://drive.google.com/file/d/1qQPLU0bu08WvK0bCoL6gIqzCJSPyYB9N/view?usp=sharing as input for all reconstructions

### Running Files
Place any file in the root folder of the cloned repo and execute

### References
https://arxiv.org/abs/2007.02471
https://arxiv.org/abs/1810.03982
https://dmitryulyanov.github.io/deep_image_prior
https://github.com/facebookresearch/fastMRI/tree/master/fastmri_examples/cs
