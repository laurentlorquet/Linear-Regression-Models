# Linear-Regression-Models
Linear Regressions, Multicollinearity, Multiple Linear Regression,

## 1. Setup
Task: Select a .csv dataset with at least 5 predictors.
Describe the dataset briefly
Load the dataset into a pandas Dataframe and display the first 5 rows.
Use .info() method to gather information about the predictors.
Manually construct an evaluation set of 5 datapoints with at least 3 predictors by defining a dictionary 
with random predictor data. This will later be utilized to assess models and perform predictions.

## 2. Simple Linear Regression
Task: Predict a continuous target variable using one predictor.
Select a numerical column as your target (Y).
Choose one predictor (X).
Visualize the relationship with a scatter plot.
Use the statsmodels.api library to fit a linear regression model and then print the model's summary (model.summary()).
Analyze the model summary, commenting on the coefficients and R^2.
Use the coefficients to write the equation for the model.
Predict the target value for the evaluation set and overlay these on the scatter plot with a different color or marker.
Add the regression line to the scatter plot.

## 3. Multicollinearity
Task: Understand multicollinearity among predictors.
Choose 4 or 5 predictors and create a subset of your dataset.
Visualize the relationships using a scatter plot matrix.
Based on visual inspection, note any predictors that appear to be correlated.
Calculate the VIF (Variance Inflation Factor) for these predictors. (check class examples).
Discuss which predictors show high multicollinearity based on the VIF values.

## 4. Multiple Linear Regression
Task: Expand your model to use multiple predictors.
Choose at least additional 3 predictors which seem relevant to the target.
Fit a linear model with the new predictors using statsmodels.api.
Print the model summary and analyze it. Compare the R^2 value with the simple linear regression.
Use the coefficients to write the equation for the model.
Predict the target values for the evaluation set based on this new model
