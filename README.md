# Heart-disease-classification
This repository contains an end-to-end solution for predicting heart disease using machine learning. The project involves data preprocessing, model training, evaluation, and prediction using a dataset from the UCI Machine Learning Repository.

## Overview
Heart disease is a major health issue globally, and early detection can significantly improve treatment outcomes. This project aims to create a machine learning model to predict the presence of heart disease in patients based on various medical attributes.

## Features
* Data Preprocessing: Cleaning and preparing the data for modeling.
* Exploratory Data Analysis: Visualizing and understanding the dataset.
* Feature Engineering: Selecting and engineering relevant features.
* Model Training: Training various machine learning models to find the best one.
* Model Evaluation: Evaluating the model using different metrics.
* Prediction: Making predictions on new data.

## Dataset
The dataset used in this project is the Heart Disease UCI dataset, which includes the following features:

* id (Unique id for each patient)
* age (Age of the patient in years)
* origin (place of study)
* sex (Male/Female)
* cp chest pain type ([typical angina, atypical angina, non-anginal, asymptomatic])
* trestbps resting blood pressure (resting blood pressure (in mm Hg on admission to the hospital))
* chol (serum cholesterol in mg/dl)
* fbs (if fasting blood sugar > 120 mg/dl)
* restecg (resting electrocardiographic results)
* thalach: maximum heart rate achieved
* exang: exercise-induced angina (True/ False)
* oldpeak: ST depression induced by exercise relative to rest
* slope: the slope of the peak exercise ST segment
* ca: number of major vessels (0-3) colored by fluoroscopy
* thal: [normal; fixed defect; reversible defect]
* num: the predicted attribute


## Model Training
The notebook covers:

* Loading and exploring the dataset.
* Preprocessing the data (handling missing values, encoding categorical variables, scaling features).
* Splitting the data into training and test sets.
* Training several machine learning models (e.g., Logistic Regression, KNN classifier, Random Forest classifier).
* Hyperparameter tuning using RandomizedSearchCV and GridSearchCV.
* Evaluating the models using metrics like accuracy, precision, recall, F1-score, and ROC-AUC score.
* Visualizing the results with plots such as confusion matrix and ROC curve.

## Results
Results of the model evaluation, including the best model performance and visualizations, are presented within the notebook. Key findings and plots are provided to illustrate the model's effectiveness in predicting heart disease.
