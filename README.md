# ODE-constrained mixture modeling workshop

This workshop is develop with the help of chatGPT.

This repository contains Jupyter notebooks for a hands-on workshop based on the paper:

Hasenauer et al. (2014): ODE-constrained mixture modelling for analysis of heterogeneous cell populations.

----------------------------------------------------------------------
WORKSHOP OVERVIEW
----------------------------------------------------------------------

The goal of this workshop is to demonstrate how mechanistic ODE models
can be combined with statistical mixture models to analyze heterogeneous
single-cell data.

Participants will:
- simulate data from a mechanistic conversion process
- explore heterogeneity in snapshot distributions
- fit classical Gaussian mixture models
- understand their limitations
- fit an ODE-constrained mixture model
- interpret results mechanistically

----------------------------------------------------------------------
NOTEBOOKS
----------------------------------------------------------------------

1. 01_static_mixtures_vs_dynamics_conversion_process.ipynb

   Purpose:
   - Introduces the conversion-process model
   - Simulates heterogeneous populations
   - Generates synthetic snapshot data
   - Fits Gaussian mixtures independently at each time point
   - Demonstrates the "component matching problem"

2. 02_minimal_ode_constrained_mixture_model_conversion_process.ipynb

   Purpose:
   - Implements a minimal ODE-constrained mixture model
   - Fits all time points jointly
   - Estimates mechanistic parameters
   - Recovers subpopulation trajectories
   - Demonstrates hypothesis testing

----------------------------------------------------------------------
INSTALLATION REQUIREMENTS
----------------------------------------------------------------------

Python >= 3.9 recommended

Required packages:
- numpy
- scipy
- matplotlib
- scikit-learn
- pandas

Install via pip:
pip install numpy scipy matplotlib scikit-learn pandas
