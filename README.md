# Stroke Prediction Model

## Overview

This project aims to develop a predictive model to identify individuals at risk of stroke (AVC) using the Stroke Prediction Dataset. By analyzing patients' health conditions and personal attributes, the model seeks to predict the likelihood of a stroke, allowing for early intervention and preventive measures. The goal is to create a reliable took that can assist healthcare professionals in identifying high-risk patients.

## Dataset

The dataset used in this project is the **Stroke Prediction Dataset**, which contains data on various health conditions of patients. It includes features such as age, hypertension, heart disease, smoking status, and more, which are relevant to predicting the risk of stroke.

- **Dataset Link**: [Stroke Prediction Dataset](https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset)

## Project Structure

- **Data Preprocessing**: Handling missing values, feature engineering, and normalization of data.
- **Model Training**: The dataset is split into training and testing sets. Several Machine Learning models are trained to find the best-performing one.
- **Evaluation**: Models are evaluated using various metrics to assess their accuracy and reliability in predicting stroke risk.

## Model Performace
- **Accuracy:** the model correctly predicts 94% of the cases. however, this metric can be misleading due to class imbalance
- **Precision:** when the model predicts a stroke, it is only correct 20% of the time, indicating a high number of false positives
- **Recall:** the model identifies only 3% of actual stroke cases, which highlights its sifnigicant limitation in detecting positive cases

## Challenges and improvements:
The model's performance is significantly impacted by class imbalance, where stroke are much less frequent than non-stroke cases. THe information that the number of "non-stroke" cases is 94,75% confirms that the dataset is highly imbalanced, which is one of the main challenges affecting your model's performace. This imbalance causes the model to lean towards predicting the majoritory class (non-stroke), resulting in high accurancy but low recall and precision for stroke cases.

## Fututre steps:
I'm currently working on implementing various strategies to improve the model's performance, focusing on enhancing its accurancy in prediction stroke cases.
