### 🧠 Student Grade Prediction using Support Vector Regression

On Day 6 of the **#50DaysOfML Challenge**, I tackled the problem of **predicting students' final grades based on various academic and socio-demographic factors**.  
I explored and evaluated the performance of **Support Vector Regression (SVR)** on the **Student Performance dataset**, focusing on understanding model behavior on real-world noisy tabular data.

---

#### 📊 Problem Statement

The goal of this project was to build a regression model that can accurately predict the final grade (G3) of students in Portuguese secondary schools. The model uses features such as past grades, study time, family background, and lifestyle factors to make predictions. Accurate grade prediction can help identify students who may need additional support early on.

---

#### 📥 Dataset Overview

- **Name**: Student Performance Dataset (UCI Repository)  
- **Shape**: 395 rows × 33 features + 1 target  
- **Target Variable**: G3 (final grade)  
- **Key Features**:  
  - G1: First period grade  
  - G2: Second period grade  
  - studytime: Weekly study time  
  - failures: Number of past class failures  
  - absences: Number of school absences

---

#### 🛠️ Tools & Libraries Used

- Python, NumPy, Pandas, Seaborn, Matplotlib  
- Scikit-learn: `SVR`, `StandardScaler`, `train_test_split`, `mean_squared_error`, `r2_score`  
- Google Colab  

---

#### 📈 Workflow Summary

- Loaded the dataset from UCI Machine Learning Repository  
- Cleaned and encoded categorical features  
- Performed Exploratory Data Analysis (EDA) using visualizations  
- Split the data into train and test sets  
- Scaled the features using StandardScaler  
- Trained a Support Vector Regression model  
- Evaluated performance using R² Score and RMSE  

---

#### ✅ Models Used

| Model              | Description                                 |
|-------------------|---------------------------------------------|
| Support Vector Regression (SVR) | Non-linear regression model using RBF kernel, sensitive to feature scaling |

---

#### 📊 Model Evaluation

| Model     | R² Score         | RMSE            | Notes                              |
|-----------|------------------|------------------|-------------------------------------|
| SVR       | 0.78 (approx)    | ~1.87 (approx)   | Performed well with G1 and G2 as strong predictors |

---

#### 💬 What I Learned

- SVR is highly sensitive to feature scaling, and `StandardScaler` greatly improved performance  
- The correlation heatmap clearly showed G1 and G2 are strong predictors of G3  
- Non-linear models like SVR can be effective even on small datasets if tuned well  
- Visualizing residuals helps understand model limitations  
- SVR is best used when relationships are non-linear and feature scaling is applied  

---

#### 🔗 Links

- 📒 **Colab Notebook**: [View Notebook](https://colab.research.google.com/drive/1tWCkFChWSDq4hysTXe4Bxc1GjIEO-YOj#scrollTo=34fcc792)  
- 📊 **Dataset Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/student+performance)  

---
