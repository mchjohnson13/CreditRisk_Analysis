# Credit Risk Analysis
## Overview
The purpose of this analysis was to use different techneques to train and evaluate models with unbalanced classes.

## Results
### Native Oversampling
![ros_classification_report](./images/ros.png)  
precision: 0.01  
recall: 0.74  
f1: 0.02  

### SMOTE Oversampling
![smote_classification_report](./images/smote.png)  
precision: 0.01  
recall: 0.63  
f1: 0.02  

### Undersampling
![cc_classification_report](./images/cc.png)  
precision: 0.01  
recall: 0.67  
f1: 0.01  

### Combination Sampling
![smoteenn_classification_report](./images/smoteenn.png)  
precision: 0.01  
recall: 0.70  
f1: 0.02  

### Balanced Random Forest Classifier
![brfc_classification_report](./images/brfc.png)  
precision: 0.01  
recall: 0.70  
f1: 0.06  

### Easy Ensemble AdaBoost Classifier
![eec_classification_report](./images/eec.png)  
precision: 0.09  
recall: 0.92  
f1: 0.16  

## Summary
None of the models yeild acceptable precision or accuracy in predicting high risk loans.
