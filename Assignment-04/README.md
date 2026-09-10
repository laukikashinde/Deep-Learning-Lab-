# Practical 4: Develop an LSTM-based model for time-series forecasting using stock price, weather, or sales datasets.

## Aim

To develop an LSTM-based model for time-series forecasting using stock price data.

## Description

In this practical, an LSTM neural network was developed to learn temporal patterns from historical stock price data. The closing prices were normalized and converted into sequences using previous time steps. The LSTM model was trained to predict future stock prices and its performance was evaluated using suitable regression metrics.

## Tools and Technologies Used

* Google Colab
* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
* yFinance

## Work Performed

* Collected historical stock price data.
* Selected closing price values for forecasting.
* Normalized the data using Min-Max scaling.
* Created sequences using previous 60 days of data.
* Split the data into training and testing sets.
* Designed and trained an LSTM model.
* Predicted stock prices using the trained model.
* Evaluated performance using RMSE and MAE.
* Compared actual and predicted prices using a graph.

## Result

The LSTM model successfully learned temporal patterns from historical stock data and generated stock price forecasts. Its performance was evaluated using RMSE and MAE.

