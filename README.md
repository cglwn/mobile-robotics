# mobile-robotics
MATLAB/Python Jupyter Notebooks for Mobile Robotics.
A lot of this code is based on code presented in the University of Waterloo's ME 597 - Autonomous Mobile Robotics class.
The class required MATLAB, but I prefer Python so I try to do a bit of both to understand some of the shortcomings that may still exist in Python.

# Usage
This repository may be used either for viewing online or tinkering with on your own machine.

## Viewing Online

###GitHub
GitHub has an Jupyter notebook renderer.
Simply open any of the ipynb files on the [repository](https://github.com/cglwn/mobile-robotics-jupyter).


###Binder
[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/cglwn/mobile-robotics-jupyter)
Binder lets you modify and run the code in these notebooks in your browser.
Just click the Binder badge above or head over to this [link](http://mybinder.org/repo/cglwn/mobile-robotics-jupyter).
2

## Viewing Locally
To run this code on your machine you will need MATLAB and Jupyter installed.

### Installation
You will have to buy MATLAB.
These programs may work with Octave but I haven't tested it myself, file a bug if something doesn't work and I'll see how I can help.

Jupyter is a free Python tool for interactive computing.
There are many ways to install Jupyter but the easiest is using `conda`.
Download it [here](http://continuum.io/downloads#py34) and run the following to install all Python dependencies:

```
conda install jupyter numpy pandas
pip install matlab_kernel
```

Once you have both installed, check out this repository using

```
git clone https://github.com/cglwn/mobile-robotics.git
```

### Running Locally
To view the notebooks locally and interact with them, navigate to the repository folder and run `ipython notebook` which will open up the web application.
