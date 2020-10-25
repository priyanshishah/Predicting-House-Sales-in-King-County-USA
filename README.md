# Predicting-House-Sales-in-King-County-USA
Project of Data Analysis with Python from Coursera

# Introduction

The objective is to create a linear regression model for a given dataset( House Sales in King County, USA). The overall idea of regression is to examine two things: 
(1) does a set of predictor variables do a good job in predicting an outcome (dependent) variable? 
(2) Which variables in particular are significant predictors of the outcome variable, and in what way do they–indicated by the magnitude and sign of the beta estimates–impact the outcome variable? These regression estimates are used to explain the relationship between one dependent variable and one or more independent variables.

Linear Regression Analysis consists of more than just fitting a linear line through a cloud of data points. 
It consists of 3 stages – 
(1) analyzing the correlation and directionality of the data.
(2) estimating the model, i.e., fitting the line.
(3) evaluating the validity and usefulness of the model.

# Data Description
In this dataset we have to predict the sales price of houses in King County, Seattle. It includes homes sold between May 2014 and May 2015. Before doing anything we should first know about the dataset what it contains what are its features and what is the structure of data.

The dataset cantains 20 house features plus the price, along with 21613 observations.

 Data Link: https://s3-api.us-geo.objectstorage.softlayer.net/cf-courses-data/CognitiveClass/DA0101EN/coursera/project/kc_house_data_NaN.csv

# Model Development 
Simple Linear Regression:

1) 'bedrooms' vs 'price'
2) 'grade' vs 'price'

Multiple Regression:

1) 'bedrooms','grade', 'sqft_living', 'sqft_above'
2) 'bedrooms','bathrooms', 'sqft_living', 'sqft_lot', 'floors', 'waterfront', 'view', 'grade', 'sqft_above', 'sqft_basement', 'lat', 'sqft_living15'

Polynomial Regression:

1) degree=2
2) degree=3
