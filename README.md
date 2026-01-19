# Monte Carlo Verification for BER Analysis of a Neuromorphic Neuron

This repository contains Jupyter Notebook files provided as supplementary
material for the term project titled:

**"Bit Error Rate Analysis of a Threshold-Based Neuromorphic Neuron under
Noisy Excitatory and Inhibitory Synaptic Inputs"**

## Purpose
The main results of the project are derived analytically using probability
theory and concepts covered in the course. The notebooks included in this
repository are used **only to verify** the analytical expressions numerically
and to visualize the analytical behavior of the bit error rate (BER).

## Files
- `monte_carlo_verification.ipynb`  
  Performs Monte Carlo verification of the analytical false positive,
  false negative, and bit error rate (BER) expressions.

- `ber_vs_threshold.ipynb`  
  Plots the analytical BER as a function of the decision threshold.

## How to Run
The notebooks can be opened and executed using Jupyter Notebook or
JupyterLab. All required libraries are standard Python scientific packages
(NumPy, SciPy, Matplotlib).

## Important Note
Monte Carlo simulation is not used as a solution method in this project.
All main results reported are obtained analytically.
