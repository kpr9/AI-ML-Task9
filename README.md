# Credit Card Fraud Detection using Random Forest

## Overview
This project is part of **AI & ML Internship – Task 9**.  
The objective is to build a machine learning model to **detect fraudulent credit card transactions** using the **Random Forest algorithm**.

The dataset is highly imbalanced, so model performance is evaluated using **precision, recall, and F1-score** instead of accuracy.

---

## Dataset
- **File:** `creditcard.csv`
- **Target column:** `Class`
  - `0` → Non-fraud
  - `1` → Fraud  
- Features include anonymized variables (`V1`–`V28`), `Time`, and `Amount`.

---

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Joblib

---

## Methodology
1. Loaded and explored the dataset.
2. Analyzed fraud vs non-fraud class imbalance.
3. Separated features (`X`) and target (`y`).
4. Applied **stratified train-test split**.
5. Trained **Logistic Regression** as a baseline (with feature scaling).
6. Trained **Random Forest** model with `n_estimators = 100`.
7. Evaluated models using precision, recall, and F1-score.
8. Plotted feature importance.
9. Saved the trained Random Forest model.

---

## Results
- Random Forest outperformed Logistic Regression.
- Better recall and F1-score for fraud detection.
- Effectively handled imbalanced data.

---

## Deliverables
- Jupyter Notebook
- Feature importance plot
- Saved model (`fraud_detection_model.pkl`)
- README.md

---

## Author
**Raji Parasa**
