# kinetic-parameter-estimation-oed
Jupyter Lab workflow for kinetic parameter estimation, statistical inference, and model-based optimal experimental design (OED) in bioprocess engineering.
Parameter Estimation and Model-Based Optimal Experimental Design

## Description
This repository contains a Jupyter Lab computational workflow designed for advanced university instruction in bioprocess engineering. It demonstrates the complete cycle of kinetic parameter identification, statistical validation, and model-based optimal experimental design (OED) for a bimolecular reaction system. 

The notebook bridges the gap between theoretical mathematical concepts and their numerical implementation, providing a rigorous framework for evaluating and minimizing parameter uncertainty.

## Core Modules
* **Forward Sensitivity Analysis:** Formulation and integration of the extended ordinary differential equation system to analytically supply the Jacobian matrix to the optimization algorithm.
* **Numerical Jacobian Validation:** Precise error quantification of the analytical Jacobian against Forward Finite Differences, Central Finite Differences, and Complex Step Differentiation.
* **Statistical Inference:** Evaluation of parameter uncertainty through variance-covariance matrices, 2D linear approximation confidence ellipses, and empirical Monte Carlo distributions.
* **Optimal Experimental Design:** Implementation of D-optimal and E-optimal design criteria using a continuous relaxation approach. The workflow utilizes the Sequential Least SQuares Programming (SLSQP) algorithm coupled with Complex Step Differentiation to efficiently optimize both the discrete sampling schedule and the initial substrate concentrations.

## Dependencies
The execution of the Jupyter Notebook requires a standard scientific Python environment. 
* Python 3.8+
* Jupyter Lab
* NumPy
* SciPy
* Matplotlib

## Usage
The script is structured sequentially. Execute the cells in order to generate the synthetic data, perform the base parameter estimation, validate the numerical methods, and run the optimization for the new experimental design.

## Author and Terms of Use
**Author:** Charlotte Deffur

If you intend to utilize this material for academic teaching, research, or any commercial application, please contact me to request explicit permission prior to use.
