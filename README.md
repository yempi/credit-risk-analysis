# credit-risk-analysis

## Overview
In this project we will be using Machine Learning to assess credit card risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. There will be the need to use different techniques to train and evaluate models with unbalanced classes: imbalanced-learn and scikit-learn libraries will be used to build and evaluate models using resampling.

What will be done:
  1. Use resampling models 
  2. Use the SMOTEENN algorithm 
  3. Use ensemble classifiers

## Results
The results from the six different machine learning models are as follows:

1. **Naive Random Oversampling**
- Balanced Accuracy Test:     65%

- Precision:
  - high-risk loans:          low
  - low-risk loans:           high    
            
- Recall:                     
  - high-risk loans:          0.72
  - low-risk loans:           0.59



2. **SMOTE Oversampling**
- Balanced Accuracy Test:     66%

- Precision:
  - high-risk loans:          low
  - low-risk loans:           high    
            
- Recall:                     
  - high-risk loans:          0.63
  - low-risk loans:           0.69



3. **Undersampling
- Balanced Accuracy Test:     66%

- Precision:
  - high-risk loans:          low
  - low-risk loans:           high    
            
- Recall:                     
  - high-risk loans:          0.69
  - low-risk loans:           0.40



4. **Over and Undersampling
- Balanced Accuracy Test:     54%

- Precision:
  - high-risk loans:          low
  - low-risk loans:           high    
            
- Recall:                     
  - high-risk loans:          0.72
  - low-risk loans:           0.57



5. **Balanced Random Forest Classifier
- Balanced Accuracy Test:     78%

- Precision:
  - high-risk loans:          low
  - low-risk loans:           high    
            
- Recall:                     
  - high-risk loans:          0.69
  - low-risk loans:           0.88



6. **Easy Ensemble AdaBoost Classifier
- Balanced Accuracy Test:     91%

- Precision:
  - high-risk loans:          low
  - low-risk loans:           high    
            
- Recall:                     
  - high-risk loans:          0.89
  - low-risk loans:           0.94



## Summary

