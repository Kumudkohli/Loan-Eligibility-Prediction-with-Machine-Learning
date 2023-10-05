# Loan Eligibility Prediction with Machine Learning

## Overview

This project aims to automate the loan eligibility process for the Dream Housing Finance company by using various machine learning algorithms. The goal is to identify eligible customers for home loans based on customer details provided during the online application process. The provided dataset contains information such as Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, and more.

## Task Requirements

### Classification Models

- Decision Tree
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Any other algorithm of your choice

### GridSearchCV for Hyperparameter Tuning

We will use GridSearchCV to find the best model with optimal hyperparameters for each algorithm. This allows us to improve the performance of our models and ensure they generalize well to new data.

The workflow includes the following steps:

1. Build models using different ML algorithms.
2. Create a parameter grid for each algorithm.
3. Run GridSearchCV to find the best hyperparameters for each model.
4. Choose the best model with the best hyperparameters.
5. Evaluate and report the best accuracy achieved by each algorithm.
6. Benchmark the best accuracy obtained for each classification algorithm.

## Getting Started

Follow these steps to reproduce the results and run the code:

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/loan-eligibility-prediction.git
