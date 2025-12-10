# Titanic Survival Prediction – Data Science Project

A **Data Science project** on the Titanic dataset where exploratory data analysis (EDA) was performed, multiple machine learning models were trained, and the best model was evaluated to predict passenger survival.  

---

## Project Overview

The goal of this project is to **predict survival on the Titanic** based on passenger features. This project includes:

- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Training multiple machine learning models  
- Evaluating and selecting the best-performing model  

---

## Dataset

The dataset used is the classic **Titanic dataset** from Kaggle. Features include:

- `PassengerId`, `Pclass`, `Name`, `Sex`, `Age`  
- `SibSp` – Number of siblings/spouses aboard  
- `Parch` – Number of parents/children aboard  
- `Ticket`, `Fare`, `Cabin`, `Embarked`  

**Target Variable:**  
- `Survived` (0 = No, 1 = Yes)  

---

## Exploratory Data Analysis (EDA) Insights

### Survival Based on Gender
- Female passengers are more likely to survive than males  
- Male survival rate: **18.89%**  
- Female survival rate: **74.20%**  

### Survival Based on Passenger Class
- 1st Class: **62.96%** survival – highest  
- 2nd Class: **47.28%** survival  
- 3rd Class: **24.23%** survival – lowest  

These insights highlight that **gender and passenger class were strong predictors of survival**.  

---

## Machine Learning Models Tested

The following models were trained and evaluated:

- Linear Regression  
- Lasso Regression  
- Ridge Regression  
- K-Neighbors Regressor  
- Decision Tree Regressor  
- Random Forest Regressor  
- AdaBoost Regressor  

> Evaluation metrics were used to determine the **Linear Regression Model**.  

---

## Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
