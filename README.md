# fintech-time-series-homework

This repository contains the Jupyter notebook, accompanied with the time series tools and library code as part of the Fintech homework assignment Unit 10— A Yen for the Future.

In this homework, we have performed time series analysis in the value of the Japanese yen versus the U.S. dollar. This analysis should help us in understanding the future direction and risk of currency.


## Files

### [Time Series Analysis](time_series_analysis.ipynb)

In this Jupyter notebook we,

- determined predictable behavior of Dollar-Yen exchange rate by applying time series analysis and modelling.

- decomposed price data by using Hodrick-Prescott Filter. This separates the trend and non-trend components.

- created ARMA and ARIMA models to forecast Returns and Settle price.

- created GARCH model to forecast the volatility of the exchange rates.

### [Linear Regression Analysis](regression_analyis.ipynb)

In this Jupyter notebook we created a linear regression model to predict current return price with the lagged return price.

The steps involved in performing the analyis using the linear regression model include, 

- splitting the data into training and testing data set so that it becomes easy to fit the data into that model.

- fitting the training data into Linear Regression model and make some prediction by using testing data(the data that has never seen before).

- comparing Out-of-sample (testing data) performance with In-sample (training data) performance to find out the model performance.