# Credit Risk Analysis

## Overview
Several models were implemented to perform the credit risk analysis since credit risk is prone to have unbalanced classification problem. 
Libraries used:
- imbalanced-learn
- scikit-learn

Models used:
- Oversampling with RandomOverSampler & SMOTE
- Undersampling with ClusterCentroids
- Combinatorial of over- and undersampling with SMOTEEN
- BalancedRandomForestClassifier & EasyEnsembleClassifier to predict credit risk

## Results
### Naive Random Oversampling
- Accuracy score: 65.4%
- Precision score for high credit risk: 0.01
- Recall scorefor high credit risk: 0.70

![naive_random_oversampling](https://github.com/junepwk/credit-risk-analysis/blob/main/Resources/naive_random_oversampling.png)

### SMOTE Oversampling
- Accuracy score: 66.2%
- Precision score for high credit risk: 0.01
- Recall scorefor high credit risk: 0.63

![smote](https://github.com/junepwk/credit-risk-analysis/blob/main/Resources/smote.png)

### ClusterCentroids
- Accuracy score: 54.4%
- Precision score for high credit risk: 0.01
- Recall scorefor high credit risk: 0.69

![clustercentroids](https://github.com/junepwk/credit-risk-analysis/blob/main/Resources/clustercentroids.png)

### SMOTEENN
- Accuracy score: 64.6%
- Precision score for high credit risk: 0.01
- Recall scorefor high credit risk: 0.72

![combination](https://github.com/junepwk/credit-risk-analysis/blob/main/Resources/combination.png)

### Balanced Random Forest Classifier
- Accuracy score: 69.3%
- Precision score for high credit risk: 0.95
- Recall scorefor high credit risk: 0.39

![randomforest](https://github.com/junepwk/credit-risk-analysis/blob/main/Resources/randomforest.png)

### Easy Ensemble AdaBoost Classifier
- Accuracy score: 93.2%
- Precision score for high credit risk: 0.09
- Recall scorefor high credit risk: 0.92

![easyensemble](https://github.com/junepwk/credit-risk-analysis/blob/main/Resources/easyensemble.png)

## Summary
