# # Welcome to this Credit Score Classification Project

In this project, we aimed to build machine learning models for a credit scores classification dataset. 
The dataset is downloaded from https://www.kaggle.com/datasets/clkmuhammed/creditscoreclassification. It is separated as training dataset and testing dataset already, and the training dataset will be used for training machine learning models. The training dataset contains credit score (Poor, Standard, Good), the target variable, and other features of the person like occupation, income, number of bank accounts, payment behaviour, etc. 

We will first use feature selection methods (K-Best, Variance Threshold) to select suitable features in training dataset, then run machine learning models to them by applying different combinations of feature scaling methods (Standard Scaler, MinMax Scaler, Robust Scaler) with different common algorithms (logistic regression, k-nearest neighbors, random forest, adaboost, etc.). After trying different combinations of feature selection, feature scaling and common algorithms, we will pick the best model and use it to make predictions on some new data get from the testing dataset.
