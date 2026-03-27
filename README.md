# 🧪 QSAR Modeling Pipeline

An end-to-end Quantitative Structure–Activity Relationship (QSAR) modeling workflow for drug discovery, integrating descriptor preprocessing, feature selection, machine learning modeling, and rigorous validation.

---

## 📌 Overview

This repository implements a complete QSAR pipeline including:

- Descriptor cleaning and normalization (Z-score)
- Low-information descriptor removal
- Data splitting using K-Means clustering
- Feature selection (Pearson correlation, VIF, LASSO)
- Model development:
  - Multiple Linear Regression (MLR)
  - Partial Least Squares (PLS)
- Model validation:
  - Cross-validation (Q²)
  - Y-randomization
  - Applicability Domain (Williams plot)
- Visualization:
  - PCA plots
  - Residual plots
  - Learning curves
- Virtual screening and prediction

---

## ⚙️ Workflow

