# Stock Price Prediction with LSTM

## Overview
This project uses a Long Short-Term Memory (LSTM) neural network to predict stock prices. It collects historical data from Yahoo Finance for four tech companies (Apple, Google, Microsoft, Amazon), preprocesses the data, trains the LSTM model, and makes predictions. The predicted prices are then compared with the actual prices to evaluate the model's performance.

## Requirements
- pandas
- numpy
- matplotlib
- seaborn
- yfinance
- pandas_datareader
- scikit-learn
- keras

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/stock-price-prediction.git
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt

## Usage
1. Import the necessary libraries.
2. Request stock prices in real-time for the desired companies using historical data from Yahoo Finance.
3. Plot the closing and sales volume of the stocks.
4. Get the data from Yahoo within specified dates.
5. Call the scaler and scale the data.
6. Create the training data and reshape it.
7. Define and compile the LSTM model.
8. Train the model.
9. Prepare the test data and make predictions.
10. Evaluate the model.
11. Plot the predictions.

## Acknowledgements
- Yahoo Finance for providing the historical stock price data.
- scikit-learn for providing the MinMaxScaler for data normalization.
- Keras for providing the LSTM model implementation.
