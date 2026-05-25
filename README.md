# BoxJenkins-vs-Exponential-Smoothing-retail-sales-forecasting
## Overview
This project compares different time series forecasting methods for US retail sales in clothing and accessory stores.

The study evaluates:
- Exponential Smoothing (ES)
- Box-Jenkins (ARIMA/BJ)
- Forecast combination approaches

using out-of-sample forecasting and backtesting techniques.

## Dataset
- Monthly US retail sales data
- Clothing and clothing accessory stores
- Sample includes COVID-19 volatility period

## Objective
- Forecast retail sales dynamics
- Compare forecasting accuracy across models
- Evaluate robustness during volatile periods

## Methodology
### Models
- Exponential Smoothing (ES)
- Box-Jenkins (ARIMA)
- Combined forecasts

### Evaluation
- Out-of-sample forecasting
- Backtesting
- Residual diagnostics
- Forecast optimality tests

## Statistical Tests
- Holden-Peel rationality test
- Mincer-Zarnowitz efficiency test
- Pesaran-Timmermann directional test
- Ljung-Box residual autocorrelation test
- Diebold-Mariano comparison test

## Results
The Box-Jenkins model outperformed Exponential Smoothing:
- Lower RMSE
- Lower MAE
- Better directional forecasting ability
- Better residual diagnostics

Combined forecasts suggest a gradual recovery in retail sales with strong seasonal peaks.

## Tools
- Python
- Time Series Forecasting
- Econometrics
- ARIMA / Box-Jenkins
- Forecast Evaluation

## Author
Inès Tapoayi
