# Data Mining UCM

Complete data mining pipeline developed as part of the Master's in Data Science 
at Universidad Complutense de Madrid.

## Structure

The notebook covers three independent datasets and analytical blocks:

### Part 1 — Data Cleaning & Regression (Agricultural Dataset)
- Full EDA and data quality validation
- Outlier detection and treatment
- Missing value analysis and imputation
- Cramér's V for feature selection
- Linear regression (complete, Lasso, backward stepwise selection)
- Logistic regression for binary target (severe pest presence)
- Cross-validation comparison of models

### Part 2 — Time Series (Spanish Industrial Production Index)
- Decomposition analysis (additive vs multiplicative)
- Holt-Winters exponential smoothing
- SARIMA modelling with auto_arima
- Residual diagnostics and forecast comparison

### Part 3 — Unsupervised Learning (Drone Delivery Dataset)
- Correlation matrix analysis
- KMO test for dimensionality reduction viability
- PCA and Factor Analysis
- K-Means clustering with silhouette and inertia analysis
- Cluster characterisation and business interpretation

## Tools
Python · pandas · scikit-learn · statsmodels · pmdarima · 
matplotlib · plotly · feature-engine · Google Colab

## Note
Developed in Google Colab. The first cell mounts Google Drive — 
skip it if running locally and load the datasets directly.
