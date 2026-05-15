# Lecture 01 — Density Estimation

This folder contains practical coding work for the density estimation lecture in the Pattern Analysis course.

## Topics Covered

- Inversion sampling
- Probability density functions (PDF) and cumulative density functions (CDF)
- Histograms as density estimators
- Kernel Density Estimation (Parzen windows)
- k-Nearest Neighbor density estimation
- Bias-variance tradeoff in density estimation

## Notebook

### [01-density-estimation-explorer.ipynb](./01-density-estimation-explorer.ipynb)

This notebook combines the main ideas of the lecture into one practical mini-project:

1. Generate samples from a custom distribution using inversion sampling.
2. Reconstruct the density from samples using:
   - histogram
   - KDE / Parzen window estimator
   - k-NN density estimator
3. Compare estimator behavior under different hyperparameter choices.
4. Visualize the bias-variance tradeoff.

## Learning Goal

The purpose of this notebook is to connect the lecture theory to actual code and plots.
It is intended as both a study aid and a small portfolio project.

## How to Run

From the repository root:

```bash
jupyter notebook
```

Then open:

```text
lecture-01-density-estimation/01-density-estimation-explorer.ipynb
```

Run all cells from top to bottom.

## Notes

- The notebook is written for learning and experimentation.
- Future lectures will be added in separate folders using the same structure.
