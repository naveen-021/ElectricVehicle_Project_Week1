# 🚗⚡ Electric Vehicle Data Analysis & Range Prediction

This project analyzes Electric Vehicle (EV) specifications and builds a machine learning model to predict EV driving range based on battery capacity and efficiency.

---

## 🎯 Week-1 Goals (Completed)

- ✅ Load & clean EV dataset  
- ✅ Parse battery & range fields  
- ✅ Handle missing values  
- ✅ Create numeric features  
- ✅ Simple Linear Regression model (battery → range)
- ✅ Generate predictions & basic plots  
- ✅ Insights + documentation  

### 📊 Key Result
EV range increases roughly **6 km per additional 1 kWh battery**.


---

## 🗓️ 3-Week Project Roadmap

### ✅ Week-1 — Data Cleaning + Basic ML
- Import, clean, parse data  
- Baseline EV range model  
- Visualizations  

## 📌 Week 2 Objective  
In Week-2, the focus was on **feature engineering**, **data preprocessing**, and **model training** using multiple regression algorithms to predict electric vehicle performance metrics. We encoded categorical variables, scaled numerical features, and trained three ML models — Linear Regression, Ridge Regression, and Random Forest Regressor.

## ✅ Tasks Completed  
- Loaded cleaned EV dataset  
- Handled categorical encoding (`OneHotEncoder`)  
- Feature scaling for numerical variables (`StandardScaler`)  
- Train–test split  
- Model training:  
  - Linear Regression  
  - Ridge Regression  
  - Random Forest Regressor  
- Model evaluation using:  
  - MAE (Mean Absolute Error)  
  - RMSE (Root Mean Squared Error)  
  - R² Score  

## 📊 Model Performance Results  
| Model | MAE ↓ | RMSE ↓ | R² ↑ |
|------|--------|--------|------|
| Linear Regression | 11.38 | 14.75 | 0.827 |
| Ridge Regression | 11.38 | 14.75 | 0.827 |
| **Random Forest** ✅ | **9.65** | **13.64** | **0.852** |

✅ **Random Forest performed the best**, showing that non-linear models capture EV performance patterns more effectively.

## 🚀 Next Steps (Week-3 Preview)
- Hyperparameter tuning (GridSearchCV / RandomizedSearchCV)
- Model saving (`joblib`)
- GUI / Web App (Streamlit or Flask)
- Deployment Documentation

---
