# Codes and calculations for Ciocan et al. 2021 

This repository contains some of the codes and calculations (contained in Jupyter Python notebooks) associated with our recent paper about the ALMA and MUSE observations of the cool core brightest cluster galaxy in MACS 1931.8-2635 (Ciocan et al. 2021).  

The codes include:

#### Data processing codes:

+ `AlignCubes.ipynb`: a Jupyter notebook for correcting the astrometric mismatch between MUSE and Subaru data. This code mainly uses the [_MPDAF_ package][https://ui.adsabs.harvard.edu/abs/2016ascl.soft11003B/abstract], a python package specially designed to work with MUSE-specific data.

+ `MUSE_ALMA_velocity_difference_maps.ipynb`: a Jupyter notebook for creating MUSE-ALMA difference or ratio maps. For this example, we have created MUSE - ALMA velocity difference maps. 

+)How to extract a spectrum from each spaxel of data-cube: `Extract_each_spaxel_as_spectrum.ipynb`

4)How to measure fluxes with mpdaf: `Flux_measurements_mpdaf.ipynb`

5)How to plot (emission) maps: `EL_maps.ipynb`

6)How to plot BPT with shock models: `Diagnostic_diag_with_shock_grids.ipynb`

7)How to plot stellar kinematics from GIST output: `Velocity_plots_GIST.ipynb`



