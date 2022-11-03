# Credit_Risk_Analysis

## Analysis

The purpose of this analysis is to predict credit risk for Lending Club's customers, a peer-to-peer lending services company. We did this by employing different techniques to train and evaluate models with unbalanced classes such as RandomOverSampler, SMOTE, Cluster Centroids, SMOTEENN, and Classifiers. These techniques can be found in the imbalanced-learn and scikit-learn libraries. Using these methods, we'll be able to find out how effective our models are at predicting credit risk.

## Results
----------------------------

- Naive Random Oversampling
The Balanced Accuracy score is 65%, the F1 score for high_risk class is very low at .02% due to low pre from the high_risk class

![image](https://user-images.githubusercontent.com/108442512/199774448-454420c7-7e3d-4b9f-abf4-7e369e71c8ca.png)

- SMOTE Oversampling
The Balanced Accuracy score is 66%, the F1 score for high_risk class is very low at .02% due to low pre from the high_risk class

![image](https://user-images.githubusercontent.com/108442512/199775228-46236e5d-5fbf-4eea-9647-57fb84dd06f1.png)

- Undersampling
The Balanced accuracy score is 66%, the F1 score for high_risk class is very low at .01% due to low pre from the high_risk class

![image](https://user-images.githubusercontent.com/108442512/199775985-5de3f1a5-6a6c-4767-9895-1b1ee20c96d0.png)

- Combination (Over and Under) Sampling
The Balanced accuracy score is 54%, the F1 score for high_risk class is very low at .02% due to low pre from the high_risk class

![image](https://user-images.githubusercontent.com/108442512/199777099-8c3cf4f5-9ea7-4f8f-9d74-7564e894e480.png)

- Balanced Random Forest Classifier
The Balanced accuracy score is 79%, the F1 score for high_risk class is very low at .07% due to low pre from the high_risk class

![image](https://user-images.githubusercontent.com/108442512/199779206-b8a1ca55-61e8-4ace-9e44-83ad1142658e.png)

- Easy Ensemble AdaBoost Classifier
The Balanced accuracy score is 93%, the F1 score for high_risk class is very low at .14% due to low pre from the high_risk class

![image](https://user-images.githubusercontent.com/108442512/199779828-f78b99d3-494b-4fee-9be6-d43bcdf41aeb.png)

## Summary

All the models showed a low level of precision. For the first four models, we used several sampling methods to assess credit risk. The accuracy of the models was average but the ability to predict positive high_risk classes was extremely low. We were able to attain very high level of accuracy when we switch to classifiers however, we only saw small increase in precision for the high_risk classes. Due to the low precision rate for all six models, I wouldn't recommend using any of them with any confidence and would look to find different models or methods to try instead.

