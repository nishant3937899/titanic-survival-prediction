# Titanic Data Science Project

A comprehensive **Data Science project** on the Titanic dataset, where exploratory data analysis (EDA) was performed, multiple machine learning models were trained, and the best-performing model was evaluated.

---

## Project Overview

The goal of this project is to **predict survival on the Titanic** based on passenger data. The project involves:

- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA) to understand trends and relationships  
- Training multiple machine learning models  
- Evaluating model performance to select the best model  

---

## Dataset

The dataset used in this project is the classic **Titanic dataset** from Kaggle. It includes the following features:

- `PassengerId`  
- `Pclass` – Passenger class  
- `Name`  
- `Sex`  
- `Age`  
- `SibSp` – Number of siblings/spouses aboard  
- `Parch` – Number of parents/children aboard  
- `Ticket`  
- `Fare`  
- `Cabin`  
- `Embarked` – Port of embarkation  

The target variable is:

- `Survived` – Survival (0 = No, 1 = Yes)  

---

## Exploratory Data Analysis (EDA)

- Checked for missing values and handled them appropriately  
- Visualized distribution of features and target variable  
- Analyzed correlations between features  
- Explored survival rates across different passenger classes, gender, and age groups  

---

## Machine Learning Models Tested

The following regression models were trained and evaluated:

- **Linear Regression**  
- **Lasso Regression**  
- **Ridge Regression**  
- **K-Neighbors Regressor**  
- **Decision Tree Regressor**  
- **Random Forest Regressor**  
- **AdaBoost Regressor**  

> Evaluation metrics were used to determine the best-performing model.

---

## Key Findings

- Feature importance analysis helped identify key predictors of survival  
- Among the models tested, the **Linear Regression** performed the best based on **R-squared score**  

---

## Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
