# Introduction to Gravitational Wave Data Analysis

A short introduction to working with gravitational wave data, with an emphasis on spectral analysis.
This is a fork from [this repository](https://github.com/jkanner/gw-intro) adapted for [EIDD Engineering School](https://u-paris.fr/eidd/en/homepage/) projects.

For more information, see https://gwosc.org

## Use either option below to run the tutorials in your browser

### Option 1: Run the tutorials in mybinder

 * Click the badge:   [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jkanner/gw-intro/main)

### Option 2: Run the tutorials in Google Co-lab

* Click the badge: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jkanner/gw-intro/blob/main)

### Option 3: Run the tutorials locally (for Linux or Mac)

1. Install Miniconda by following the installation instructions for your operating system:

     - [Linux](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html)
     - [macOS](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html)

   Choose the "Miniconda" installer, not the full Anaconda Distribution.
   You may need to restart your computer after installation.

2. Add the conda-forge channel

   `conda config --add channels conda-forge`

3. Create the environment.

   `conda env create --file environment.yml`

4. Activate the environment.

   `conda activate odw-py311`

5. Clone the workshop git repo

   `git clone git@github.com:qbaghi/gw-intro.git`

7. Move into the directory with the workshop git repo

   `cd gw-intro`

8. Build a custom [jupyter kernel](https://ipython.readthedocs.io/en/stable/install/kernel_install.html) using the command

   `python -m ipykernel install --user --name odw-py311 --display-name "Python (odw-py311)"`

9. Start the Jupyter notebook server

   `jupyter notebook` and select the kernel `odw-py311` if this is not done by default.
   
* Clone the repository by running


## Video Lectures

[Recorded Lectures](https://labcit.ligo.caltech.edu/~jkanner/gwosc/intro-course/) accompany these tutorials.

## Addtional instructions

See [Open Data Workshop 2021](https://github.com/gw-odw/odw-2021/blob/master/setup.md) for video help and other software setup suggestions.

## Acknowledgement

This research has made use of data or software obtained from the Gravitational Wave Open Science Center (gwosc.org), a service of the LIGO Scientific Collaboration, the Virgo Collaboration, and KAGRA.  Materials inspired by the GW Open Data Workshop, at https://github.com/gw-odw
