


# Stock Prediction Model using LSTM

## Introduction

This repository contains the code and resources for a stock prediction model developed as part of an internship task for CodeAlpha. The model predicts stock prices for the next 30 days using Long Short-Term Memory (LSTM) networks. The dataset used for this project consists of Google share prices sourced from Kaggle.

## Dataset

The dataset used in this project contains historical stock prices of Google. The data includes features such as date, opening price, closing price, highest and lowest prices, and volume. The dataset was downloaded from Kaggle and preprocessed before being used in the LSTM model.

## Model

The model is built using LSTM, a type of recurrent neural network (RNN) that is well-suited for time-series prediction tasks. The model architecture includes the following key components:
- Input Layer: Accepts the preprocessed stock price data.
- LSTM Layers: Capture the temporal dependencies in the stock price data.
- Dense Layer: Produces the final output, which is the predicted stock price for the next day.
- Activation Function: Used to apply non-linearity to the model output.

The model was trained on the historical stock price data to learn patterns and make accurate future predictions.

## Results

The output of the model provides predictions for the next 30 days of Google's stock prices. The predictions are based on the patterns and trends learned from the historical data. The results indicate the model's capability to capture the stock price dynamics and provide meaningful forecasts.



## Conclusion

This project demonstrates the application of LSTM networks for stock price prediction. The model successfully predicts stock prices for the next 30 days, providing valuable insights for financial analysis and decision-making. Feel free to explore the code and experiment with different datasets and model configurations.



---

