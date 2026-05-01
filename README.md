# Code README

This repository contains the main code used to analyse drought-induced resilience shifts in tropical forests and to examine the potential environmental drivers of these changes.

1. Code_resilience_example.py:

This code provides example scripts for estimating ecosystem resilience from remotely sensed vegetation time series.

The resilience metric used in this study is based on the first-order autoregressive coefficient, AR(1), estimated from a dynamic linear model (DLM). Following the theory of critical slowing down, higher AR(1) values indicate stronger temporal persistence and slower recovery from perturbations.

More information about this code can be found in the following references:
Liu, Y., Kumar, M., Katul, G. G. & Porporato, A. Reduced resilience as an early warning signal of forest mortality. Nat. Clim. Chang. 9, 880-885 (2019).
Zhang, Y. et al. Warming and disturbances affect Arctic-boreal vegetation resilience across northwestern North America. Nat. Ecol. Evol., 8, 2265–2276 (2024).


2. Code_Rf.py:

This code contains scripts for Random Forest modelling.

The Random Forest models were used to examine the nonlinear relationships between resilience-related responses and potential environmental drivers, such as climate, soil nutrients and vegetation conditions.

3. Code_regress.py:

This code contains scripts for regression-based sensitivity analysis.

The regression analyses were used to identify the dominant factor associated with resilience or productivity responses within different ecological units or forest biomes.

For each ecological zone, standardized single-factor coefficients were calculated between the response variable and each candidate driver. The factor with the largest absolute standardized coefficient was identified as the dominant factor for that ecological zone.

## Requirements
- Python 3.8+
- Required packages: pandas, numpy, scipy, scikit-learn, statsmodels (if applicable)
- See individual scripts for specific imports.
