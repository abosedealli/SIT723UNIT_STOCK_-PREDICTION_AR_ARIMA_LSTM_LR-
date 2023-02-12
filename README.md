STOCK_-PREDICTION_AR_ARIMA_LSTM_LR-

Data is Netflix and Apple Inc
Duration Apple 1/1/1980 - 19/1/2023
Netflix is 1/1/2020-   30/12/2022 and 1/7/2033-30/12/2022

Testing models are Autoregression, ARIMA( Autoregressive integrated Moving average
                                  Linear regression and LSTM Long short term Memory.
Train :Test rate is 80:20 
p va;ues were higher than 0.05. Models were fitted.
Prediction error metrics: RMSE, MSE, MAE and MAPE
For error, the lower, the better.

The summary is that LSTM did not perform excellently well with reduction in data length. 
Large data trains well
Sequence =50


For a prediction of six months, the result of LSTM depreciates further which makes the summary that LSTM need more data length to train Apple data size was over 10375. 

For Linear regression, large data are also great.

For AR and ARIMA, AR and ARIMA models however had better results with lesser data length. The lesser results were observed for six month dataset for ARIMA.
In all, LSTM seems to be the best hoewver we suggest a further research with the use of hybrid model ans a sentiment analysis alongside Data is suggested.
