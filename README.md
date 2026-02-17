# Sales-Forecasting
# Project Overview

This project focuses on forecasting next quarter’s monthly sales using time series analysis techniques in Python. The objective was to build a reliable forecasting model that captures trend and seasonality in historical sales data and provides accurate short-term predictions with confidence intervals.

# Objectives

Load and preprocess monthly sales data

Perform Exploratory Data Analysis (EDA)

Test for stationarity using the Augmented Dickey-Fuller (ADF) test

Apply first and seasonal differencing

Build a Seasonal ARIMA (SARIMA) model

Generate a 3-month sales forecast

Evaluate model performance using MAE and MAPE

# Tools & Technologies
Python
Pandas
Statsmodels
Matplotlib
Scikit-learn
Google Colab

Exploratory Data Analysis

Visualized monthly sales trends

Identified clear 12-month seasonality

Stationarity Testing

Applied Augmented Dickey-Fuller (ADF) test
Original series was non-stationary
Applied seasonal differencing (lag = 12)
Achieved stationarity after transformation
 Model Used

SARIMA (1,1,1)(1,1,1,12)

This model captures:

Trend component

Seasonal component (12-month cycle)

📈 Model Evaluation

Mean Absolute Error (MAE): 410

Mean Absolute Percentage Error (MAPE): 9.25%

A MAPE below 10% indicates excellent forecasting accuracy.

Resource allocation

Business decision-making
