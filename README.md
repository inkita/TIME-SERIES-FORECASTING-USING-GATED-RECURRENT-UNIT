# TIME-SERIES-FORECASTING-USING-GATED-RECURRENT-UNIT


For time series forecasting of traffic flows using the given dataset, there are several established models to consider
like Autoregressive Integrated Moving Average (ARIMA), Long Short-Term Memory (LSTM), Gated Recurrent Unit
(GRU), Temporal Convolutional Networks (TCNs), Transformers and others.
Given the high frequency nature of the data (traffic flow per hour for a year), it was essential to choose a model that
would look back at long term trends and give a prediction. Among the popular choices for this requirement are LSTM
and GRU. After weighing their trade-offs and experimenting with both on the training data, GRU demonstrated better
performance, achieving a lower Mean Squared Error (MSE) on the validation data, despite comparable loss values on
the training data for both models.
