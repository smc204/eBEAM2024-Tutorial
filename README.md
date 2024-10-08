# Introduction to *HyperSpy*, *LumiSpy* and *eXSpy*

> **Spectroscopy Data Analysis in Python Using [HyperSpy](https://hyperspy.org)**

Tutorial for the **[eBEAM2024](https://ebeam2024.sciencesconf.org/) school on nano-optics with free electrons**

> Aussois, September 1-13, 2024

---------------

**Dear attendants of the eBEAM summer school,**

we are happy to introduce you to data analysis using [HyperSpy](https://hyperspy.org) and its extensions [LumiSpy](https://lumispy.org) and [exSPy](https://hyperspy.org/exspy) at the eBEAM 2024. 

To follow the interactive tutorials and make maximum use of the limited time available, we kindly ask you to bring your laptop and already install the **[HyperSpy-bundle](https://hyperspy.org/hyperspy-bundle/)** matching your system before coming to the school. The [HyperSpy bundle](https://hyperspy.org/hyperspy-bundle/) ships a python environment including all relevant packages.

## Installing HyperSpy

Follow the [installation guide for the HyperSpy bundle](https://hyperspy.org/hyperspy-bundle/install.html).

If you already have python installed on your system and prefer not installing the bundle, we recommend creating a new environment for the tutorial and installing at least the following packages using *pip* or *conda*:

``hyperspy, exspy, lumispy, hyperspy-gui-ipywidgets, jupyter-lab, numba``

Otherwise, have a look at the full [list of packages included in the HyperSpy-bundle](https://hyperspy.org/hyperspy-bundle/index.html#included-software-and-libraries).

## Download tutorial for local execution:

The tutorials are based on [Jupyter Notebooks](http://jupyter.org/).

**[Download the tutorial notebooks and demo data as zip file](https://github.com/LumiSpy/eBEAM2024-Tutorial/archive/refs/heads/main.zip)** from this repository and unpack in a local directory.

The tutorial is split in three jupyter notebooks to cater both for participants with ot without precious experience using HyperSpy:
- `1_Intro_HyperSpy-LumiSpy-eXSpy.ipynb` - A basic introduction to HyperSpy to get started with core functionalitie
- `2_AdvancedExamples_HyperSpy-LumiSpy-eXSpy.ipynb`- Some more advanced usages examples for users with previous experience
- `3_MachineLearning_Plasmonic_EELS_BlindSourceSeparation.ipynb` - A dedicated file introducing the machine learning features for denoising and decomposition of spectral maps

The relevant datasets are provided in the subfolder `data`.

## Introduction to python

If you are new to programming or programming with python, we recommend the [W3 schools Python Tutorial](https://www.w3schools.com/python/default.asp).


## Visualising and running the tutorials online:

(Non-interactive) Visualizing the tutorial notebooks online:

[![Notebook Viewer (nbviewer)](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg?sanitize=true)](https://nbviewer.org/github/lumispy/eBEAM2024-Tutorial/tree/main/)

(Interactive) Running the tutorial notebooks online (may be slow):

[![Live demos (Binder)](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/lumispy/eBEAM2024-Tutorial/main)
