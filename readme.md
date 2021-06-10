# About
This repository contains the application of SMOTE (Synthetic Minority Oversampling Technique) on an imbalanced dataset, and evaluation of some popular Classification models on the dataset, before and after applying SMOTE.

Source: [Credit Card Fraud Detection with SMOTE handling](https://www.kaggle.com/himanshuyadav95627/credit-card-fraud-detection-with-smote-handling/notebook)

# Problem
**Problem statement**: For this toy problem, we have a dataset of transactions occurred in a range of time using credit card. Our goal is to detect any fradulant transaction by using this dataset so that in future this does not take place. Another name for this task is Anomaly Detection.<br>

**Our dataset**:<br>
- Have feature columns V1,V2...v28 some attribute .<br>
- Time of transaction (Time column)<br>
- Transited amount (Amount column)<br>
- Class Feature this is the response variable and it takes value 1 in case of fraud and 0 otherwise.<br>

**Library used in this code sample**:<br>
- *numpy* and *pandas*: preprocessing, loading the dataset
- *matplotlib* and *seaborn*: plotting and visualizing
- *imblearn*: implementation of SMOTE
- *sklearn*: implementation of a variety of classification models, *e.g.*: Logistic Regression, Decision Tree.
