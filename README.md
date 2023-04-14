# Credit_Risk_Analysis

## Project Overview
In this project, three supervised machine learning models are compared to determine which model is better at predicting credit risk. Credit card credit dataset from LendingClub, a peer-to-peer lending services company, is used in this project. 

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, in this project, different techniques are used to train and evaluate models with unbalanced classes. Libraries such as imbalanced-learn and scikit-learn are used to build and evaluate models using resampling. 

Oversampling of the data using the RandomOverSampler and SMOTE algorithms, and undersampling of the data using the ClusterCentroids algorithm is used. A combinatorial approach of over- and undersampling using the SMOTEENN algorithm is used in the comparison as well. Two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, are used also to predict credit risk. Performance of all mentioned models with regards to predicting credit risk is evaluated. 

## Objective

1. Use Resampling Models to Predict Credit Risk.
2. Use the SMOTEENN Algorithm to Predict Credit Risk.
3. Use Ensemble Classifiers to Predict Credit Risk.
4. A Written Report on the Credit Risk Analysis (README.md).

## Results
[credit_risk_resampling](https://github.com/MSF2141/Credit_Risk_Analysis/blob/e3dac1e8ea263f2918c6b63b685fed13fe9cc7f9/credit_risk_resampling.ipynb) code.
- Naive Random Oversampling
![Naive%20Random%20Oversampling](https://github.com/MSF2141/Credit_Risk_Analysis/blob/7d7c69787617c3d44effb85f8161b18b11a94422/Naive%20Random%20Oversampling.png)

- SMOTE Oversampling
![SMOTE%20Oversampling](https://github.com/MSF2141/Credit_Risk_Analysis/blob/3f1b7078ffc8ec7be978daa47b67d49858cf29de/SMOTE%20Oversampling.png)

- Undersampling

- Combination Sampling

- Balanced Random Forest Classifier

- Easy Ensemble AdaBoost Classifier 



