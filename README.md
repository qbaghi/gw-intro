# EIDD project: Introduction to Gravitational Wave Data Analysis

![Spiral Dance of Black Holes](https://www.ligo.caltech.edu/system/pages/images/24/page/Gravity_Waves_StillImage.jpg?1699659823 'Image credit: LIGO/T. Pyle')


This repository contains material for an [EIDD Engineering School](https://u-paris.fr/eidd/en/homepage/) project that will provide you with
* A short introduction to working with gravitational wave (GW) data
* How to simulate the expected gravitational-wave signals
* How to use the Fourier transform and time-frequency representations to analyse detector measurements

Note: This repository is a fork and an adaptation of [a repository used in the GW open data workshop](https://github.com/jkanner/gw-intro).

Follow the steps below to start the project:

## 1. Pre-requisite: learn about gravitational waves

To get more familiar with the gravitational waves, how they are emitted, and how they are detected, please consult the following materials:
* Watch the two videos in https://gwosc.org/path/ (Step 1 and Step 2)
* Read pages 5 to 13 of the [LIGO's educator guide](https://dcc.ligo.org/public/0123/P1600015/006/LIGOEdGuide_Final.pdf)

## 2. Run the tutorials

We will use Jupyter notebooks written in Python for this project.
Use either option below to run the tutorials in your browser.

### Option 1: Run the tutorials in Google Co-lab

1. Click the badge: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jkanner/gw-intro/blob/main)
2. Double-click the notebook of your choice
3. At the top of the notebook, uncomment any `pip install` commands by removing the `#`, like:

     `! pip install -q pycbc gwpy`

4. Click `run all` from the `runtime` menu at the top
5. You can also run the cells one by one by clickingthe Play button in the top-left corner of each cell.

### Option 2: Run the tutorials locally (for Linux or Mac)

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
   

## 3. Answer the tutorial questions

Starting with the first tutorial, please answer the questions that are asked.
Your answers constitute part of the output of this engineering project. You can either answer them within the notebooks or in a separate document.

## 4. Address the problem posed at the end of tutorial 6

In the last tutorial `intro-6-whiten-bandpass.ipynb`, the last question you are asked is more open and requires some investigation.
We will discuss the strategy you may adopt. If time permits, we will go beyond these tutorials and explore more sophisticated data analysis methods.


## Further help: Video Lectures

[Recorded Lectures](https://labcit.ligo.caltech.edu/~jkanner/gwosc/intro-course/) accompany these tutorials.
You can use them to answer the questions.

## Additional instructions

See [Open Data Workshop 2021](https://github.com/gw-odw/odw-2021/blob/master/setup.md) for video help and other software setup suggestions.

## Acknowledgement

This research has made use of data or software obtained from the Gravitational Wave Open Science Center (gwosc.org), a service of the LIGO Scientific Collaboration, the Virgo Collaboration, and KAGRA. Materials inspired by the GW Open Data Workshop, at https://github.com/gw-odw
