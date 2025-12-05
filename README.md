# 🚗 Car Price Prediction Using Machine Learning

## 📌 Project Overview
A Chinese automobile company plans to enter the US market and wants to understand:
- Which factors significantly influence car prices.
- How strong the relationship is between car features and price.
  
This project builds multiple regression models to predict car prices and analyzes the most important features affecting pricing.

---

## 📁 Dataset
**CarPrice_Assignment.csv**

This dataset contains specifications and pricing details of cars available in the American market.

---

## 📝 Objectives
### ✔ Load and preprocess the dataset  
### ✔ Implement 5 machine learning regression models:
- Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- Gradient Boosting Regressor  
- Support Vector Regressor  

### ✔ Evaluate models using:
- R² Score  
- Mean Squared Error (MSE)  
- Mean Absolute Error (MAE)

### ✔ Analyze feature importance  
### ✔ Perform hyperparameter tuning  
### ✔ Identify the best performing model  

---

## 🛠 Technologies Used
- Python  
- Jupyter Notebook  
- Pandas, NumPy  
- Scikit-Learn  
- Matplotlib, Seaborn  

---

## 📊 Project Workflow

### 1️⃣ **Data Loading & Preprocessing**
- Mounted Google Drive  
- Loaded dataset  
- Removed unnecessary columns  
- One-hot encoded categorical features  
- Train-test splitting  
- Scaled numerical features for SVR  

---

### 2️⃣ **Modeling**
Implemented regression algorithms:
- Linear Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  
- Support Vector Regressor (SVR)

---

### 3️⃣ **Model Evaluation**
Models evaluated on:
- **R² Score**
- **MSE**
- **MAE**

The best model is selected based on the highest R² and lowest error scores.

---

### 4️⃣ **Feature Importance**
Using Random Forest and Gradient Boosting:
- Identified top predictors (engine-size, horsepower, curb weight, car width, etc.)

---

### 5️⃣ **Hyperparameter Tuning**
GridSearchCV used to improve performance of the best model.

---

## 📈 Results Summary

- **Random Forest / Gradient Boosting** performed best.
- Hyperparameter tuning improved model accuracy further.
