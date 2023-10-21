# Documentation

## Packages Used

-Pandas: Used for data manipulation and analysis.
-NumPy: Used for mathematical operations and array manipulation.
-Scikit-learn: Used for linear regression model and mean square error and r-squared calculation.
-SciPy: Used for statistical functions, including boxcox transformation.

## Problem Definition

The problem addressed in the notebook is to perform a linear regression analysis on an insurance dataset. The goal is to build a model to predict insurance charges based on various independent variables such as age, sex, BMI, number of children, smoker status, and region.

## The notebook follows these steps:

Importing the necessary libraries.
Reading the insurance dataset and exploring its information.
Preprocessing the data by converting categorical variables into numeric using dummy variables and normalizing the charges using the boxcox transformation.
Splitting the data into training and testing sets.
Implementing linear regression using the normal equation method.
Implementing linear regression using the Scikit-learn.
Comparing the results obtained from Scikit-learn's linear regression model and the Python implementation from scratch.

## Comparison of Results
the results are almost the same with an unnoticeable slight difference that is shown only by the value of r squared and is not noticed in the plotting
