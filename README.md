# British Airways Booking Predictions

## Overview
### This project is intended to use data from British Airways (BA) to build, test, and validate models for predicting whether or not a customer will book a trip. 
### Fourteen columns of data were provided, for 50,000 customer interactions with BA, and the goal was to find a combination chosen from the first thirteen columns to be able to predict whether or not a customer would book a trip with BA.

## Features
### Four models were trained and fit to the data, using both Random Forest and XGBoost classifiers, with either all variables (columns) used as predictors or just the six variables with the highest mutual information scores. The Random Forest model with all variables was found to be the best, based on accuracy and AUC.

## Running the Project
### All that is required to run the project locally is the data file and Python, as well as the imported libraries that were used to produce the models.

## Dependencies
