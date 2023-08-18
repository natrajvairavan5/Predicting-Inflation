# Predicting-Inflation

Comparing ARIMA and VAR on how accurately they can forecast future inflation rates using previous inflation data
and other macroeconomic indicators. Note that each model was fitted using a fixed training and testing dataset -- the goal is to
find the model with the best long-term accuracy, as opposed to building models that produce rolling forecasts.

The Linear Regression section was included to show relationships within the data. Also, given that linear regression is the main algorithm used to estimate parameter values for prominent time series models such as ARIMA, I wanted to see how it produces forecasts with other datasets. That being said, linear regression shouldn't be used to make forecasts that can be taken seriously as the i.i.d. assumption for this model is violated with time series data.
