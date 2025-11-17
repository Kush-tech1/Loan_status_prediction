# 💳 Loan Status Prediction

## 📘 Overview
Compact Jupyter-notebook project that predicts loan approval (binary: 0:reject or 1;accepted) using tabular applicant data. Focus is on quick EDA, simple preprocessing, model training, and evaluation.

## ⚙️ How It Works
- Load dataset (e.g., data/loan_data.csv) and inspect target distribution.
- Clean and preprocess: impute missing values, encode categoricals, create derived features (e.g., total_income).
- Train models (Logistic Regression, RandomForest, XGBoost) with cross-validation.
- Evaluate on hold-out set using accuracy, precision/recall/F1, and ROC-AUC.
- (Optional) Explain results with feature importances or SHAP.

## ✨ Features
- End-to-end notebook: EDA → preprocessing → modeling → evaluation
- Baseline and tree-based model implementations
- Cross-validation and simple hyperparameter tuning
- Guidance for handling class imbalance and feature engineering
- Minimal, easy-to-update code paths for dataset and outputs

## 🛠 Tech Stack
- Python, Jupyter Notebook
- numpy, pandas, scikit-learn
- matplotlib, seaborn
- xgboost (optional)
- imbalanced-learn (optional)
