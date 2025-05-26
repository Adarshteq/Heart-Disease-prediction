# 🫀 Heart Disease Prediction Using Machine Learning

This project focuses on predicting the likelihood of heart disease in patients using machine learning algorithms. 

By analyzing clinical features from a dataset, we build predictive models to assist in early diagnosis and risk assessment.

## 📁 Project Overview

Heart disease is one of the leading causes of death globally. 

Early detection can save lives and reduce healthcare costs. 

This project leverages various supervised machine learning techniques to predict heart disease based on patient data such as age, cholesterol levels, blood pressure, etc.

## 📊 Dataset

The dataset used is a cleaned version of the UCI Heart Disease dataset, containing the following features:

- Age

- Sex

- Chest Pain Type

- Resting Blood Pressure

- Serum Cholesterol

- Fasting Blood Sugar

- Resting ECG

- Maximum Heart Rate

- Exercise-Induced Angina

- Oldpeak (ST depression)

- Slope of the ST segment

- Number of Major Vessels

- Thalassemia

- Target (0 = No Disease, 1 = Disease)

## ⚙️ Features

- Data preprocessing and visualization

- Feature selection and scaling

- Model training using multiple algorithms:

  - Logistic Regression

  - Random Forest

  - K-Nearest Neighbors (KNN)

  - Support Vector Machine (SVM)

- Performance evaluation using accuracy, confusion matrix, and classification report

📓 Usage

Open the Jupyter Notebook:

bash

jupyter notebook Heart_Disease_Prediction.ipynb

Run the notebook cells sequentially to:

Load and explore the data

Train machine learning models

Evaluate and compare model performance

📈 Results

Our best-performing model achieved high accuracy on the test set, demonstrating the effectiveness of machine learning in predicting heart disease. 

Evaluation metrics such as confusion matrix and classification reports are provided in the notebook.

📌 Requirements

Python 3.7+

pandas

numpy

matplotlib

seaborn

scikit-learn

jupyter

📁 Files

Heart_Disease_Prediction.ipynb — Main Jupyter Notebook

data.csv — Cleaned dataset used for training and testing

README.md — Project documentation

requirements.txt — List of required Python libraries
