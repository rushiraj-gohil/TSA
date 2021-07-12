# TIME SERIES ANALYSIS
### Time Series Analysis is a series that often presents itself in day to day situations and requires forecasting, be it stock prices, weather, etc.
  ##### In this project, we will forecast the "Closing Price " of Tata Power (NSE) stock using various techniques.
  ###### The first step is to acquire the data that we perform using the Yahoo finance library, and then we present the Dickey-Fuller test, which is used to measure the stationarity of any Time Series.
###### After this step, we plot various graphs to ease the analysis using visual representation. Which is followed by multiple plots drawn to represent -
  - Seasonality
  - Trend
  - Correlation
  ###### These plots are followed by sampling the data into two parts the first 80% for training the model and the remaining for testing the model. We perform curve fitting using the ARIMA model based on minimisation of SMAPE(squared mean absolute percentage error).
  ##### To conclude, the predictions are adequately accurate, but as the model is dynamic, its value will vary in different time frames.
