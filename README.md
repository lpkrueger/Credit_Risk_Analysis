# Credit_Risk_Analysis
Module 18 Challenge, Big Data - UNCCH Data Analytics Bootcamp, Spring 2023

## Project Overview

### Purpose
In this exercise, I assisted Jill with applying machine learning to a dataset to help determine credit risk, an inherently unbalanced classification problem that requires us to train and evaluate models with unbalanced classes. 

## Method
Python libraries "imbalanced-learn" and "scikit-learn" were used to evaluate different machine learning models by resampling a dataset to determine which is better at predicting credit risk.

From the Module 18 Challenge:
```
    Deliverable 1: Use Resampling Models to Predict Credit Risk.
    Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk.
    Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk.
    Deliverable 4: A Written Report on the Credit Risk Analysis (README.md).
```

- Links to notebook files for analysis using imbalanced-learn and scikit-learn in Jupyter Notebooks
    - [credit_risk_resampling](credit_risk_resampling.ipynb)
    - [credit_risk_ensemble](credit_risk_ensemble.ipynb)

## Results

- Random Oversampling
    - Balanced Accuracy Score = 0.64
    - Precision Score = 0.99
    - Recall Score = 0.60
    ![RandomOversampling](/RandomOversampling.png)
    
- SMOTE Oversampling
    - Balanced Accuracy Score = 0.66
    - Precision Score = 0.99
    - Recall Score = 0.69
    ![SMOTEOversampling](/SMOTEOversampling.png)

- Undersampling
    - Balanced Accuracy Score = 0.64
    - Precision Score = 0.99
    - Recall Score = 0.57
    ![Undersampling](/Undersampling.png)

- Combination (Over and Under) Sampling
    - Balanced Accuracy Score = 0.67
    - Precision Score = 0.99
    - Recall Score = 0.57
    ![CombinationSampling](/CombinationSampling.png)

- Balanced Random Forest Classifier
    - Balanced Accuracy Score = 0.79
    - Precision Score = 0.99
    - Recall Score = 0.87
    ![BalancedRandomForest](/BalancedRandomForest.png)

- Easy Ensemble AdaBoost Classifier
    - Balanced Accuracy Score = 0.92
    - Precision Score = 0.99
    - Recall Score = 0.90
    ![EasyEnsemble](/EasyEnsemble.png)

## Summary 

I would recommend using (1) Easy Ensemble or (2) Balanced Random Forest models for this analysis, as they provide the highest balanced accuracy scores and recall scores of all the models used. Thus the most accurate predictions of credit risk could be expected from these models. 

