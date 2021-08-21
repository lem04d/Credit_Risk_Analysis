# Credit_Risk_Analysis

# Purpose

The purpose of this is to use the credit card credit dataset from LendingClub and over and under-sample the data and use two machine learning models that reduce bias to predict credit risk. Once that is completed, the performance of these models will be evaluated and a written recommendation will be made on whether they should be used to predict credit risk.


# Results

### Naive Random Oversampling:

![image](Credit_Risk_Analysis/Naive_Random_Oversampling.png)

Balanced Accuracy Score: 0.67
The high_risk precision is .01, recall score of 0.67 and an F1 score of 0.02
The high number of the low_risk population shows a precision of 0.99 with a sensitivity of 0.67 and an F1 score of 0.80


### SMOTE Oversampling:
![image](Credit_Risk_Analysis/SMOTE_Oversampling.PNG)
Balanced Accuracy Score: 0.63
The high_risk precision is .01, recall score of 0.57 and an F1 score of 0.02
The high number of the low_risk population shows a precision of 1.0 with a sensitivity of 0.68 and an F1 score of 0.81


### Cluster Centroids Undersampling:

![image](Credit_Risk_Analysis/Cluster_Centroids_Resampler.PNG)
Balanced Accuracy Score: 0.63
The high_risk precision is .01, recall score of 0.57 and an F1 score of 0.02
The high number of the low_risk population shows a precision of 1.0 with a sensitivity of 0.68 and an F1 score of 0.81


### SMOTEENN - Combination Sampling to assess Credit Risk:

![image](Credit_Risk_Analysis/SMOTE_Oversampling.PNG)

Balanced Accuracy Score: 0.65
The high_risk precision is .01, recall score of 0.72 and an F1 score of 0.02
The high number of the low_risk population shows a precision of 1.0 with a sensitivity of 0.58 and an F1 score of 0.73

## Using Ensemble Algorithms to assess Credit Risk

### Balanced Random Forest Classifier:

![image](Credit_Risk_Analysis/Balanced_Random_Forest_Classfier.PNG)

Balanced Accuracy Score: 0.79
The high_risk precision is .03, recall score of 0.71 and an F1 score of 0.06
The high number of the low_risk population shows a precision of 1.0 with a sensitivity of 0.88 and an F1 score of 0.93

### Easy Ensemble Classifier

![image](Credit_Risk_Analysis/Easy_Ensemble_Classifier.PNG)

Balanced Accuracy Score: 0.926
The high_risk precision is .08, recall score of 0.91 and an F1 score of 0.14
The high number of the low_risk population shows a precision of 1.0 with a sensitivity of 0.94 and an F1 score of 0.97

# Summary
