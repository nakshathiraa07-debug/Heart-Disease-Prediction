# Heart Disease Prediction Using Machine Learning

## Project Overview

This project uses machine learning techniques to predict the presence of heart disease based on patient health information.

The project uses the Heart Disease UCI dataset and compares two machine learning algorithms:

* Logistic Regression
* Decision Tree Classifier

## Objectives

* Load and explore the heart disease dataset
* Clean and preprocess the data
* Handle missing values and categorical features
* Split the dataset into training and testing sets
* Apply feature scaling
* Train Logistic Regression and Decision Tree models
* Evaluate model performance
* Compare the two models

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Dataset

The project uses the Heart Disease UCI dataset.

The target variable is converted into:

* `0` = No Heart Disease
* `1` = Heart Disease

## Machine Learning Models

### 1. Logistic Regression

Logistic Regression is used as a classification model to predict whether heart disease is present.

### 2. Decision Tree

A Decision Tree classifier is used to identify patterns in the patient data and make predictions.

## Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* Confusion Matrix
* ROC Curve
* AUC

## Results

The Decision Tree model achieved the highest accuracy on the test dataset:

**Accuracy: 88.04%**

Therefore, the Decision Tree was selected as the better-performing model based on accuracy.

## Project Files

* `Heart_Disease_Prediction.ipynb` — Jupyter Notebook containing the complete project
* `heart_disease_uci.csv` — Dataset used for the project
* `README.md` — Project documentation

## Conclusion

This project demonstrates how machine learning can be applied to health-related data for classification. Logistic Regression and Decision Tree models were trained and evaluated using several performance metrics.

The Decision Tree achieved the highest accuracy of 88.04% on the test data.

These predictions are intended for educational and machine-learning purposes and should not be considered a medical diagnosis.
