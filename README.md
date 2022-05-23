![](https://storage.googleapis.com/kaggle-competitions/kaggle/5407/media/housesbanner.png)

# House Price Prediction with Mutiple Regression Models

## About

This work is for my final project of MSIS2631 - Machine Learning.

In this project, I used several different regressors such as `ElasticNet`, `Light Gradient Boost`, and `Random Forest`... to predict the house price.

For the hyperparameters tuning, I used `optuna`, a good automatic hyperparameter optimization software framework.

### Competition Overview

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

Link for this competition: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

Data used in this project: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

## Content

* EDA

* Data Cleaning & Imputation

* Feature Engineeering

* Tuning Hyperparameters with Optuna

* Model Stacking(In progress)

* File Output

## Dependencies

This work is based on python.

See all the needed libraries in "requirements.txt"

You can use "pip install -r requirements.txt" to replicate the environment used for this project. Make sure to new a python virtual environments to avoid conflicts.