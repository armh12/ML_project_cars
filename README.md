Project created in educational purposes.
Problems.
Problem 1. Use “Auto” dataset.
with this command: !curl -O https://raw.githubusercontent.com/JWarmenhoven/ISLR-python/master/Notebooks/Data/Auto.csv

a) Perform a simple linear regression with “mpg” as the response and “horsepower” as the predictor. Print and explain the output: I. Is there a relationship between the predictor and the response? II. How strong is the relationship between the predictor and the response? III.What is the predicted “mpg” associated with a “horsepower” of 98? IV.What are the associated 95% confidence and prediction intervals? b) Plot the response and the predictor c) Produce diagnostic plots. Comment on any problems you see with the fit. d) Do the residual plots suggest any unusually large outliers? Does the leverage plot identify any observations with unusually high leverage?

Problem 2. Use “Carseats” dataset
with this command: !curl -O https://raw.githubusercontent.com/JWarmenhoven/ISLR-python/master/Notebooks/Data/Carseats.csv

a) Fit a multiple regression model to predict “Sales” using “Price”, “Urban”, and “US”. b) For which of the predictors can you reject the null hypothesis? c) On the basis of your response to the previous question, fit a smaller model that only uses the predictors for which there is evidence of association with the outcome. d) How well do the models in a) and c) fit the data? e) Using the model from c), obtain 95% confidence intervals for the coefficient(s). f) Produce diagnostic plots of the linear regression fit. Comment on any problems you see with the fit. g) Do you see any outliers or leverage points?

Problem 3. Use “Auto” dataset
with this command: !curl -O https://raw.githubusercontent.com/JWarmenhoven/ISLR-python/master/Notebooks/Data/Auto.csv

a) Produce a scatterplot matrix which includes all of the variables in the data set. b) Compute the matrix of correlations between the variables. You will need to exclude the “name” variable, which is qualitative.

c) Perform a multiple linear regression with “mpg” as the response and all other variables except “name” as the predictors. Comment on the output: I. Is there a relationship between the predictors and the response? II. Which predictors appear to have a statistically significant relationship to the response? III.What does the coefficient for the “year” variable suggest? d) Produce diagnostic plots of the linear regression fit. Comment on any problems you see with the fit. e) Do you see any outlier or leverage points? f) Try a few different transformations of the variables, such as log(X), √X, X^2. Comment on your findings.
