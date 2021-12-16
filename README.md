# Credit Risk Analysis

## Overview
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. This analysis was completed to understand and compare various linear models with unbalanced classes. The scikit-learn libraries were used  - and the following models were tested and compared:
* Naive Oversampling
* SMOTE Oversampling
* Cluster Centroid Undersampling
* SMOTEEN Combination Sampling
* Easy Ensemble AdaBoost Classifier
* Balanced Random Forest Classifier 


## Results
### Naive Oversampling
65.5% Accuracy Score
![](./Resources/naive_oversampling.png)

### SMOTE Oversampling
67.4% Accuracy Score
![](./Resources/SMOTE_oversampling.png)

### Cluster Centroid Undersampling
54.4% Accuracy Score
![](./Resources/cluster_centroid.png)

### SMOTEEN Combination Sampling
66.7% Accuracy Score
![](./Resources/SMOTEEN_combination.png)

### Easy Ensemble AdaBoost Classifier
93.2% Accuracy Score
![](./Resources/easy_ensemble_adaboost.png)

### Balanced Forest Classifier
78.8% Accuracy Score
![](./Resources/balanced_forest.png)


## Summary
Based on this analysis, the easy ensemble classifier models should be used. Thi model has a 93.2% accuracy score and should be trusted over the other under and combination resampling models. 

