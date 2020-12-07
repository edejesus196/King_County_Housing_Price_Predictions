# Kings County Housing Predictions
![seattle](https://github.com/edejesus196/King_County_Housing_Price_Predictions/blob/main/images/Downtownseattlerainier2015nst.jpg)

## Overview
This project will utilize multiple regression analysis to predict housing prices using data of homes sold in King County, WA, during 2014 and 2015. This dataset will be explored for completeness and integrity, relationships between attributes and target variable, and for feature engineering. Several models will be built and trained by SciKit python library to generate predictions on unseen data. A final model will be chosen based on its Root Mean Squared Error (RMSE) value. The data and project scope was provide by Flatiron School for Data Science Immersive program phase 2 final project.


## Repository Structure
    .
    ├── data                                # data folder
    ├── reference                           # project work book and reference files
    ├── images                              # project image/graph files
    ├── models                              # final regression models
    ├── results                             # model predicted file location
    ├── housing_price_prediction.ipynb      # final project notebook with EDA and model creation
    └── README.md

## Business Problem
A Seattle real estate company seeks to increase porfolio in King County Seattle and wants to accurately predict the sales price of a property. Having an accurate sales prediction will aid in strategizing the investment options to maximize their profit. A multiple linaer regression model will be built base on provided property data for this task. 

During the exploratory phase following questions will also be focused on:
1. What location in the county has the highest property value?
2. What aspects of the property brings value?
3. Do renovations have effect on property value?

## Approachcs
1. Check for data completeness and integrity
2. Perform EDA with statistical analysis to determine statistically significant features
3. Visualize statistically significant features
4. Engineer new features based on stastistical findings
5. Model Linear Regression models and evaluate each model for final implementation
6. Implement feature engineering and final model to the data set. 


## Modeling
Using Scikit-learn package 4 linear regression models were crated.
- Model 1 : Linear Regression
- Model 2 : Linear Regression with Kbest feature selection
- Model 3 : Linear Regression with Recursive Feature Elminiation and Cross Valdiation
- Model 4 : Linear Regression with Kbest feature selection with Ridge regression

It was determined that the simple Linear Regression with model perfromed the best and was utilized for the final implementation. 

## Summary
Basic linear Regression with no feature selection had the lowest Root Mean Square Error (RMSE) error value. These means that Model number 1 was better than the other models at prediction home prices on useen data. From the data set analysis and model coefficients, the features the have the highest impact on home prices are square foot living, number of bathrooms, number of bedrooms, grade, and condition.
