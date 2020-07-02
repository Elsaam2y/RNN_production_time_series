# RNN_production_time_series
Python script for forecasting times seires data using LSTM

# Requirements
Familiarity with RNN, tensorflor, pandas and numpy


# Dataset
The dataset used in this model is an industrial production data that keeps monthly tracks of nondurable goods.  
It can be freely downloaded from:
https://fred.stlouisfed.org/series/IPN31152N


# Using the code
This code has been written as a solution for the RNN project in the course entitled: "Complete Tensorflow 2 and Keras Deep Learning Bootcamp."
First the data is loaded and preprocessed to scale it and assign the train and test datasets. Then the LSTM model is created and evaluated with the test data. Then it is used to forecast the new data of the following 18 months.

