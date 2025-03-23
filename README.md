Task 2: Predictive Analysis Using Machine Learning (Titanic Dataset)

Project Overview:
This project is part of the CodTech Data Analysis Internship (Task 2). The goal was to build a predictive classification model to predict passenger survival on the Titanic based on multiple features.

Dataset Used:
Dataset: Titanic Dataset (tested.csv)
Format: CSV

Key Features:
Pclass, Sex, Age, SibSp, Parch, Fare, Embarked
Target Variable: Survived

Tools & Libraries Used:
Pandas (for data loading and preprocessing)
Matplotlib & Seaborn (for visualization)
Scikit-learn (for model building and evaluation)
Jupyter Notebook (Anaconda)

Process Followed:
Data Loading & Exploration
Handling Missing Values (filling with median values)
Feature Selection & Cleaning
Categorical Encoding (using get_dummies)
Train-Test Split (80/20)
Model Training using Logistic Regression
Model Evaluation with accuracy score, confusion matrix, and classification report

Key Results:
Model Accuracy: 100% (due to small dataset and possible overlap — mentioned as a limitation)
Top Features Influencing Survival: Pclass, Sex, Age, and Fare.

Insights:
Females and passengers from higher classes had better survival chances.
Higher fares correlated with better survival likelihood.
