# Credit_Risk_Analysis

## Overview

The purpose fo this analyis is to utilize machine learning to predict credit risk from a credit card dataset from LendingClub. The analysis utilizes imbalanced-learn, scikit-learn, RandomOverSampler, SMOTE, SMOTEEN, ClusterCentroids, BalancedRandomForestClassifier, and EasyEnsembleClassifier.

## Results

Review of each of the 6 models showed the following results.

### RandomOverSampler

- calculated balanced accuracy score = 0.637
- precision = 0.01 high risk & 1.00 low risk with an average of 0.99
- recall = 0.62 high risk & 0.65 low risk with an average of 0.65

![image](https://user-images.githubusercontent.com/90691846/150169014-596ede3a-4bfe-4498-9c6e-6fefb82f07d9.png)

### SMOTE Oversampling

- calculated balanced accuracy score = 0.63
- precision = 0.01 high risk & 1.00 low risk with an average of 0.99
- recall = 0.62 high risk & 0.64 low risk with an average of 0.64

![image](https://user-images.githubusercontent.com/90691846/150169316-ef1decba-7df8-4bbf-a0e4-c012973aaafb.png)


### ClusterCentroid Undersampling

- calculated balanced accuracy score = 0.516
- precision = 0.01 high risk & 1.0 low risk with an average of 0.99
- recall = 0.60 high risk & 0.43 low risk with an average of 0.44

![image](https://user-images.githubusercontent.com/90691846/150169639-efc5a20d-db7e-4bd2-848d-9b600d39f6b3.png)

### SMOTEENN Combination Over and Under Sampling

- calculated balanced accuracy score = 0.625
- precision = 0.01 high risk & 1.0 low risk with an average of 0.99
- recall = 0.71 high risk & 0.54 low risk with an average of 0.54

![image](https://user-images.githubusercontent.com/90691846/150169922-49667d22-73bd-4947-8f66-7e40f420fae2.png)

### BalancedRandomForestClassifier

- calculated balanced accuracy score = 0.788
- precision = 0.01 high risk & 1.0 low risk with an average of 0.99
- recall = 0.67 high risk & 0.91 low risk with an average of 0.91

![image](https://user-images.githubusercontent.com/90691846/150170151-c9e1f3e6-b43a-40b9-9036-ca8c500d93f7.png)

### EasyEnsembleClassifier

- calculated balanced accuracy score = 0.92
- precision = 0.07 high risk & 1.0 low risk with an average of 0.99
- recall = 0.90 high risk & 0.94 low risk with an average of 0.94

![image](https://user-images.githubusercontent.com/90691846/150170350-405990f5-8eb4-4ebb-900a-729d6978665b.png)

## Summary

If we were to look at numbers alone and assume the higher the number means the better suited model, then the EasyEnsembleClassifier would be the best model to utilize. This model ahd the highest accuracy, precision, and recall of all 6 models.


