# Heart Disease Prediction - Model Training

This repository contains the Jupyter notebook used to train the machine learning model for predicting heart disease risk, based on patient health parameters.

## What's inside
- Exploratory Data Analysis (EDA)
- Data preprocessing (encoding categorical features, scaling numerical features)
- Comparison of 5 ML models: Logistic Regression, KNN, Naive Bayes, Decision Tree, SVM
- Final model (KNN) exported using joblib for deployment

## Dataset
Heart disease dataset with features like Age, Sex, Chest Pain Type, Resting Blood Pressure, Cholesterol, Fasting Blood Sugar, Resting ECG, Max Heart Rate, Exercise-Induced Angina, Oldpeak, and ST Slope.

## Model Performance
| Model | Accuracy | F1 Score |
|---|---|---|
| Logistic Regression | 0.8641 | 0.8804 |
| KNN | 0.8533 | 0.8708 |
| Naive Bayes | 0.8533 | 0.8683 |
| SVM | 0.8478 | 0.8679 |
| Decision Tree | 0.7826 | 0.8095 |

## Deployment
The trained model is deployed as an interactive web app using Streamlit:
- Live App: https://heart-stroke-app-gkzffhrmisg9tkdb375ebq.streamlit.app
- Deployment code repo: https://github.com/prateekpatel95097/heart-stroke-app

## Author
Prateek Patel
