# Website-Traffic-Forecasting
ABOUT
Website Traffic Forecasting means forecasting traffic on a website during a particular
period. It is one of the best use cases of Time Series Forecasting. The dataset I am using for Website Traffic Forecasting is
collected from the daily traffic data of thecleverprogrammer.com. It contains data about
daily traffic data from June 2021 to June 2022.

# ML MODEL ARIMA
ARIMA stands for autoregressive integrated moving average model and is specified by
three order parameters: (p, d, q).
• AR(p) Autoregression – a regression model that utilizes the dependent
relationship between a current observation and observations over a previous
period. An auto regressive (AR(p)) component refers to the use of past values in
the regression equation for the time series.
• I(d) Integration – uses differencing of observations (subtracting an observation
from observation at the previous time step) in order to make the time series
stationary. Differencing involves the subtraction of the current values of a series
with its previous values d number of times.
• MA(q) Moving Average – a model that uses the dependency between an
observation and a residual error from a moving average model applied to lagged
observations. A moving average component depicts the error of the model as a
combination of previous error terms. The order q represents the number of terms
to be included in the model.

# Types of ARIMA Model
• ARIMA: Non-seasonal Autoregressive Integrated Moving Averages
• SARIMA: Seasonal ARIMA (I'll be using this in the project)
• SARIMAX: Seasonal ARIMA with exogenous variable

# CHALLENGES

The original data needed some clean up and some feature engineering as well.
Deciding which method to use for solving this problem was a difficult and critical one
because there are many techniques available which are popular for e.g. ARIMA,
SARIMA, XGBoost, LightGBM, LSTM and libraries such as Facebook’s prophet. In
the end, it was a good decision to go with ARIMA as it provides a good groundwork
for understanding other time series analysis techniques and is easier to implement than
some other techniques.
The other challenge was to be able to visualize these results in concise manner to get a
good overview how the models are performing. The plots for actual predictions and
the errors painted a good picture of how the models perform. 
