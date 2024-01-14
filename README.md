*Data is partitioned into 75% training and 25% validation sets.
*The target variable is identified as "MEDV," and features are selected.
*Features are stored in X, and the target variable is stored in y.
*A linear regression model is built using the scikit-learn library.
*Feature weights (coefficients) are obtained for the linear regression model.

Linear Regression with Two Predictors (Model 1):
Only two input variables, "Age" and "RM," are considered.
Another linear regression model (Model 1) is built using these two predictors.
The model summary, including R-squared, coefficients, and intercept, is presented.

Model 1 Performance Evaluation:
The performance of Model 1 is evaluated on the validation set using RMSE (Root Mean Squared Error) and MAE (Mean Absolute Error).

Linear Regression with All Predictors (Model 2):
All available features (after removing linearly dependent variables) are considered.
Another linear regression model (Model 2) is built using all predictors.
The model summary is presented.
