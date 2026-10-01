# Stock Price Prediction

A time-series forecasting project focused on predicting stock prices using statistical and deep learning models.

## Overview

This project explores traditional time-series models and a hybrid deep learning approach for stock price forecasting using historical **NIFTY 50 market data**.

## Models & Techniques

- Developed **SARIMAX** and **LSTM** models for stock price forecasting.
- Applied **PDFs, PMFs, hypothesis testing, CLRM, and OLS regression** with residual diagnostics.
- Implemented **AR, MA, and ARMA** models with order selection using:
  - ACF/PACF
  - AIC/BIC
  - Ljung-Box diagnostics
- Built a **hybrid ARIMA-LSTM model** using LSTM on ARIMA residuals to capture linear and non-linear dependencies.
- Evaluated forecasting performance using **MAPE** and **RMSE**.
- Used **walk-forward cross-validation** for model validation.

## Results

- Achieved **2.16% MAPE**.
- Achieved **37.42 RMSE** on Reliance stock.
- Validated the forecasting approach using **walk-forward cross-validation**.
