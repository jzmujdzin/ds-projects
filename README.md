Repository will consist of a few data science projects. Data is stored in data directory. Each analysis is in separate notebook, with EDA and models used.

# Wine Classification
The notebook consists of two approaches: regression and classification. The aim was to a) predict the score of a wine from available data b) predict whether the wine was good. Using different methods, xgboost proved to be the best for both approaches.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)

## General info
Regression predictions are made using OLS and XGBRegressor. For the classification case, SVC, Logistic Regression, KNN, XGBClassifier, Naive Bayes algorithms were used. In both cases, hyperparameter optimization was implemented, where RandomSearch and GridSearch were used to get better results. Finally, in the classification problem, dalex library was applied, to get a better understanding of XGB's blackbox for bussiness cases.
## Technologies
* Python 3.8
* NumPy 1.20.1
* pandas 1.2.4
* sklearn 1.01
* xgboost 2.0.0
* statsmodels 0.11
* dalex 2.4.0

