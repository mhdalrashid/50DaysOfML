# 🏡 Day 2: Predict House Prices using Multivariate Linear Regression

Welcome to Day 2 of my **#50DaysOfML Challenge**!  
In this project, I built a **multivariate linear regression** model to predict house prices using the **California Housing** dataset.

---

## 📊 Problem Statement

> Predict the median house value in a California district using features like income, age of the house, average rooms, location, etc.

---

## 📁 Dataset Overview

- **Source**: `sklearn.datasets.fetch_california_housing`
- **Shape**: 20,640 rows × 9 columns
- **Features**:
  - `MedInc`, `HouseAge`, `AveRooms`, `AveBedrms`, `Population`, `AveOccup`, `Latitude`, `Longitude`
- **Target**: `MedHouseVal` (Median house value)

---

## 🛠️ Tools & Libraries Used

- Python, Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (Linear Regression, preprocessing, metrics)
- Joblib (model persistence)

---

## 📈 Workflow Summary

- Loaded and explored the California housing dataset
- Performed EDA: visualized distributions, correlations, patterns
- Preprocessed the data: scaled features using StandardScaler
- Split data into training and test sets
- Trained a Linear Regression model
- Evaluated with MAE, RMSE, R²
- Visualized predicted vs actual values
- Saved the model for future use
- Predicted on unseen/test data

---

## ✅ Key Results

- **MAE**: ~0.53  
- **RMSE**: ~0.75  
- **R² Score**: ~0.61  

---

## 💬 What I Learned

- How to structure a multivariate regression pipeline
- Importance of feature scaling in numerical datasets
- How to visualize and interpret linear model results
- Improved my EDA skills using correlation heatmaps and pairplots

---

## 🔗 Resources

- 📘 [Scikit-learn California Dataset Docs](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)
- 📒 [Colab Notebook](https://colab.research.google.com/drive/https://colab.research.google.com/drive/1vISJ4OjZVYGiyfS-8a9fXDArUTnA2n65#scrollTo=814da21f)

---
