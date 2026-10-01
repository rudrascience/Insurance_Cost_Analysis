# Insurance_Cost_Analysis
This is a data analysis project for Medical Insurance dataset included in IBM Data Science Professional Certificate.

---
## Clone the project
https://github.com/rudrascience/Insurance_Cost_Analysis.git

---

## Used tools
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/IBM-052FAD?style=for-the-badge&logo=ibm&logoColor=white"/>
</p>

---
## 📋 Project Overview

This repository contains a **Data Analytics and Machine Learning Capstone Project** completed as part of the IBM Data Science Professional Certificate programm. It performs a comprehensive end-to-end analytical workflow on the **Medical Insurance cost dataset** — covering Exploratory Data Analysis (EDA), data wrangling, statistical visualization, predictive model development and model refinement using regression techniques.

The project demonstrates the full data science pipeline: from raw data ingestion and cleaning, through visual correlation analysis, to model training, evaluation, and regularization — resulting in quantified predictive performance metrics for Insurance Cost estimation.

---

## 🛠️ Technology Stack

| Technology | Role |
|:---|:---|
| **Python 3.x** | Core language |
| **Jupyter Notebook** | Interactive analysis environment |
| **Pandas** | Data loading, cleaning, transformation, groupby |
| **NumPy** | Numerical operations and array handling |
| **Matplotlib** | Base plotting library |
| **Seaborn** | Statistical visualisation (`regplot`, `boxplot`) |
| **Scikit-learn** | `LinearRegression`, `Ridge`, `Pipeline`, `PolynomialFeatures`, `StandardScaler`, `train_test_split` |

---

| Attribute |Description| Content type |
|---|----|---|
|age| Age in years| integer |
|gender| Male or Female|integer (1 or 2)|
| bmi | Body mass index | float |
|no_of_children| Number of children | integer|
|smoker| Whether smoker or not | integer (0 or 1)|
|region| Which US region - NW, NE, SW, SE | integer (1,2,3 or 4 respectively)|
|charges| Annual Insurance charges in USD | float|

---
## Objectives
In this project, I have:
 - Loaded the data as a `pandas` dataframe
 - Cleaned the data, taking care of the blank entries
 - Ran exploratory data analysis (EDA) and identify the attributes that most affect the `charges`
 - Developed single variable and multi variable Linear Regression models for predicting the `charges`
 - Used Ridge regression to refine the performance of Linear regression models.

---
