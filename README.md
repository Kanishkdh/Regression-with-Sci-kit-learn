# Regression with Sckit-learn
Detailed comparison of performance of Linear regression and Polynomial regression.

Linear regression
Linear regression is a basic and commonly used type of predictive analysis.  The overall idea of regression is to examine two things: (1) does a set of predictor variables do a good job in predicting an outcome (dependent) variable?  (2) Which variables in particular are significant predictors of the outcome variable, and in what way do they–indicated by the magnitude and sign of the beta estimates–impact the outcome variable?  These regression estimates are used to explain the relationship between one dependent variable and one or more independent variables. 


Polynomial Regression
Polynomial regression is a form of linear regression in which the relationship between the independent variable x and the dependent variable y is modeled as an nth order polynomial. Polynomial regression fits a nonlinear relationship between the value of x and the corresponding conditional mean of y, denoted E(y | x), and has been used to describe nonlinear phenomena.
Overfitting and Underfitting
Error metrics:
Metrics


The three most common evaluation metrics for regression problems:

**Mean Absolute Error** (MAE) is the mean of the absolute value of the errors:

**Mean Squared Error** (MSE) is the mean of the squared errors:

**Root Mean Squared Error** (RMSE) is the square root of the mean of the squared errors:

Comparing these metrics:

MAE** is the easiest to understand, because it's the average error.
MSE** is more popular than MAE, because MSE "punishes" larger errors, which tends to be useful in the real world.
RMSE** is even more popular than MSE, because RMSE is interpretable in the "y" units.

All of these are **loss functions**, because we want to minimize them.


Regularization:
Regularization is a way to reduce model overfitting and variance.
Three main types of regularization: 

- L1 Regularization(Lasso regression)
- L2 Regularization(Ridge Regression)
- Combining L1 & l2(Elastic Net)
