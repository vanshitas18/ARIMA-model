# ARIMA Modeling for Stock Data

This project performs ARIMA (AutoRegressive Integrated Moving Average) modeling on stock market data, specifically using the stock prices of Nestle and Britannia over 
the past five years. The goal of ARIMA modeling is to forecast future stock prices based on historical data trends. ARIMA is a widely-used statistical model for time series 
data, especially in financial markets, because it helps in predicting future prices by considering past values, trends, and residuals.

## Why ARIMA Modeling for Stock Data?
Stock prices typically exhibit temporal dependencies, and ARIMA is ideal for capturing these relationships between current and past stock values. We are using ARIMA for 
stock price forecasting to predict future movements in stock prices and to understand long-term trends. ARIMA modeling is effective because it can accommodate both trend 
and seasonality in time series data, which are common in stock markets. It is also versatile in handling non-stationary data by applying differencing.

## Prerequisites for ARIMA Modeling
Before performing ARIMA modeling, it is crucial to check whether the time series data is stationary, as ARIMA assumes stationarity in the data. To ensure this, we perform 
an Augmented Dickey-Fuller (ADF) test, which tests for the presence of a unit root in the data. If the time series is non-stationary, differencing is applied to make the 
data stationary before fitting the ARIMA model.

## Modeling in RStudio
The ARIMA modeling is performed in RStudio, and it is recommended to use an RSweave (.Rnw) file for this project. RSweave allows for seamless integration of R code and 
LaTeX, making it easy to generate a PDF document where both the code and its output (plots, tables, etc.) are displayed together. This approach helps in creating a 
well-documented report where the steps, results, and visualizations are in one cohesive document.
