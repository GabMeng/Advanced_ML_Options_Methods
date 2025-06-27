# Advanced_ML_Options_Methods
This project implements European option pricing using the Heston stochastic volatility model, enhanced with PCA and autoencoders to detect and filter synthetic ("fake") implied volatility surfaces. Includes data generation, Fourier inversion pricing, and implied volatility extraction for use in quantitative finance and machine learning.
---

## Project Highlights

* Implements **Heston model pricing** via Fourier inversion using characteristic functions
* Supports **Latin Hypercube Sampling (LHS)** for synthetic data generation
* Uses **PCA (Principal Component Analysis)** to compress implied volatility surfaces and identify their key drivers and detect "fake" ones wit a z-score approach
* Trains an **autoencoder** to reconstruct real implied volatility surfaces and detect "fake" or anomalous ones making use of reconstruction error

---

## Applications

* Quantitative research in derivative pricing
* Synthetic data generation and filtering for machine learning models
* Risk management, volatility modeling, and surface validation

---
