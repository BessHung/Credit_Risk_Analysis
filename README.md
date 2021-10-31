# Credit Risk Analysis

## Overview 
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, apply several machine learn models to predict credit risk. Then, we will evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk. 

## Result

### RandomOverSampler model evaluation
- Balanced accuracy scores: 66.03%
- Precision scores for high risk: 1%
- Recall scores for high risk: 74%
- Precision scores for low risk: 100%
- Recall scores for low risk: 58%

###### Screenshot of RandomOversampler model output 
![](Results/RandomOversampler.png)

### SMOTE model evaluation
- Balanced accuracy scores: 65.37%
- Precision scores for high risk: 1%
- Recall scores for high risk: 62%
- Precision scores for low risk: 100%
- Recall scores for low risk: 68%
###### Screenshot of SMOTE model output 
![](Results/SMOTE.png)

### ClusterCentroids model evaluation
- Balanced accuracy scores: 54.43%
- Precision scores for high risk: 1%
- Recall scores for high risk: 69%
- Precision scores for low risk: 100%
- Recall scores for low risk: 40%
###### Screenshot of ClusterCentroids model output 
![](Results/ClusterCentroids.png)

### SMOTEENN model evaluation
- Balanced accuracy scores: 63.66%
- Precision scores for high risk: 1%
- Recall scores for high risk: 70%
- Precision scores for low risk: 100%
- Recall scores for low risk: 57%
###### Screenshot of SMOTEENN model output 
![](Results/SMOTEENN.png)

### BalancedRandomForestClassifier model evaluation
- Balanced accuracy scores: 78.85%
- Precision scores for high risk: 3%
- Recall scores for high risk: 70%
- Precision scores for low risk: 100%
- Recall scores for low risk: 87%
###### Screenshot of BalancedRandomForestClassifier model output 
![](Results/BalancedRandomForestClassifier.png)

### EasyEnsembleClassifier model evaluation
- Balanced accuracy scores: 93.17%
- Precision scores for high risk: 9%
- Recall scores for high risk: 92%
- Precision scores for low risk: 100%
- Recall scores for low risk: 94%
###### Screenshot of EasyEnsembleClassifier model output 
![](Results/EasyEnsembleClassifier.png)

## Summary
