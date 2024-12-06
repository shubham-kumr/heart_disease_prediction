# Heart Disease Prediction with Classification Algorithms

This project implements machine learning models to predict the likelihood of heart disease based on various medical features. We use several classification algorithms to achieve this goal, including Logistic Regression, Naive Bayes, and K-Nearest Neighbors (KNN), and evaluate their performance using metrics like accuracy and F1 score.

## Overview

The goal of this project is to predict whether a person is likely to develop heart disease based on a set of medical features. The dataset contains information about patients' medical history, including factors like age, blood pressure, cholesterol levels, and more. By training various classification models on this dataset, we aim to find the most accurate and reliable algorithm for heart disease prediction.

## Dataset

The dataset used in this project is publicly available and consists of several medical attributes that help in determining the likelihood of heart disease. The target variable is a binary classification (0 = No heart disease, 1 = Heart disease).

## Algorithms Implemented

1. **Logistic Regression**: A statistical method that models the relationship between a dependent binary variable and one or more independent variables.
2. **Naive Bayes**: A probabilistic classifier based on applying Bayes' theorem with strong independence assumptions between the features.
3. **K-Nearest Neighbors (KNN)**: A non-parametric method used for classification based on feature similarity.

The models are trained and evaluated on the same training and testing datasets to ensure a fair comparison.

## Evaluation Metrics

- **Accuracy**: Measures the proportion of correct predictions.
- **F1 Score**: A weighted harmonic mean of precision and recall, especially useful for imbalanced datasets.

## Requirements

- Python 3.x
- scikit-learn
- pandas
- matplotlib
- seaborn
- numpy
