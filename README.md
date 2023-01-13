# GC-origin-ANNclassifier
Implementation of an artificial neural network to predict the origin of globular clusters in external galaxies from their observed properties

This repository contains the ANN model and a Jupyter notebook showing an example of its use to predict the origin labels (in-situ or accreted) of observed globular clusters. The ANN classifier is described and tested on simulated and real data for the Milky Way GC system in Trujillo-Gomez et al. (submitted). In its simplest form, the model only requires as input features the metallicities $\rm{[Fe/H]}$, projected galactocentric distances $R_p$, and radial velocities $V_p$ of the clusters, in addition to the stellar mass $M_*$, effective radius $R_e$, and mean metallicity of their host galaxy $\rm{[Fe/H]}_{gal}$. 

The code will be released publicly upon publication of the paper. If you are interested in using the model prior to its release, please contact the author at strujill@gmail.com.
