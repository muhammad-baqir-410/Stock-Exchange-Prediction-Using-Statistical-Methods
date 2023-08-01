# Stock-Exchange-Prediction-Using-Statistical-Methods

This project aims to predict the closing values of the 100-index of a stock exchange on a given day. The data spans from December 31, 2009, to November 15, 2017, and we employ various statistical methods to forecast the Close values.

## Objectives

The main objective of this project is to explore different statistical forecasting techniques and compare their performance in predicting the closing values of the stock exchange. We focus on the following methods:

1. Moving Averages (Simple Moving Averages): We utilize the moving average approach to generate predictions.

2. EWMA (Exponentially Weighted Moving Average): We leverage the exponentially weighted moving average method to forecast the Close values.

3. Auto Regression: Auto Regression (AR) models are used to predict future values based on their past values.

4. ARIMA (AutoRegressive Integrated Moving Average): The ARIMA model combines autoregression, differencing, and moving average components to forecast time series data.

5. ARIMAX (ARIMA with Exogenous Variables): We extend the ARIMA model by incorporating exogenous variables to enhance predictions.

6. SARIMAX (Seasonal ARIMA with Exogenous Variables): The SARIMAX model accounts for seasonal patterns along with exogenous variables for more accurate forecasts.

## Dataset
The dataset contains historical data from five different stock exchanges, covering the period from December 31, 2009, to November 15, 2017. It includes the Close column, which represents the closing value of the 100-index on each trading day.

## Requirements

To run this notebook and reproduce the results, you need the following libraries:

1. numpy
2. pandas
3. statsmodels
5. matplotlib
