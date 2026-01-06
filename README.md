🚢 Titanic Survival Prediction – Data Analysis & Machine Learning
📌 Project Overview

This project focuses on exploratory data analysis (EDA), feature engineering, and machine learning modeling to predict the survival of passengers aboard the Titanic.
The goal is not just prediction accuracy, but understanding the factors that influenced survival using data-driven insights.

🎯 Objectives

Analyze passenger data to uncover survival patterns

Perform structured exploratory data analysis (EDA)

Engineer meaningful features from raw data

Build and evaluate a machine learning model to predict survival

🧰 Tools & Technologies Used

Python

NumPy – numerical operations

Pandas – data manipulation

Matplotlib & Seaborn – data visualization

Scikit-learn – machine learning models & evaluation

📂 Project Structure
Titanic-Dataset-Analysis/
│
├── data/
│   ├── train.csv
│   └── processed_titanic.csv
│
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_feature_engineering.ipynb
│   └── 03_modeling.ipynb
│
├── README.md

📘 Notebook Breakdown
1️⃣ Exploratory Data Analysis (01_eda.ipynb)

Dataset overview and missing value analysis

Survival rate distribution

Univariate, bivariate, and multivariate analysis

Visual insights on survival vs gender, class, age, and fare

Key Insights:

Female passengers had a significantly higher survival rate

First-class passengers survived more than lower classes

Younger passengers had better survival chances

2️⃣ Feature Engineering (02_feature_engineering.ipynb)

Handling missing values using group-based statistics

Creating new features:

FamilySize

IsAlone

Passenger Title extracted from names

Encoding categorical variables

Dropping irrelevant features

Saving a clean, model-ready dataset

3️⃣ Modeling & Evaluation (03_modeling.ipynb)

Train–test data split

Logistic Regression model training

Model evaluation using:

Accuracy

Confusion Matrix

Precision, Recall, and F1-score

Interpretation of important features

📊 Model Performance

The model demonstrates reasonable performance given the dataset size and class imbalance.
Evaluation metrics beyond accuracy were used to ensure balanced assessment.

🔍 Key Learnings

Importance of EDA before modeling

Feature engineering can significantly improve model interpretability

Accuracy alone is not sufficient for imbalanced datasets

Structured ML pipelines improve reproducibility and clarity

🚀 Future Improvements

Compare multiple models (Random Forest, XGBoost)

Apply cross-validation

Hyperparameter tuning

Deploy as a web app using Streamlit

Add ROC-AUC and Precision–Recall analysis

🧠 Interview-Ready Summary

“This project demonstrates a complete data science workflow — from exploratory data analysis and feature engineering to machine learning modeling and evaluation — with a strong emphasis on interpretability and structured analysis.”