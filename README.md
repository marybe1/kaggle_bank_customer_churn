# 🏆 Kaggle Competition: Bank Customer Churn Prediction Challenge

📅 **Start date:** 2025-03-28

👤 **Author:** Maria Belyakova  
LinkedIn: https://www.linkedin.com/in/mariabelyak/  
Kaggle: https://www.kaggle.com/marybel

---

## 📌 Overview

This project is part of the Kaggle competition [**Bank Customer Churn Prediction Challenge**](https://www.kaggle.com/competitions/bank-customer-churn-prediction-challenge/overview) focused on solving the problem of predicting bank customer churn.

The goal is to predict **churn probability**.
The evaluation is area under ROC curve.

---

## 💻 Technologies Used
- Python (Pandas, NumPy, Scikit-learn)
- XGBoost, LightGBM, Random Forest
- Matplotlib, Seaborn (EDA & visualization)
- GridSearchCV (hyperparameter tuning)

---

## 🗂️ Project Structure

```bash
.
├── data/               # Raw and processed datasets
├── notebooks/          # Jupyter notebooks with EDA and modeling
├── outputs/            # Submission files and result snapshots
├── requirements.txt    # Python dependencies
└── README.md
```

---

## 🔎 Key Steps

1. **EDA**
   - Identified class imbalance, correlated features, and feature distributions  
   - Visualized churn patterns by geography, age, and tenure

2. **Preprocessing**
   - Encoded categorical features (e.g., Gender, Geography)  
   - Standardized numerical features where necessary  
   - Removed outliers based

3. **Modeling**  
   - Trained multiple classifiers with cross-validation  
   - Tuned hyperparameters using GridSearchCV  
   - Evaluated using ROC AUC

4. **Final Model**  
   - Chosen model: `XGBoost` with tuned parameters  
   - ROC AUC: **0.9337 (CV)**, **0.9277 (Test)**

---

## 📊 How to Reproduce

1. Clone the repo:
```bash
git clone https://github.com/marybe1/kaggle_bank_customer_churn
cd churn-prediction-kaggle
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook and explore:
```bash
jupyter notebook notebooks/bank_customer_churn.ipynb
```
