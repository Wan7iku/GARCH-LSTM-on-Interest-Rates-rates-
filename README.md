# Predicting Interbank-Rates-using LSTM model
Problem statement: Interbank rates are the rates of interest charged on most short-term loans between banks.
Motivation:
Objective: To predict interbank rates using an LSTM model.
Shape of the output affects predicted result. If you use (len(data)) as the number of neurons in the output layer, the model will output wrong results.
After training the model, data is to be  inverse scaled for better prediction.
