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

## Observations
Relation between Age and Area income

<img width="656" height="542" alt="image" src="https://github.com/user-attachments/assets/8509b737-1494-46dc-962c-1c465ee435c7" />

Daily time spent on site vs Age

<img width="617" height="537" alt="image" src="https://github.com/user-attachments/assets/f29720c0-31b6-4339-8e79-6bf1c02525bb" />



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
