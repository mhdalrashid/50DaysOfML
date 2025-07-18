# Day 4:🏠 Ridge & Lasso Regression - House Price Prediction

On Day 4 of the **#50DaysOfML Challenge**, I explored **regularization techniques** in regression using the famous Boston Housing dataset. I implemented and compared **Linear Regression**, **Ridge Regression**, and **Lasso Regression** to understand how each model deals with overfitting and feature importance.

---

## 📊 Problem Statement

Predict house prices based on various features such as crime rate, number of rooms, location, and more. The primary aim was to observe the **impact of L1 and L2 regularization**.

---

## 📥 Dataset Overview

- **Name**: Boston Housing Dataset  
- **Shape**: 506 rows × 13 features + 1 target  
- **Target Variable**: `MEDV` (Median value of owner-occupied homes in $1000s)  
- **Feature Columns**:  
  - `CRIM`: per capita crime rate by town  
  - `ZN`: proportion of residential land zoned for large lots  
  - `INDUS`: proportion of non-retail business acres per town  
  - `CHAS`: Charles River dummy variable (= 1 if tract bounds river)  
  - `NOX`: nitric oxides concentration (parts per 10 million)  
  - `RM`: average number of rooms per dwelling  
  - `AGE`: proportion of owner-occupied units built before 1940  
  - `DIS`: weighted distances to five Boston employment centers  
  - `RAD`: index of accessibility to radial highways  
  - `TAX`: property-tax rate per $10,000  
  - `PTRATIO`: pupil-teacher ratio by town  
  - `B`: 1000(Bk - 0.63)^2 where Bk is the proportion of Black residents  
  - `LSTAT`: % lower status of the population  

---

## 🛠️ Tools & Libraries Used

- Python, NumPy, Pandas, Seaborn, Matplotlib  
- Scikit-learn: `LinearRegression`, `Ridge`, `Lasso`, `train_test_split`, `StandardScaler`  
- Jupyter/Google Colab  

---

## 📈 Workflow Summary

- Loaded dataset and converted to DataFrame  
- Performed EDA (correlation heatmap, pairplot)  
- Split into training and testing sets  
- Scaled features using `StandardScaler`  
- Trained three models:  
  - Linear Regression  
  - Ridge Regression (L2)  
  - Lasso Regression (L1)  
- Evaluated with **MSE** and **R² Score**  

---

## ✅ Models Used

| Model              | Description                                      |
|-------------------|--------------------------------------------------|
| Linear Regression | Baseline regression without regularization      |
| Ridge Regression  | Penalizes large coefficients (L2 penalty)        |
| Lasso Regression  | Performs feature selection (L1 penalty)          |

---

## 📊 Model Evaluation

| Model              | MSE    | R² Score |
|-------------------|--------|----------|
| Linear Regression | 22.51  | 0.79     |
| Ridge Regression  | 22.65  | 0.78     |
| Lasso Regression  | 23.92  | 0.77     |

---

## 💬 What I Learned

- Ridge and Lasso both help reduce overfitting but behave differently.  
- Lasso can push coefficients to zero, acting as a built-in feature selector.  
- Linear Regression performed slightly better on this dataset but might overfit on others.  
- Regularization helps improve model generalization on unseen data.  

---

## 🔗 Links

- 📥 **Dataset Source**: [UCI Boston Housing](https://archive.ics.uci.edu/ml/datasets/housing)  
- 📒 **Colab Notebook**: [View Notebook](https://colab.research.google.com/drive/1k6gzFroHCOAJPEMgbcOvWxZmn5_Ifu_C)

---
