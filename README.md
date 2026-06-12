# 🏠 Airbnb Price Prediction — Predictive Modeling Pipeline

A complete end-to-end Data Science pipeline for predicting nightly rental prices of Airbnb listings using statistical techniques and supervised Machine Learning algorithms.

---

## 📋 Project Overview

This project builds and evaluates regression models capable of estimating the price of Airbnb listings based on property features, location, guest reviews, and other relevant variables. The goal is to identify the most effective modeling approach by comparing a linear baseline against more powerful ensemble methods.

---

## 🔧 Pipeline Steps

### 1. Data Preprocessing
- Missing value imputation
- Categorical variable encoding (One-Hot Encoding)
- Numerical feature normalization and standardization
- Outlier removal based on statistical analysis

### 2. Modeling
Three regression approaches were applied:

| Model | Description |
|---|---|
| **Multiple Linear Regression** | Baseline model; assumes a linear relationship between features and price |
| **Random Forest Regressor** | Ensemble of decision trees; robust to outliers and non-linear patterns |
| **Gradient Boosting Regressor** | Sequential boosting technique; minimizes residual error at each iteration |

### 3. Evaluation
Models were evaluated on a held-out test set using the following metrics:

- **RMSE** (Root Mean Squared Error) — penalizes large prediction errors
- **MAE** (Mean Absolute Error) — interpretable average absolute error
- **R²** (Coefficient of Determination) — measures how much variance the model explains

---

## 📊 Results

Ensemble-based models (Random Forest and Gradient Boosting) significantly outperformed the linear baseline, confirming the presence of complex, non-linear patterns in the data.

---

## 🚀 Future Work

- Hyperparameter tuning with Grid Search and Random Search
- Testing advanced boosting frameworks: **XGBoost** and **LightGBM**
- K-fold cross-validation for more robust evaluation
- Model deployment to a production environment for real-time predictions

---

## 🛠️ Tech Stack

- **Language:** Python
- **Libraries:** scikit-learn, pandas, numpy, matplotlib / seaborn
- **Version Control:** Git & GitHub

---

## 📁 Project Structure

```
airbnb-price-prediction/
│
├── data/                  # Raw and processed datasets
├── notebooks/             # Exploratory analysis and modeling notebooks
├── models/                # Saved model artifacts
├── src/                   # Source scripts (preprocessing, training, evaluation)
├── requirements.txt       # Project dependencies
└── README.md
```

---

## 👤 Author

Pedro — Software Engineering Student  
Feel free to connect or reach out via [GitHub](https://github.com/).
