Time Series Forecasting Using SARIMA Model


This project focuses on predicting future stock prices using the SARIMA (Seasonal Autoregressive Integrated Moving Average) model. The dataset used includes Apple's daily stock price from January 2012 to December 2019. The goal is to preprocess the data, identify stationarity, tune SARIMA hyperparameters, and evaluate performance using statistical metrics.

Project Overview


Time series forecasting is a powerful technique to predict future values based on historical data. In this project:

Daily Apple stock price data was collected and analyzed.
Preprocessing and feature engineering were performed in Python.
Stationarity tests like the Augmented Dickey-Fuller (ADF) Test were applied to ensure data readiness for modeling.
The SARIMA model was fine-tuned using Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) plots.
Model performance was evaluated using:
Symmetric Mean Absolute Percentage Error (SMAPE)
Mean Absolute Error (MAE)


Features


Data Preprocessing: Cleaning, visualizing, and testing for stationarity.
SARIMA Modeling: Seasonal and trend-based predictions using statistical methods.
Performance Metrics: SMAPE and MAE are used to evaluate the model.
Hyperparameter Tuning: Parameters selected based on ACF and PACF plots.


Data

The dataset contains daily stock price data for Apple Inc. from January 2012 to December 2019. The key features are:

Date: Daily date range
Close: Adjusted closing price
Data Source: Publicly available historical stock data (Yahoo Finance).

Methodology

Data Preprocessing:

Removed missing values.
Visualized the data to identify trends and seasonality.
Applied the Augmented Dickey-Fuller (ADF) Test to test for stationarity.

Hyperparameter Tuning:

ACF and PACF Plots were analyzed to determine AR, I, and MA parameters.
The SARIMA model was configured to capture both trend and seasonality.
Model Training and Forecasting:

Trained SARIMA on historical data.
Forecasted future stock prices and compared them with the test set.

Model Evaluation:

SMAPE: 11.04
MAE: 17.04

Results

Model Performance
Metric	Value

Symmetric Mean Absolute Percentage Error (SMAPE)	11.04%
Mean Absolute Error (MAE)	17.04

Visualizations


ACF and PACF Plots: Used to identify SARIMA parameters.

Forecasted vs Actual Stock Prices:


The SARIMA model successfully captures trends and seasonality.

