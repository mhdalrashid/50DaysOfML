# 📚 Day 1: Student Score Prediction using Simple Linear Regression

Welcome to Day 1 of my **#50DaysOfML Challenge**!  
To kick things off, I built a **simple linear regression** model to predict student scores based on their study hours.

---

## 📊 Problem Statement

> Given the number of hours a student studies, predict the percentage score they are likely to achieve in an exam.

---

## 📥 Dataset Overview

- **Source**: [Supervised ML - Student Scores Dataset](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) (used version from open GitHub link)
- **Shape**: 25 rows × 2 columns
- **Features**:  
  - `Hours`: Number of hours studied  
  - `Scores`: Exam score (target)

---

## 🛠️ Tools & Libraries Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (Linear Regression, metrics)

---

## 📈 Workflow Summary

- Loaded dataset from GitHub raw URL
- Performed quick EDA (scatterplot + correlation check)
- Trained a **Simple Linear Regression** model
- Evaluated model using:
  - **Mean Absolute Error (MAE)**
  - **Root Mean Squared Error (RMSE)**
  - **R² Score**
- Visualized regression line over data points
- Made prediction for a custom input (`Hours = 9.25`)

---

## ✅ Key Results

- **MAE**: ~4.18  
- **R² Score**: ~0.95  
- **Predicted score for 9.25 hours**: ~93.89%

---

## 💬 What I Learned

- Understood the end-to-end process of building a basic regression model  
- Explored how well a simple model performs on a small, clean dataset  
- Practiced using `scikit-learn` for model fitting and evaluation  
- Learned how to visualize regression outputs for insight

---

## 🔗 Resources

- 📒 [Colab Notebook](https://colab.research.google.com/drive/1I3rCN63q8paAfyZjQiHlk_4KDZdZqbge)
- 📘 [Dataset GitHub Source](https://raw.githubusercontent.com/AdiPersonalWorks/Random/master/student_scores%20-%20student_scores.csv)

---

