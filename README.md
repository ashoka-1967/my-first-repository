# my-very-first-repository
Brief Introduction of my project

# SQD Noise and Sampling Experiment

## Overview

This notebook explores the impact of classical bit-flip noise and sampling budget on the energy estimation and recovery process in Sample-based Quantum Diagonalization (SQD).

The experiment investigates how varying noise probabilities and shot counts affect the recovered energy and subspace.

## Experiment

- **Method:** Sample-based Quantum Diagonalization (SQD)
- **Molecular system:** Stretched water molecule
- **Noise model:** Classical post-sampling bit-flip noise
- **Noise levels:** 0%, 2%, 5%, 10%, and 15%
- **Shot counts:** 1,000, 5,000, 10,000, and 20,000
- **Recovery:** Iterative configuration recovery and subspace diagonalization

## Open the Notebook in Google Colab

Click the badge below to open the notebook in Google Colab.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ashoka-1967/my-first-repository/blob/main/SQD_noise_sampling_experiment.ipynb)

## Objectives

- Investigate the effect of sampling noise on SQD energy.
- Examine the role of shot count in sampling and recovery.
- Study the behaviour of the recovered subspace.
- Explore the robustness of iterative recovery under classical bit-flip perturbations.
- Visualize the results using heatmaps.

## Results

The notebook includes computational experiments, energy comparisons, heatmap visualizations, and interpretation of the observed results.

## Technologies

- Python
- Qiskit
- NumPy
- Matplotlib
- Jupyter Notebook
- Google Colab

## Author

Ashoka Choudhury
