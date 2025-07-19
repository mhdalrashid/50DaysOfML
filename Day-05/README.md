### 🧠 Predicting Used Car Prices

On Day 5 of the **#50DaysOfML Challenge**, I tackled the problem of **predicting the resale price of used cars**.  
I explored and compared the performance of **Linear Regression, Ridge, and Lasso Regression** on the **Used Car Dataset from Cardekho**, focusing on **feature engineering, regularization, and generalization**.

---

#### 📊 Problem Statement

The goal is to predict the **selling price** of used cars based on features like car age, mileage, fuel type, and transmission. This regression problem involves both numeric and categorical data, requiring preprocessing and regularization.

---

#### 📥 Dataset Overview

- **Name**: Used Car Dataset (Cardekho)  
- **Shape**: ~8,000 rows × 8 features + 1 target  
- **Target Variable**: `Selling_Price`  
- **Key Features**:  
  - `Present_Price`: Ex-showroom price  
  - `Kms_Driven`: Total kilometers driven  
  - `Fuel_Type`, `Seller_Type`, `Transmission`: Categorical features  

---

#### 🛠️ Tools & Libraries Used

- Python, NumPy, Pandas, Seaborn, Matplotlib  
- Scikit-learn: LinearRegression, Ridge, Lasso, train_test_split, metrics  

---

#### 📈 Workflow Summary

- Loaded and cleaned dataset  
- Feature engineered `Car_Age` and encoded categoricals  
- Split into train/test sets  
- Trained: Linear, Ridge, Lasso  
- Evaluated using MAE, RMSE, R²  

---

#### ✅ Models Used

| Model              | Description                     |
|-------------------|---------------------------------|
| Linear Regression | Baseline with all features      |
| Ridge Regression  | L2-regularized to reduce overfit|
| Lasso Regression  | L1-regularized for sparse model |

---

#### 📊 Model Evaluation

| Model              | MAE     | RMSE    | R²     | Notes                      |
|-------------------|---------|---------|--------|----------------------------|
| Linear Regression | 1.22    | 2.13    | 0.85   | Good base performance      |
| Ridge Regression  | 1.18    | 2.08    | 0.86   | Slight improvement w/ L2   |
| Lasso Regression  | 1.25    | 2.17    | 0.83   | Less stable due to L1 shrinkage |

---

#### 💬 What I Learned

- How to preprocess mixed data types  
- The role of Ridge vs Lasso in regularization  
- Feature engineering like `Car_Age` improves performance  
- Real-world datasets require hands-on data cleaning  

---

#### 🔗 Links

- 📒 **Colab Notebook**: [https://colab.research.google.com/drive/10LnXhN3LKGf4WBCxOdGoiGJIMO7y3K0U#scrollTo=SwcQcsZ3tEJe)  
- 📊 **Dataset Source**: [Kaggle Dataset](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)
