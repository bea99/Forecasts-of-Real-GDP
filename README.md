# Forecasts-of-Real-GDP
Time series and forecasting project - Forecasts of Real GDP


We constructed 1-quarter-ahead forecasts of Real GDP (log-level): yt = log(GDP C1t) where
GDP C1 is the code of the series in the dataset.
All models are estimated using a rolling window of 100 observations. The first forecast origin
is R = 1985 : Q2, and the last forecast origin is T = 2018 : Q3, for a total of P = 134 forecasts. At
each forecast origin, you will estimate models and save the forecasts from the models, as detailed
below.
Forecast evaluation is carried out comparing forecasts for the level with Real GDP GDP C1t and
computing the root mean squared error, RMSE.
