# 🌾 Crop Price Prediction using Machine Learning

## 📌 Project Overview
This project aims to predict agricultural crop prices using machine learning techniques. Crop price prediction plays a crucial role in helping farmers, traders, and policymakers make informed decisions by analyzing historical market data.

The notebook covers the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation.

---

## 🧠 Problem Statement
Agricultural commodity prices vary due to factors such as crop type, market location, seasonality, and demand–supply conditions. Traditional methods of price estimation are often inaccurate and inefficient.

This project focuses on building a machine learning model to **predict crop prices using historical agricultural market data**.

---

## 📂 Dataset Description
- The dataset is **extracted from AGMARKNET (AGMarket / e-NAM)**.
- Data was collected for **5 to 6 major crops commonly grown in India**.
- Covers a **5-year period**, capturing seasonal and yearly price variations.
- Data from different markets and time periods were **combined into a single dataset**.

### Key Features
- Crop name  
- Market / location  
- Date / Year  
- Minimum price  
- Maximum price  
- Modal price  

### Data Preparation Steps
- Merging market-wise and crop-wise datasets  
- Handling missing and inconsistent values  
- Encoding categorical variables  
- Feature scaling and transformation  

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was performed to:
- Understand price trends over years  
- Compare prices across markets  
- Analyze crop-wise price distribution  
- Identify missing values and outliers  

Visualization libraries used:
- Matplotlib  
- Seaborn  

---

## ⚙️ Technologies & Libraries Used
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- XGBoost  
- LightGBM  
- CatBoost  

---

## 🧪 Machine Learning Models Implemented
- Linear Regression  
- Random Forest Regressor  
- XGBoost Regressor  
- LightGBM Regressor  
- CatBoost Regressor  

---

## 📈 Model Evaluation Metrics
The models were evaluated using:
- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- R² Score  

---

## 🔄 Machine Learning Pipeline
- Missing value imputation  
- Categorical feature encoding  
- Feature scaling and transformation  
- End-to-end pipeline using `ColumnTransformer` and `Pipeline`  

---

## ✅ Results & Insights
- Ensemble and boosting models outperformed linear regression.
- XGBoost, LightGBM, and CatBoost showed strong predictive performance.
- Multi-year data improved model robustness and stability.

---
Author

## Adithya
- B.Tech – Data Science
 - Aspiring Data Scientist & Machine Learning Engineer
