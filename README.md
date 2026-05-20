

## About

This repository contains the code and materials required to reproduce the machine learning experiments investigating non-invasive prediction of gallstone disease using demographic characteristics, bioimpedance analysis (BIA) parameters, and laboratory biomarkers.

The study evaluates four gradient boosting machine learning algorithms—XGBoost, LightGBM, CatBoost, and HistGradientBoosting—for binary classification of gallstone-positive and gallstone-negative individuals in a retrospective clinical cohort comprising 319 participants. Model performance was assessed using repeated stratified 10-fold cross-validation with discrimination, calibration, and clinical utility metrics, including AUC-ROC, accuracy, F1-score, sensitivity, specificity, Brier score, and decision curve analysis. Model interpretability was examined using SHAP analyses, and feature ablation experiments were conducted to quantify the contribution of demographic, bioimpedance, and laboratory feature groups.

The .ipynb file in the repository contains the code for the entire research. The research is conducted in Google Colaboratory (version 2026.4).  
