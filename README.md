# Credit_Risk_Analysis
## Overview 
The overview of this challenge was to build machine learning models to build credit risk. We built these models through Python. Below we see the results for the different kind of models that were made to predict this data. 
## Results 
### Random OverSample Model

![image1](https://github.com/mckjack/Credit_Risk_Analysis/blob/main/Images/Oversampling.png)
- we see here that the balance accuracy score was 63%
- high risk precision is 1 %  with 71% sensitivity resulting in a F1 of 2%
- low risk precision is 100% with 54% sensitivity

### SMOTE 
![image 2](https://github.com/mckjack/Credit_Risk_Analysis/blob/main/Images/SMOTE.png)
- balance accuracy score of 66%
- high risk precision is 1% with 62% sensitivity resulting in a F1 of 2%
- low risk precision is 100% with 67% sensitivity

### Undersampling 
![image 3](https://github.com/mckjack/Credit_Risk_Analysis/blob/main/Images/Undersampling.png)
- balance accuracy score of 52%
- high risk precision of 1% with 61% sensitivity resulting in a F1 of 1%
- low risk precision of 100% with 43% sensitivity

### Over and Under Sampling Combo
![image 4](https://github.com/mckjack/Credit_Risk_Analysis/blob/main/Images/Combo.png)
- balance accuracy score of 63%
- high risk precision of 1% with 71% sensitivity with 2% F1
- alot of false positives of low risk with sensitivity of 54%

### Ensemble Classifier
![image 5](https://github.com/mckjack/Credit_Risk_Analysis/blob/main/Images/Ensemble.png)
- balance accuracy score of 93% 
- high risk precision of 7% with 91% sensitivity resulting in 14% F1
- low risk precision of 100% with 94% sensitivity

### Balanced Classifier
![image6](https://github.com/mckjack/Credit_Risk_Analysis/blob/main/Images/Boosted.png)
- balance accuracy score of 79%
- high risk precision of 4% with 67% sensitivity resulting in 7% F1
- low risk precision of 100% with 91% sensitivity

## Summary 
Every single one of the machine learning models to predict high risk credit does a poor job at precision. The ensemble classifier was the only model to have a significant difference in predicting high risk credit  due to a precision of 7% with 91% sensitivity. However, with a lot of false positives found using every single model with the low risk precision being 100% for every model meaning some high risk credits are getting falsely detected. This means the bank's strategy could suffer. Because of this we would not suggest any models to predict credit risk. 


