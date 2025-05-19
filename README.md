# CODSOFT-Sales-Prediction
# 📊 Sales Prediction Using Regression

This project applies machine learning regression models to predict mobile phone sales based on product and customer features. It showcases a complete data science workflow, including data preprocessing, feature engineering, model training, evaluation, and visualisation.

---

## 📂 Project Overview

Using a real-world mobile phone sales dataset from 2024, we built and evaluated multiple regression models to predict unit sales based on the following features:

- Brand and Model  
- Storage Capacity  
- RAM  
- Operating System  
- Color  
- Processor  
- Screen Size  
- Region  

The primary goal is to understand which factors influence product sales and develop a model that can accurately predict future sales for better business decision-making.

---

## 🧠 Models Used

The following regression models were trained and evaluated using performance metrics like R² Score, MAE, and RMSE:

- Random Forest Regressor  
- XGBoost Regressor  
- Gradient Boosting Regressor  
- Bagging Regressor  
- Extra Trees Regressor ✅ *(Best Performer)*

**Extra Trees Regressor** achieved the highest R² score of **0.9600**, making it the best-performing model.

---

## 📊 Key Visualisations

- **Correlation Heatmap** – Shows feature relationships  
- **Feature Importance Plot** – Highlights features with the greatest impact on sales  
- **Actual vs Predicted Plot** – Visualises prediction accuracy  
- **Residual Plot** – Examines error distribution and model fit  

---

## 📌 Results Summary

- **Top Predictors of Sales**: `Brand`, `Model`, `RAM`, `Region`, and `Screen Size` had the most influence on predicted sales values.
- **Best Model**: Extra Trees Regressor delivered superior predictive performance and error minimisation.
- **Model Evaluation Metrics**:

| Model                  | R² Score | MAE   | RMSE  |
|------------------------|----------|-------|--------|
| Extra Trees Regressor  | 0.9600   | 0.7800 | 1.1100 |
| Bagging Regressor      | 0.9500   | 0.9300 | 1.2000 |
| Random Forest Regressor| 0.9500   | 0.9200 | 1.2100 |
| XGBoost Regressor      | 0.9500   | 0.9400 | 1.2100 |
| Gradient Boosting      | 0.9400   | 0.8900 | 1.3200 |

---

## 📁 Files Included

- `sales_prediction_model.ipynb`: Main Jupyter Notebook with data cleaning, modeling, and visualisations  
- `dataset/`: (if included) Cleaned dataset used for training and testing  
- `README.md`: This project summary  
- `requirements.txt`: List of Python libraries used
