# 🚗 Car Price Prediction using Machine Learning

## 📌 Project Overview
This project focuses on building an end-to-end Machine Learning model to predict car prices based on various features such as brand, engine size, fuel type, transmission, mileage, condition, and model.  
The objective is to apply data science and regression techniques to derive accurate price predictions and compare model performance.

---

## 📊 Dataset Description
The dataset contains information about cars with the following features:

- Brand  
- Engine Size  
- Fuel Type  
- Transmission  
- Mileage  
- Condition  
- Model  
- Price (Target Variable)

The dataset is used for exploratory data analysis, feature engineering, and model training.

---

## ⚙️ Technologies & Tools Used
- Programming Language: Python  
- Libraries:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Statsmodels

---

## 🔍 Project Workflow
1. Data Loading & Exploration  
   - Loaded dataset using Pandas  
   - Checked data types, missing values, and duplicates  

2. Exploratory Data Analysis (EDA)  
   - Outlier detection using boxplots  
   - Feature distribution analysis  

3. Data Preprocessing  
   - Categorical feature encoding using Label Encoding  
   - Multicollinearity analysis using Variance Inflation Factor (VIF)  

4. Feature Selection  
   - Dropped highly correlated features  
   - Selected relevant predictors  

5. Model Building  
   - Train-test split (80% training, 20% testing)  
   - Implemented regression models  

6. Model Evaluation  
   - Evaluated models using R² Score  

---

## 🤖 Machine Learning Models Used
- Linear Regression  
- Random Forest Regressor  

Random Forest achieved better performance compared to Linear Regression.

---

## 📈 Results
- Successfully predicted car prices using regression techniques  
- Random Forest model produced higher accuracy  
- Demonstrates effectiveness of ensemble learning  

---

## 🚀 How to Run the Project

### Clone the Repository
git clone https://github.com/sai-chaitanya-reddy/car-price-prediction.git
