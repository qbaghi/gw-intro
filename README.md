# Introduction to Gravitational Wave Data Analysis

A short introduction to working with gravitational wave data, with an emphasis on spectral analysis.
This is a fork from [this repository](https://github.com/jkanner/gw-intro) adapted for [EIDD Engineering School](https://u-paris.fr/eidd/en/homepage/) projects.

For more information, see https://gwosc.org

## Use either option below to run the tutorials in your browser

### Option 1: Run the tutorials in mybinder

 * Click the badge:   [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jkanner/gw-intro/main)

### Option 2: Run the tutorials in Google Co-lab

* Click the badge: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jkanner/gw-intro/blob/main)

### Option 3: Run the tutorials locally

* Clone the repository by running
```
git clone git@github.com:qbaghi/gw-intro.git
```
or by clicking on Code/Download ZIP on the repository page.
* Go to the directory and create a conda environment
```
cd gw-intro
conda env create --name introenv --file=environment.yml
```
* Activate the environment
```
conda activate introenv
```
* Make the environment accessible to Jupyter
```
python -m ipykernel install --user --name=introenv 
```
* Run Jupyter and access the provided URL.
```
jupyter notebook
```
* You can run the first notebook by opening it and selecting the kernel "introenv" on the upper right of the page.

## Video Lectures

[Recorded Lectures](https://labcit.ligo.caltech.edu/~jkanner/gwosc/intro-course/) accompany these tutorials.

## Addtional instructions

See [Open Data Workshop 2021](https://github.com/gw-odw/odw-2021/blob/master/setup.md) for video help and other software setup suggestions.

## Acknowledgement

This research has made use of data or software obtained from the Gravitational Wave Open Science Center (gwosc.org), a service of the LIGO Scientific Collaboration, the Virgo Collaboration, and KAGRA.  Materials inspired by the GW Open Data Workshop, at https://github.com/gw-odw
