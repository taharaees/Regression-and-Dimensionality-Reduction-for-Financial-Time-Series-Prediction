# Regression and Dimensionality Reduction for Financial Time Series Prediction

This project analyzes and predicts **S&P 500 index daily returns** using multiple regression and dimensionality reduction techniques.  
The objective is to compare analytical (OLS, SVD), iterative (Gradient Descent), and regularized (Ridge) regression approaches, along with **PCA-based feature reduction**, for modeling financial time series.

---

## Project Overview

| Section | Description |
|----------|--------------|
| **Dataset** | Daily S&P 500 prices (2015–2025) from Yahoo Finance |
| **Goal** | Predict next-day returns using historical indicators |
| **Methods Used** | OLS, SVD, Gradient Descent, PCA, Ridge Regression |
| **Evaluation Metric** | Mean Squared Error (MSE) |
| **Visualization Tools** | Correlation Heatmap, Singular Value Spectrum, PCA Scree Plot, Ridge λ Curve, Loss Convergence |

The study demonstrates how **regularization and dimensionality reduction** improve model generalization and stability — key principles in **quantitative finance** and **machine learning**.

---

## Environment Requirements

You can recreate this project in any Python 3.10+ environment (e.g., VS Code, JupyterLab, Google Colab).
