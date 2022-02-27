# Time-Series-on-Restaurant-Visitors

## 1. INTRODUCTION

There is a steady increase of restaurants in the 21st century and running a local restaurant is not an easy job.
The number of visitors to a restaurant for a period of
time is random. The advent of many a restaurants in a
region marks the chance of the existing restaurants to lose
scope. There is a predicament with expectation of visitors to a restaurant. It seems to be inconvenient for the
successful run of the eatery in a locality thus, disturbing
the economic attributes of the functioning market. Forecasting plays a major role with planning the total number
of visitors using the time series data. The reservation of
visitors are also a part of the prediction perspective. The
challenges include in building a technically efficient model
to forecast and this paper explores the appliance of time
series forecasting model Autoregressive Integrated Moving Average (ARIMA). The ARIMA approach planned by
Box and Jenkins is popular as it yields most accurate forecasting results. A study of time series data of visitors to
restaurants in Japan over a period of 2016–2017 to create
models.

## 2. PURPOSE OF TIME SERIES IN PROCESSING

A time series is a structured dataset that can be annual,
monthly, or in this case daily. The visit data and reserve
data used here are time series data. Even date is analyzed for better results. Descriptive model is applied for
making predictions. The visit data specifies the time of
reservation and reserve data specifies the time when the
reservation was made. This model helps in describing the
trends, patterns and it uses the information in time series
to forecast future values of that series. Making prediction about future is called as extrapolation. Forecasting
involves taking models that fit on historical data and use
them to predict future. The purpose of time series analysis
are to understand or model the stochastic mechanism that
gives rise to an observed series and to predict or forecast
the future values of a series based on the history of that
series. Time series include four parts level, trend, seasonality and noise. Level is undesirable because it forms the
baseline values and the baseline values are the
data of date and time. The next important feature is seasonal variation, where seasons in Japan play a vital role.
These are the parameters of time series considered in this
paper.

## 3. FORECASTING OF VISITORS USING ARIMA

The main technique being explored is ARIMA which is a
forecasting technique that projects the future values of a
series based entirely on its own inertia. Its main application
is in the area of short term forecasting requiring at least
40 historical data points. The auto regressive part of the
model determines the dependence on previous time points.
The data is split into training set and testing set. The training period was different to testing period as there are different cuisine restaurants in this case. So, the train period
is shortened and the test period too. Here period is weekly
cycle and the visitors per cuisine and per restaurant is valuated. These data are taken for training to the ARIMA
model. As ARIMA model uses p d q the series should
be made stationary and choosing of order models with
ACF and PACF for fitting the ARIMA to the state of train
is fixed.

## 4. PERFORMANCE MEASURES USING RMSE AND MAPE

The prediction of visitor arrivals during testing is done
and the measures of accuracy were calculated. Root mean
square error and Mean absolute percentage error were used
for forecasting error in time period and to measure accuracy of continuous variables. The average y value with
given x value is predicted using regression. They can be
positive or negative as the predicted value under or over
estimates the actual value. Squaring the residuals, averaging the squares, and taking the square root gives the r.m.s
error. Then use the r.m.s. error of the y values as a measure of the spread about the predicted y value. It’s the
square root of the average of squared differences between
prediction and actual observation.

MAPE measures the average magnitude errors in a set of
predictions without directions. It is the average over the
test sample of absolute difference between predictions and
actual observations.

Both are used to express average and RMSE have interesting implication for large errors. RMSE is more useful
than MAPE because it is steady and RMSE does not necessarily increase with the variance of the errors. RMSE
increases with the variance of the frequency distribution
of error magnitudes. Hence RMSE is better.

## 5. CONCLUSION

This explores a growing trend in the future of restaurants by forecasting the number of visitors each day. In this
study the time series forecasting model ARIMA is functional. Based on the above an efficient prediction of visitors to come in future was analyzed for the profits of the
restaurant. This prediction results in easy scheduling of
ingredients and staffs for enhanced experience of visitors.
Even offers can be offered during bad weather conditions
for the successful running of the restaurants. The results of
the study is revealed using metrics like RMSE and MAPE,
where RMSE gives better accuracy in predicting the visitors. The information thus obtained from forecasting the
visitors will act as an aid of support to the restaurants in
focusing with the development of creating an enjoyable
dining experience for the visitors. As far as the experimental results, the system thus proposed works well in
forecasting visitors and is robust too.

## 6. Cited: Article  in  Journal of Computational and Theoretical Nanoscience · May 2018
