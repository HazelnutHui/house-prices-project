# 🏠 Ames Housing Price Prediction

A regression project using machine learning to predict housing prices based on the Ames Housing dataset.

Achieved a **Kaggle score of 0.12655**, ranked **#405 out of 4781 (top ~8.5%)** under the Kaggle username **Hui**.

---

## 📦 Project Overview

This notebook-based project walks through the full pipeline of:

- Exploratory Data Analysis (EDA)
- Data cleaning and imputation
- Feature engineering and log transformation
- Modeling using Ridge, Lasso, XGBoost, LightGBM
- Model blending with weighted ensembling
- Generating Kaggle submission file

---

## ⚙️ Tools & Techniques

- Python, Pandas, NumPy  
- Scikit-learn (Ridge, Lasso)  
- XGBoost & LightGBM  
- Cross-validation with RMSE scoring  
- One-hot encoding and log1p transformation  
- SHAP (optional for model explainability)

---

## 📊 Model Performance

| Model    | CV RMSE  |
|----------|----------|
| Ridge    | 0.12710  |
| Lasso    | 0.12655  |
| XGBoost  | 0.12836  |
| Ensemble | ~0.126XX |

---

## 📁 Directory Structure

```
.
├── 1_eda.ipynb
├── 2_data_cleaning&feature_engineering.ipynb
├── 3_ridge.ipynb
├── 4_lasso.ipynb
├── 5_xgboost.ipynb
├── 6_ensemble.ipynb
├── X_train_cleaned.csv
├── X_test_cleaned.csv
├── y_train.csv
└── ridge_submission.csv
```

---

## 📄 Submission Example

```csv
Id,SalePrice
1461,208500.0
1462,181500.0
...
```

---

## 🙋‍♀️ Author

**Hui Wang**  
Undergraduate, University of Utah  
Major: Mathematics (Statistics Emphasis)  
Target: Data Analyst / Data Scientist Internship  

---

## 🌐 More

This project is part of my data science portfolio for internship applications.  
Feel free to check out more projects on [my GitHub](https://github.com/) or contact me for collaboration.
