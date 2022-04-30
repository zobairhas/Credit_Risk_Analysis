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

<img>

- Accuracy score of SMOTE Oversampling using ```SMOTE```

<img>

- Accuracy score of Undersampling using ```ClusterCentroids```

<img>

- Accuracy score of Combination (Over and Under) Sampling using ```SMOTEENN```

<img>

- Accuracy score of ML model using ```BalancedRandomForestClassifier```

<img>

- Accuracy score of ML model using ```EasyEnsembleClassifier```

<img>

## Recommendations

 - Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.