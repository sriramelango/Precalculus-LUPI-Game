# Precalculus-LUPI-Game
**CHS Precalculus Period 8 Lowest Unique Possible Integer (LUPI) Game Analysis and Results**

**Summary:**

Within this repository, you will find the results of playing the Lowest Unique Positive Integer Game (LUPI) over the course of time, and the corresponding time series analysis, figures, and the building of an ARIMA model (autoregressive integrated moving average) for the purposes of predicting/forecasting future trends and values.

**Time Series Analysis Conclusions:**

Based upon the existing data, all null hypotheses can be rejected and we can assume that the series is stationary. This means that the data has statistical properities that do not variy in time. For example, mean, variance, and autocorrelation are all constant over time. This is very beneficial for the purposes of the ARIMA model and machine learning, since a stationary series is way easier to predict and forecast values for. 

**ARIMA ML Model Results**

The ARIMA ML model was successful in training as well as the forecasting of potential future values and trends based on the prior existing data, both in terms of estimating future trends using all of the dataset for training, as well as in a train/test split and predicting existing values in the dataset (test) for cross reference and comparison.
