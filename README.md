# Copula-Based Asset Price Simulation

This project demonstrates the simulation of asset prices using a copula-based approach, specifically the Clayton copula. The primary objective is to model and analyze the dependency structure between two assets, compute their cross-correlation, and visualize the results.

## Features

- **Clayton Copula Simulation:** Generates dependent random variables for asset price simulation.
- **Geometric Brownian Motion (GBM):** Simulates asset prices based on the given drift (`mu`), volatility (`sigma`), and copula-generated dependency.
- **Cross-Correlation Analysis:** Calculates and visualizes the cross-correlation between the simulated asset price series.
- **Interactive Notebook:** Provides a step-by-step demonstration of the simulation process and results visualization.

## Requirements

To run the notebook, ensure the following Python packages are installed:

- `numpy`
- `matplotlib`
- `numba`

