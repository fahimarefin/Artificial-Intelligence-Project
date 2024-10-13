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

To run the notebook and replicate the results, install the required dependencies.

### Major Libraries:
- Scikit-learn
- Pandas
- NumPy

## Instructions

1. Clone the repository from GitHub.
2. Open the Jupyter notebook (`code.ipynb`) and run all the cells to reproduce the model training and evaluation.

## Conclusion

The Logistic Regression model showed better sensitivity compared to the Decision Tree, Gaussian Naive Bayes, and Bernoulli Naive Bayes models, making it the best choice for predicting high-risk COVID-19 patients.
"""
