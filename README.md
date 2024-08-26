# Fraud Detection Prediction

This repository contains a machine learning project aimed at predicting fraudulent transactions based on transaction data. The project leverages classification algorithms to determine the best performing model for fraud detection.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Data](#data)
- [Feature Engineering](#feature-engineering)
- [Modeling](#modeling)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
Fraud detection is crucial in financial systems to identify and prevent fraudulent transactions. This project explores various machine learning models to predict whether a transaction is fraudulent based on transaction features. The models used include Logistic Regression and Decision Tree Classifier.

## Installation
To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/your-username/fraud-detection-prediction.git
```

Make sure you have the following Python packages installed:
- `pandas`
- `numpy`
- `plotly`
- `scikit-learn`
- `warnings`

## Data

The dataset used in this project includes information about transactions. The data is used to train and evaluate the models.

Data File: *fraud.csv*

## Feature Engineering

Feature engineering enhances the model's performance. In this project:
- Transaction types were mapped to numerical values.
- Only numerical columns were used for correlation analysis.
- Features with high correlation were identified to avoid multicollinearity.

## Modeling

Two classification models were applied to the dataset:
- **Logistic Regression**
- **Decision Tree Classifier**
- 
Each model was evaluated based on the following metrics:
- **Accuracy Score**
- **ROC AUC Score**

## Results

The performance of each model was evaluated, and the results are as follows:

- **Logistic Regression**
  - **Accuracy:** 0.9995
  - **ROC AUC Score:** 0.9918
- **Decision Tree Classifier**
  - **Accuracy:** 0.9989
  - **ROC AUC Score:** 0.5747

## Conclusion

This project demonstrates the effectiveness of various machine learning models in predicting fraudulent transactions. Based on the evaluation metrics, the Logistic Regression model outperforms the Decision Tree Classifier with a significantly higher ROC AUC Score of 0.9918. This indicates the Logistic Regression model's superior ability to distinguish between fraudulent and non-fraudulent transactions, making it the recommended model for deployment in real-world fraud detection scenarios.
