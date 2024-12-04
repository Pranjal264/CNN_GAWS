# CNN_GAWS

This is the Git repository for the CNN model of the paper  [Deep learning-driven wavefront sensing for grating-array based wavefront sensor](https://doi.org/10.1111/jmi.13362).

## Setting up

The program was developed in Python 3.8.8. Later versions of Python should be supported but have not been tested yet.
If you are on a later version, give it a try!

I would suggest you use [Anaconda](https://www.anaconda.com/download/success) / Miniconda and set up a virtual environment as:

- `conda create -n "myenv" python=3.8.8` # replace "myenv" with your desired name.

After setting up the virtual environment, you can install the dependencies as:

- `pip install -r requirements.txt`

## Usage

- training_data_generator.ipynb : this notebook is used to generate training as well as testing data fopr the CNN model
- CNN_GAWS_v1.ipynb : this is the main notebook which predicts the aberration strengths from focal spots array

A step-by-step procedure for using each notebook is incorporated into the notebooks.

Thank you,

Pranjal Choudhury
