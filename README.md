# Stock-Market-Price-Prediction
Stock Market Price Prediction project

Stock market prediction is a complex problem and one that is a common area of research
for machine learning. For comparison of Machine Learning methods in this area this pa-
per compares the performance of Support Vector Regression, Multi-Layer Perceptron, one
dimensional Convolutional Neural Network, Long Short Term Memory Neural Network
(LSTM) and Bi-directional LSTM. The data selected are stock price and volum data for
nine stocks from the S&P 500, the data was normalized for each stock and MACD, RSI and
EMA were calculated. After hyperparameter tuning the models were compared in terms of
test MSE and MAPE. We found that the Bi-Directional LSTM consistently outperforms
the other methods presented on the test set. Since the complexity of this network was not
high it could also be used with additional data outside price and volume related measures
in the future as a possible tool for short term trading.
