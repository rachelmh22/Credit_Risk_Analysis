# Credit Risk Analysis

## Overview 

The purpose of this analysis is to execute a variety of machine learning models to assess whether individuals have low or high credit risks. The machine learning modules implemented include oversampling and undersampling the data, as we as a combination approach. In addition, two other machine learning models used include BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. 

## Results

### Random Oversampling

- balanced accuracy score: 65%
- precision score: high risk = 1% and low risk = 100%
- recall score: high risk = 62% and low risk = 68%

![random_oversampling](/images/random_oversampling.png)

### SMOTE Oversampling

- balanced accuracy score: 51%
- precision score: high risk = 1% and low risk = 100%
- recall score: high risk = 59% and low risk = 44%

![SMOTE_oversampling](/images/SMOTE_oversampling.png)

### Undersampling

- balanced accuracy score: 51%
- precision score: high risk = 1% and low risk = 100%
- recall score: high risk = 59% and low risk = 44%

![undersampling](/images/undersampling.png)

### Combination Sampling (SMOTEENN)

- balanced accuracy score: 64%
- precision score: high risk = 1% and low risk = 100%
- recall score: high risk = 70% and low risk = 57%

![combo](/images/combo.png)

### Balanced Random Forest Classifier

- balanced accuracy score: 68%
- precision score: high risk = 86% and low risk = 100%
- recall score: high risk = 37% and low risk = 100%

![BRFC](/images/BRFC.png)

### Easy Ensemble AdaBoost Classifier

- balanced accuracy score: 91%
- precision score: high risk = 7% and low risk = 100%
- recall score: high risk = 89% and low risk = 94%

![EEAC](/images/EEAC.png)

## Summary 

When looking at the results, the high risk scores are of interest since this analysis focuses on determining which individuals are low credit risk and high credit risk in order to predict loan status. The first four models for high risk status score 1% for precision with recall scores between 59% and 70%, while their balanced accuracy scores were in the 50 and 60 percent range. These results do not give confidence that these models are good predictors. On the other hand, the ensemble learning models had higher balanced accuracy scores, especially the Easy Ensemble AdaBoost Classifier with a score of 91%. The precision score was better for the Balanced Random Forest Classifier and the recall score was better for the Easy Ensemble AdaBoost Classifier. If recommending a model for predictions, the learning ensemble models would predict more accurate results according to the analysis. Additionally, if precision is more important then the Balanced Random Forest Classifier is a better model and if recall scores are more important then the Easy Ensemble AdaBoost Classifier would be the recommended model.
