
# SP Challenge

## Problem Statement:
forecasting the 3 years a head of future sales based on SuperStore Dataset 
to help the business planning and support future decision for budgetting and operations and deliveries pro-actively and within time .
## Technical Report:
in this project I tried to gain more information and exploring it using Visualizing techniuqe matplotlib and seaborn and pandas 
and take a look for the statistical properties for it .

## Model Selection:
# Fbprophet : 
Prophet is a procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects. It works best with time series that have strong seasonal effects and several seasons of historical data.
https://facebook.github.io/prophet/
unfortunately it did'nt work so well for this dataset because
it didn't show any stationarity yet.

# SARIMA :
AR: Autoregression. A model that uses the dependent relationship between an observation and some number of lagged observations.
I: Integrated. The use of differencing of raw observations in order to make the time series stationary.
MA: Moving Average. A model that uses the dependency between an observation and a residual error from a moving average model applied to lagged observations.
https://becominghuman.ai/what-is-arima-and-sarima-model-10972b5e13c0]


# Result :
You Can reuse the notebook to see the result here :
https://colab.research.google.com/drive/1wBFXYjamPBroS_KBBITg_p0yCXfjO9EL?usp=sharing

I concluded that SARIMA Model with it's ability of differenceing show an. acceptable score with mse: 5911.2612 as shown in the notebook 

# Refrencnce:
https://becominghuman.ai/what-is-arima-and-sarima-model-10972b5e13c0]
https://facebook.github.io/prophet/
https://www.digitalocean.com/community/tutorials/a-guide-to-time-series-forecasting-with-arima-in-python-3

