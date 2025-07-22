"""
### 🧠 SVR on Bike Rental Demand

On Day 7 of the **#50DaysOfML Challenge**, I tackled the problem of **predicting daily bike rental counts using Support Vector Regression (SVR)**.  
I used the **Bike Sharing Dataset (daily)** and focused on exploring **SVR performance on real-world, seasonally influenced data**.

---

#### 📊 Problem Statement

The goal is to predict the number of rented bikes on a given day based on weather, temperature, humidity, and seasonal features. This is a real-world regression problem that helps in understanding demand patterns in shared mobility systems.

---

#### 📥 Dataset Overview

- **Name**: Bike Sharing Dataset (Daily)  
- **Shape**: 731 rows × 16 features + 1 target  
- **Target Variable**: `cnt` (total count of bikes rented)  
- **Key Features**:  
  - `temp`: Normalized temperature in Celsius  
  - `hum`: Normalized humidity  
  - `windspeed`: Normalized wind speed  
  - `season`, `weekday`, `workingday`, `weathersit`: Categorical predictors of time/weather

---

#### 🛠️ Tools & Libraries Used

- Python, NumPy, Pandas, Seaborn, Matplotlib  
- Scikit-learn: `SVR`, `StandardScaler`, `train_test_split`, `mean_absolute_error`, `r2_score`  
- Google Colab  

---

#### 📈 Workflow Summary

- Loaded dataset from a **working public GitHub source**  
- Cleaned and preprocessed data (dropped irrelevant columns, one-hot encoding, scaling)  
- Performed EDA with numeric correlation only (to avoid string conversion errors)  
- Trained **Support Vector Regression (SVR)** with RBF kernel  
- Evaluated using MAE, RMSE, R²  
- Visualized predictions with scatter plots  

---

#### ✅ Models Used

| Model              | Description                               |
|-------------------|-------------------------------------------|
| SVR (RBF Kernel)  | Handles nonlinear patterns in rental data |

---

#### 📊 Model Evaluation

| Model  | MAE    | RMSE   | R²     | Notes                            |
|--------|--------|--------|--------|----------------------------------|
| SVR    | ~92.2  | ~120.4 | ~0.78  | Performs well, slightly underfits |

---

#### 💬 What I Learned

- SVR performs best when features are well-scaled and the kernel is tuned.  
- Real-world datasets often require **type-specific handling** (like numeric-only for `.corr()`).  
- Public datasets on GitHub are easier for Colab workflows than UCI zip files.  
- Even without deep tuning, SVR gives a decent performance for nonlinear patterns.

---

#### 🔗 Links

- 📒 **Colab Notebook**: [View Notebook](https://colab.research.google.com/drive/1wk0X4fi58TuUcyHCWYCEOQuH_20jusFz#scrollTo=IBjxydlLES9n)  
- 📊 **Dataset Source**: [Bike Sharing Daily CSV](https://github.com/christophM/interpretable-ml-book/blob/master/data/bike-sharing-daily.csv)
"""
