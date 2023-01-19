# credit_risk_analysis

# Overview

The goal of this project is to employ different techniques to train and evaluate models with unbalanced classes. We will be using libraries to build and evaluate models using resmapling. We will be oversampling the data using random over sampler and smote algorithms, and undersample the data using the clustercentroids. We will then use a combination of over and under sampling using Smoteenn. We will then compare the two new ML models that reduce bias to predict credit risk. 


# Results

### Random Imbalance

![random_imbalance.png](https://github.com/Adam-Warrick/credit_risk_analysis/blob/main/images/random_imbalanced.png)

### Undersampling

![undersampling.png](https://github.com/Adam-Warrick/credit_risk_analysis/blob/main/images/undersampling.png)

### Easy Ensemble

![easy_ensemble.png](https://github.com/Adam-Warrick/credit_risk_analysis/blob/main/images/easy_ensemble.png)

### Smote

![smote_imbalanaced.png](https://github.com/Adam-Warrick/credit_risk_analysis/blob/main/images/smote_imbalanced.png)

### Random Forest Classifier

![random_forest.png](https://github.com/Adam-Warrick/credit_risk_analysis/blob/main/images/random_forest.png)

### Combination

![combination_under_over.png](https://github.com/Adam-Warrick/credit_risk_analysis/blob/main/images/combination_under_over.png)

## Summary

The "Accuracy" column shows that the highest score (at 93%) is obtained by the EasyEnsembleClassifier model. And the lowest corresponds to the ClusterCentroids with just 53%.  The EasyEnsembleClassifier model again outperformed the others, with a score of 91%, followed by the SMOTEENN with only 69%. Worth noting that the Precision (7%) and F1 (14%) scores are also the highest with this model.
Because this data is so imbalanced (99.5% low risk vs. 0.5% high risk), it is not a surprise that every model has a precision of 100% for this class. When it comes to sensitivity and F1 scores, one more time, the EasyEnsembleClassfier tops with 94% and 97% respectively. And the lowest scores in both categories were obtained with the ClusterCentriods model (45% and 62%).
