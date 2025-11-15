```markdown
# Loan Status Prediction

Binary classification notebook to predict loan repayment (loan status).

Quick start
- Put dataset at: data/loan_data.csv (or update path in the notebook).
- Open: loan_status_prediction.ipynb
- Run cells top-to-bottom (or open in Colab via GitHub).

What it does
- EDA, missing-value handling, feature engineering
- Baseline and tree-based models (Logistic, RandomForest, XGBoost)
- Evaluation: accuracy, precision/recall/F1, ROC-AUC
- Optional: model explainability (feature importances / SHAP)

Reproduce
1. git clone https://github.com/Kush-tech1/Loan_status_prediction.git
2. python -m venv .venv && source .venv/bin/activate
3. pip install -r requirements.txt
4. jupyter lab

Minimal requirements (suggested)
numpy, pandas, scikit-learn, matplotlib, seaborn, xgboost, imbalanced-learn, jupyter

Notes
- Update dataset path and column names inside the notebook to match your data.
- Add a LICENSE file if you want to specify reuse terms.

```
