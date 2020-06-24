# Bayesian-multi-component-40Ar-39Ar-dating
Code and data for the paper:   A Bayesian approach to the deconvolution of 40Ar/39Ar data from multi-component mixtures

This repository constains all the material, code and data, associated with the paper: 

A Bayesian approach to the deconvolution of 40Ar/39Ar data from multi-component mixtures



Within this github repository are the following folders: 

##Code - This folder contains IPython/Jupyter notebook files that create all outputs and figures in the paper.


##Data - Contains all data used in the case studies in the paper

With Code folder is the code for each case study presented in the Paper. 
The Vanlaningham&Mark folder contains four notebooks for each mixture. Each notebook reads in a dataframe, each dataframe is the the data folder. The code read in each dataframe frame then carries out the Bayesian analysis that is described in the paper.  

The kula case studies are in the Kula case study folder. The data for these notebooks are in the data folder. Each notebook reads in a a mixture dataset and then is analysed with the Bayesian model described in the paper. 

The Muscovite test model is a forwarded then analysis dataset assuming the ages, diffusion kinetics and mixing fraction of Kula muscovite mixture one. In the code file the dataset is created and then analysed in the same fashion as all other dataset. In this model we do not constrain the mixing fraction but show that when two components have identical kinetics additional information is required to extract real geological infomation.

The final case study is in the Mars surface case study. In this notebook the datasets is forward modelled then inverted with the Bayesian model. 

 
