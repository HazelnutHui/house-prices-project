🏠 **Ames Housing Price Prediction (Kaggle Competition – Top 8.5%)**

A regression modeling project based on the Kaggle “House Prices: Advanced Regression Techniques” competition.

Achieved a Kaggle score of **0.12655**, ranking **#405 out of 4,781** submissions (Top ~8.5%) under the Kaggle username **Hui**.

---

📦 **Project Overview**

This notebook-based project walks through a complete regression modeling pipeline:

- Exploratory Data Analysis (EDA)
- Data cleaning and missing value imputation
- Feature engineering (log transformation, one-hot encoding)
- Modeling with Ridge, Lasso, XGBoost, and LightGBM
- Ensemble blending with weighted averaging
- Generating and submitting Kaggle predictions

---

⚙️ **Tools & Techniques**

- Python, pandas, NumPy  
- scikit-learn (Ridge, Lasso)  
- XGBoost, LightGBM  
- Cross-validation with RMSE scoring  
- SHAP for post-hoc model explainability  
- Jupyter Notebook

---

📊 **Model Performance (Cross-Validated RMSE)**

| Model     | CV RMSE   |
|-----------|-----------|
| Ridge     | 0.12710   |
| Lasso     | 0.12655   |
| XGBoost   | 0.12836   |
| Ensemble  | ~0.126xx  |

---

🧠 **Model Explainability (SHAP Analysis)**

To enhance model interpretability, I used SHAP (SHapley Additive exPlanations) to explain predictions for Ridge, Lasso, and XGBoost models.

- **SHAP Summary Plots** visualize how each feature impacts predictions across the dataset.
- **SHAP Waterfall Plots** show feature contributions for individual predictions.

#### 🔹 XGBoost SHAP Summary  
![XGBoost SHAP Summary](images/XGBoost_shap_summary.png)

#### 🔹 XGBoost SHAP Waterfall (Sample)  
![XGBoost SHAP Waterfall](XGBoost_shap_waterfall.png)

#### 🔹 Lasso SHAP Summary  
![Lasso SHAP Summary](Lasso_shap_summary.png)

#### 🔹 Lasso SHAP Waterfall (Sample)  
![Lasso SHAP Waterfall](Lasso_shap_waterfall.png)

#### 🔹 Ridge SHAP Summary  
![Ridge SHAP Summary](Ridge_shap_summary.png)

#### 🔹 Ridge SHAP Waterfall (Sample)  
![Ridge SHAP Waterfall](Ridge_shap_waterfall.png)

---

📁 **Directory Structure**
.
├── 1_eda.ipynb
├── 2_data_cleaning&feature_engineering.ipynb
├── 3_ridge.ipynb
├── 4_lasso.ipynb
├── 5_xgboost.ipynb
├── 6_ensemble.ipynb
├── 5_shap_explainability.ipynb
├── X_train_cleaned.csv
├── X_test_cleaned.csv
├── y_train.csv
└── ridge_submission.csv

---
📄 **Sample Submission Format**

Id,SalePrice
1461,208500.0
1462,181500.0
...

---

🙋‍♀️ **Author**

**Hui Wang**  
Undergraduate @ University of Utah  
Major: Mathematics (Statistics Emphasis)  
Target Role: Data Analyst / Data Scientist Internship

