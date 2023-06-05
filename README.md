# Stock-Price-Prediction
Build and train a model to predict the daily adjusted closing prices of Tesla (TSLA), using data from previous days. This experiment will consist of data starting from TSLA's IPO date which is 2013-06-29 to 2023-05-24

# Objective
The objective of this experiment is to build and train a model to predict the daily adjusted closing prices of Tesla (TSLA) 1 year into the future.  This experiment will consist of data starting from TSLA's IPO date which is 2010-06-29 to 2023-05-24. The data is taken from yahoo finance using a python library called yfinance

In this experiment, I aim to utilize XGBoost to accurately forecast TSLA’s performance in one years time. However, since the data from years 2010 - 2019 are so small compared to the recent years’ data, I will perform time series cross validation to train sectioned date ranges in order to achieve a better trained model.

To evaluate the effectiveness of my model, I will use the root mean square error (RMSE) score where the lower the score, the more accurate the prediction.


