# COVID-19 Patient Mortality Prediction

This repository contains a project aimed at predicting patients at high risk of death from COVID-19 using machine learning models. The primary focus is on addressing class imbalance using undersampling techniques and comparing the performance of various models.

## Project Overview

The main goal of this project is to predict the mortality risk of COVID-19 patients based on medical data. The project compares several machine learning algorithms to find the one that offers the best sensitivity, particularly for identifying high-risk patients.

### Models Used:
- Logistic Regression
- Decision Tree
- Gaussian Naive Bayes
- Bernoulli Naive Bayes

### Key Findings:
- **Logistic Regression** had the best sensitivity in identifying high-risk patients, compared to other models.
- Undersampling was used to handle the imbalance in the dataset.

## Requirements

To run the notebook and replicate the results, install the required dependencies:

```bash
pip install -r requirements.txt
