# Credit_Risk_Analysis

## Project Overview
Assist the client to predict credit risk using a variety of Resampling Models and algorithms. 

## Methodology
Tools/Programs/Languages used:

- imbalanced-learn library
- scikit-learn library
- ETL
- Machine Learning

I oversampled data via RandomOverSample and SMOTE algorithms using credit card credit dataset from LendingClub. ClusterCentroids algorithm was used to undersample the data. SMOTEENN algorithm was used for over-and-undersampling. Then I used two machine learning models to predict credit risk.

## Summary of Results

- Accuracy score of Random Oversampling using ```RandomOVersampler```
- Accuracy score 

![image](https://user-images.githubusercontent.com/44425379/166125433-788102ba-2d4f-4560-9ccb-615c7c9ceb5f.png)

- Accuracy score of SMOTE Oversampling using ```SMOTE```

![image](https://user-images.githubusercontent.com/44425379/166125438-5a1c4626-e965-4e2d-9b09-e7a30e95c7cd.png)

- Accuracy score of Undersampling using ```ClusterCentroids```

![image](https://user-images.githubusercontent.com/44425379/166125444-69d38603-a017-49eb-baf7-dd2513468cde.png)

- Accuracy score of Combination (Over and Under) Sampling using ```SMOTEENN```

![image](https://user-images.githubusercontent.com/44425379/166125448-b2deea13-e11d-4a19-bc46-efb475cc108e.png)

- Accuracy score of ML model using ```BalancedRandomForestClassifier```

![image](https://user-images.githubusercontent.com/44425379/166125457-6b63ff60-5105-4990-9ae2-5ed8b9032785.png)

- Accuracy score of ML model using ```EasyEnsembleClassifier```

![image](https://user-images.githubusercontent.com/44425379/166125452-49a3a3b4-6eee-4a25-ab51-edb6adb6332a.png)

## Recommendations

 - Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
