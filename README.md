# Codes and calculations for Ciocan et al. 2021 

This repository contains some of the codes and calculations (contained in Jupyter Python notebooks) associated with our recent paper about the ALMA and MUSE observations of the cool core brightest cluster galaxy in MACS 1931.8-2635 (Ciocan et al. 2021).  

The codes include:

#### Data processing codes:

+ `AlignCubes.ipynb`: a Jupyter notebook for correcting the astrometric mismatch between MUSE and Subaru data. This code mainly uses the _MPDAF_ package ([Bacon et al. 2016](https://ui.adsabs.harvard.edu/abs/2016ascl.soft11003B/abstract) ), a python package specially designed to work with MUSE-specific data.

+ `MUSE_ALMA_velocity_difference_maps.ipynb`: a Jupyter notebook for creating MUSE-ALMA difference or ratio maps. For this example, we have created MUSE - ALMA velocity difference maps. 

+ `Extract_each_spaxel_as_spectrum.ipynb` : a Jupyter notebook showing how to extract a spectrum from each spectral pixel (spaxel) of the MUSE data-cube; this is a relevant step of the data-processing procedure for prepearing the data for the [_FADO_ pipeline](http://spectralsynthesis.org/fado-manual-v1b-patch-10.html) ([Gomes & Papaderos 2017](https://www.aanda.org/articles/aa/abs/2017/07/aa28986-16/aa28986-16.html) )

#### Data analysis codes:

+ `Flux_measurements_mpdaf.ipynb` : a Jupyter notebook showing how to measure fluxes of strong emission lines from a galaxy spectrum using the [_MPDAF_ package] 

+ `EL_maps.ipynb`:  a Jupyter notebook showing how to plot (emission-line) maps from the output tables of the [_FADO_ pipeline]

+ `Diagnostic_diag_with_shock_grids.ipynb` : a Jupyter notebook showing how to plot the BPT diagnostic diagram ([Baldwin et al 1981](https://ui.adsabs.harvard.edu/abs/1981PASP...93....5B/abstract) )  together with predictions from [fully radiative shock models](https://iopscience.iop.org/article/10.1086/589652/meta) 

7)How to plot stellar kinematics from GIST output: `Velocity_plots_GIST.ipynb`



