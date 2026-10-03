## Logistic Regression on Advertising Dataset
This project demonstrates how to apply Logistic Regression to predict whether a user will click on an advertisement based on demographic and behavioral features.
It covers the end-to-end machine learning workflow: data analysis, preprocessing, model building, and evaluation.

---

# Objective
The objective is to build a classification model that explains how factors such as Age, Daily Internet Usage, and Area Income influence the likelihood of clicking on an advertisement.
The model is evaluated using standard metrics to measure accuracy and reliability.

---

# Dataset
Source: Advertising dataset (commonly used in ML tutorials).

# Attributes:

Daily Time Spent on Site

Age

Area Income

Daily Internet Usage

Male (binary indicator)

Clicked on Ad (target variable: 0 = No, 1 = Yes)

---

# Tech Stack
Python 3

Pandas, NumPy → Data wrangling

Matplotlib, Seaborn → Visualization

Scikit-learn → Logistic Regression & evaluation

---

# Workflow
Data Loading & Exploration

Import dataset using Pandas

Perform exploratory data analysis (EDA) with visualizations

Preprocessing

Handle categorical/numeric features

Split dataset into training and testing sets

Model Building

Train Logistic Regression model using scikit-learn

Fit the model on training data

Evaluation

Accuracy score

Confusion matrix

Classification report (precision, recall, F1-score)

ROC curve & AUC

---

# Results
Logistic Regression achieved strong accuracy in predicting ad-clicks.

Age and Daily Internet Usage emerged as the most influential predictors.

The model provides interpretable insights useful for digital marketing strategies.

---

# Future Improvements
Compare Logistic Regression with other classifiers (Random Forest, SVM, XGBoost).

Perform hyperparameter tuning for improved performance.

Deploy the model using Streamlit or Flask for interactive predictions.

---

# Acknowledgements
Dataset widely used in ML tutorials (Kaggle, Udemy, Coursera).
