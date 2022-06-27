# titanic_survival_prediction_kaggle
Survival Prediction of the Titanic Disaster based on Kaggle Dataset.

# Project: Titanic - Machine Learning from Disaster

Predict survival on the Titanic

##### Kaggle link: https://www.kaggle.com/competitions/titanic/overview

Courtesy:
* https://www.kaggle.com/code/ccastleberry/titanic-cabin-features
* https://www.kaggle.com/code/gunesevitan/titanic-advanced-feature-engineering-tutorial
* https://www.kaggle.com/code/yassineghouzam/titanic-top-4-with-ensemble-modeling

## Problem Statement: Predict the survival from Titanic

Using the provided train and test data, we have to predict the `Surivived` column where `1` means `Survived` and `0` means `Not Survived`.

**Train Data** : Train data has features columns and target variable (`Survived`) column.

**Test Data** : Test only has features columns and do not have the `Survived` column. We will not going to using test data while building our model and also to check accuracy during testing of multiple models. Only use test data for final prediction. (This will prevent overfitting of ML models till some extent.)

**Submission Data** : We have to submit our prediction in this format. It will have `PassengerId` and `Survived` column.

## Task to perform to solve the problem:
* Exploratory Data Analysis
* Data Preprocessing & Feature Engineering
* Data Preparation for Machine Learning
* Implement Machine Learning Models and compare accuracy
* Ensembling (Stacking of multiple ML models)
* Final Prediction using final ML model with Test Data
