# Comparative Evaluation of Advanced Gradient Boosting Models for Predicting Salt Adsorption Capacity

A machine learning study evaluating advanced gradient boosting models for predicting the salt adsorption capacity (SAC) of faradic materials used in capacitive deionization (CDI).

## Overview

The study compares XGBoost, LightGBM, CatBoost, NGBoost, GBDT, Random Forest, SVM, and ANN using a dataset of 510 observations and four predictors:

- Specific capacitance (Cs)
- Specific surface area (SSA)
- Electrolyte concentration (EC)
- Applied voltage (AV)

Two evaluation protocols were used: fixed 80:20 train-test evaluation and nested five-fold cross-validation with out-of-fold predictions. :chatgpt-content-reference{index="0"}

## Key Results

- **Study 1:** Tuned CatBoost achieved the best fixed-test performance with **MAE = 5.110 mg g⁻¹** and **RMSE = 7.502 mg g⁻¹**.
- **Study 2:** XGBoost achieved the best nested OOF performance with **MAE = 5.2252 mg g⁻¹**, **RMSE = 7.9470 mg g⁻¹**, and **R² = 0.8649**.
- **SHAP analysis:** Specific capacitance (Cs) and electrolyte concentration (EC) were consistently the two most influential features. :chatgpt-content-reference{index="1"}

## Methods

- Gradient boosting and ensemble regression
- Hyperparameter optimization
- Five-fold cross-validation
- Nested cross-validation
- Out-of-fold prediction
- SHAP-based model interpretation

## Repository Contents

This repository contains the dataset, computational notebooks, analysis, and supporting material associated with the study.

## Authors

**Ishan Jain · Yash Agarwal · Pratham R Shenoy**

MIT, Manipal
