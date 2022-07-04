# Credit Risk Analysis

## Overview 

The purpose of this analysis is to execute a variety of machine learning models to assess whether individuals have low or high credit risks. The machine learning modules implemented include oversampling and undersampling the data, as we as a combination approach. In addition, two other machine learning models used include BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Results

### Random Oversampling

- balanced accuracy score: 65%
- precision score: high risk = 1% and low risk = 100%
- recall score: high risk = 62% and low risk = 68%

### SMOTE Oversampling

- balanced accuracy score: 51%
- precision score: high risk = 1% and low risk = 100%
- recall score: high risk = 59% and low risk = 44%

### Undersampling

- balanced accuracy score: 51%
- precision score: high risk = 1% and low risk = 100%
- recall score: high risk = 59% and low risk = 44%

### Combination Sampling (SMOTEENN)

- balanced accuracy score: 64%
- precision score: high risk = 1% and low risk = 100%
- recall score: high risk = 70% and low risk = 57%

### Balanced Random Forest Classifier

- balanced accuracy score: 68%
- precision score: high risk = 86% and low risk = 100%
- recall score: high risk = 37% and low risk = 100%

### Easy Ensemble AdaBoost Classifier

- balanced accuracy score: 91%
- precision score: high risk = 7% and low risk = 100%
- recall score: high risk = 89% and low risk = 94%

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
