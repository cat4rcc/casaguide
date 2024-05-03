# CASA Guide: BETA TEST

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cat4rcc/casaguidebetaready/HEAD)

#Claire's CASA Guide Beta Test Ready Version

This Guide is a work in progress.  The guide is designed to be an interactive introduction to CASA, Common Astronomy Software Applications Package, which is used to processes data from radio telescopes. 

## This repository contains:

| File  | Description  |
| -------- | ------- |
| `DockerFile.txt` | This file has the information to create a python environment capable of running the guide. This file was created by Aard Keimpema, Tammo Jan Dikema, and Bruno Juncklaus Martins and is available [here](https://github.com/aardk/jupyter-casa) |
| `requirements.txt` | contains the required dependencies to run the Guide  |
| `GetData.ipynb` | Installs casatasks, casatools, astropy, and casadata. Downloads and expands the needed Images, Premade Masks and Measurement sets hosted on Box [here]({https://virginia.box.com/s/qhc736l24ikriadqvflnf0drhed7ll9z) |
| `CASAGuideIntro.ipynb` | An introduction to CASA. Includes: What is a Radio Telescope, What is an Interferometer, Key Parameters for Cleaning Data and More!  |
| `GuideCleanCont.ipynb` |  How to Clean Continuum data (Interactive Activity)   |
| `GuideCleanLine.ipynb`  | How to Clean Line data (Interactive Activity) |  
| `movie.py` | Makes gif files from set of channel maps generated |
| `newmom0.py` | Makes moment 0 maps  |
| `plot_all.py` | Plots all channels in a grid  |
| `plot_cont.py`  | Plots the continuum  |  
| `Beamsize.py`  | Calculates the size of the beam. Can be used to determine image size |
| `movie.gif` | Sample gif file |


Download the files and run in your own environment or use mybinder:   [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cat4rcc/casaguidebetaready/HEAD)

This guide can be launched in mybinder. The Dockerfile.txt file will produce the correct environment in mybinder. After Launching run the GetData.ipynb Jupyter Notebook to download the measurements set, images, and premade masks. This file will also install casatasks, casatools, and other files and packages required to run the guide smoothly. 

After running the cell in GetData.ipynb, explore the Introduction, try cleaning the continuum, and then try cleaning the line data! 
