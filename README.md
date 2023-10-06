# Project 2 - Ames Housing Data and Kaggle Challenge

#### Problem Statement

As a new hire for zillow, i have been asked to create a predictive model for homes 
in Ames, Iowa. the 2 forms of data sets which we use to create these models is 
1. the 'training' dataset(train.csv);
2. the 'testing' dataset (test.csv).  

Zillow's Data Analytics team and I plan first to do some Exploratory Data Analysis
(EDA) to search for any outliers or otherwise apprehensive data.  Next, we will clean
the data for any detected errors and deal with null values.  Finally, we will iteratively
run different regression models on selected features, or variable inputs, to build a 
model that predicts the home sale price of home listings in Aimes, Iowa.

Kaggle, the Data Science website, has a 'holdout' data set, or
a collection of unseen data, for Aimes, Iowa, which we will be able to test our model
against.  After building our models, we will run them on the 'test' set, and upload
the resulting predictions to Kaggle.  Kaggle will then return the Root Mean Squared
Error of those predictions against the true home sale prices.  The Root Mean Squared
Error, essentially, is the average difference between a home's actual sale price and
its predicted sale price.  This being said, we want our model to have an RMSE as close
to 0 as possible.  The model with the lowest RMSE will be chosen as our winner!
