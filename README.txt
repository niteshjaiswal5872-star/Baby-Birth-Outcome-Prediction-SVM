# Baby Birth Outcome Prediction using SVM

## Project Overview
This project uses Machine Learning to predict a baby's birth outcome based on maternal and pregnancy-related information. The model classifies the outcome into two categories: Normal and At_Risk.

## Machine Learning Model
A Support Vector Machine (SVM) classifier is used for prediction. StandardScaler is applied to scale the numerical features, and class balancing is used to improve the detection of the At_Risk class.

## Data Preprocessing
The dataset is processed by:
- Handling missing numerical values using the mean.
- Handling missing categorical values using the mode.
- Converting categorical features using one-hot encoding.
- Splitting the dataset into training and testing sets.
- Scaling the features using StandardScaler.

## Features
The dataset includes:
- Mother Age
- Gestational Weeks
- Maternal BMI
- Systolic Blood Pressure
- Hemoglobin
- Blood Sugar
- Prenatal Visits
- Smoking
- Alcohol Use
- Previous Complications
- Exercise Hours Per Week
- Stress Level

## Model Performance
The SVM model achieved approximately 68% accuracy. Precision, Recall, and F1-Score were also used to evaluate the performance of both Normal and At_Risk classes.

The class-balanced SVM improved the model's ability to identify At_Risk cases compared with the initial model.

## Streamlit Deployment
The trained SVM model is integrated with Streamlit to create an interactive web application. Users can enter maternal and pregnancy-related information through the interface, and the application displays the predicted birth outcome.

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Support Vector Machine (SVM)
- StandardScaler
- Streamlit

## How to Run
Install the required libraries:

pip install -r requirements.txt

Run the Streamlit application:

python3 -m streamlit run svm.py

## Objective
The objective of this project is to demonstrate the application of machine learning classification and Streamlit deployment to build an interactive prediction system.

## Disclaimer
This project is developed for educational purposes only. The dataset and model are not medically validated, and the predictions should not be used for medical diagnosis, treatment, or clinical decision-making.

## Author
Yash Jaiswal