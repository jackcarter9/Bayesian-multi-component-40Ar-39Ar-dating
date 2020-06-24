# A Bayesian approach to the deconvolution of 40Ar-39Ar data from mixtures
Code and data for the paper:   A Bayesian approach to the deconvolution of 40Ar-39Ar data from mixtures


This repository contains the input data and code associated with the paper:

A Bayesian approach to the deconvolution of 40Ar/39Ar data from mineral mixtures

Within this github repository are the following folders:

##Data - Contains all data used in the case studies in the paper

##Code - This folder contains IPython/Jupyter notebook files that create all outputs and figures in the paper,. The 'Vanlaningham&Mark' folder contains four notebooks for each mixture that we studied in Case Study #1. The models for Case Study #2 are in the 'Kula case study' folder. Each notebook in the ‘Vanlaningham&Mark’ and ‘Kula case study’ folders reads in a dataframe from the Data folder, then carries out the Bayesian analysis that is described in the paper. The 'Muscovite Test Model’ folder includes a notebook that first forward models the age spectrum and cumulative release curve of a synthetic muscovite mixture and then carries out our Bayesian inversion of these synthetic data, as described in the discussion section of the paper. Finally, the ‘Mars Suface Case Study’ folder includes a notebook that first forward models the age spectrum and cumulative release curve of a synthetic Martian mineral mixture and then carries out our Bayesian inversion of these synthetic data, as described in Case Study #3.
