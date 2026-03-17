Binary classification model predicting loan defaults using the LendingClub dataset (2014–2018).

**Best Model:** LightGBM — F1: 0.7716 | ROC-AUC: 0.9589

## What's Inside
- Full EDA on 2.7M loan records
- Feature engineering & data leakage prevention
- Model comparison: Logistic Regression, Random Forest, XGBoost, LightGBM
- Threshold tuning & bias analysis
  
- ## How to Run
1. Download the LendingClub dataset from Kaggle
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebooks/credit_risk_education_material.ipynb` in Jupyter

## Tech Stack
Python · Pandas · Scikit-learn · XGBoost · LightGBM
