# Bike Sharing Demand Prediction using Linear Regression
## Project Overview

This repository contains the implementation of a Multiple Linear Regression model to predict the demand for shared bikes based on various features like weather, season, and year. The dataset is provided by a US-based bike-sharing company to help them understand the key factors affecting bike demand. The model was built and evaluated using Python in a Jupyter Notebook.

This project includes:
1. A Python notebook that details data cleaning, feature engineering, model building, and evaluation.
2. A PDF document with answers to subjective questions related to linear regression concepts.

## Files Included
* Bike_Sharing_Final_Regression_Model.ipynb: A Jupyter notebook that includes the complete linear regression model.
* (Answered) Linear Regression Subjective Questions.pdf: A PDF file with answers to key questions related to linear regression.
* README.md: This file, which contains an overview of the project.

## Model Overview
The linear regression model predicts the number of bike rentals (cnt) based on factors such as:
* Weather conditions
* Temperature and wind speed
* Holiday or working day
* Seasonal effects

## Key Steps:
* Data Preprocessing: Handling missing values, feature scaling, and creating dummy variables for categorical features.
* Feature Selection: Using Recursive Feature Elimination (RFE) to select the most important features.
* Model Building: Implementing the regression model using scikit-learn and statsmodels.
* Evaluation: Calculating R-squared, analyzing residuals, and checking for multicollinearity using VIF.

## R-squared Score: 
The final R-squared score on the test set is 0.765, indicating a strong model that explains 76.5% of the variance in bike demand.

## How to Run the Code
1. Clone this repository:
git clone https://github.com/Satish006/Bike-Sharing-Demand-Linear-Regression.git
2. Open the Jupyter notebook (Bike_Sharing_Final_Regression_Model.ipynb) and run it cell by cell in your local environment or on Google Colab.
3. Review the (Answered) Linear Regression Subjective Questions.pdf for detailed answers to the subjective questions.

## Conclusion
This project showcases the successful application of linear regression for predicting bike-sharing demand. The model helps understand how various factors influence demand, providing actionable insights for business strategy. The process includes feature selection, evaluation of assumptions, and model refinement to ensure accuracy.


