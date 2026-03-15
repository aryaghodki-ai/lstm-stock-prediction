# LSTM-Based Stock Price Prediction

A deep learning project built during WiDS 5.0 at IIT Bombay.

## Overview
Predicts Apple Inc. stock prices using stacked LSTM networks trained 
on 10 years of historical data (2015–2024).

## Motivation

Financial markets generate large amounts of sequential data. 
Traditional models struggle to capture long-term dependencies in such time series. 
This project explores the use of Long Short-Term Memory (LSTM) networks to model historical stock price patterns and generate predictions.

## Tech Stack
- Python, TensorFlow/Keras, NumPy, Pandas, Matplotlib

## Key Concepts
- Time-series preprocessing & sliding window sequence generation
- LSTM architecture with Dropout regularization
- Adam optimizer with MSE loss
- Train-test split and validation monitoring
  
## Results

The trained LSTM model is able to capture the general trend of Apple stock prices.

• Training data predictions closely match historical price movement.  
• Test predictions follow the overall direction of the market but show small deviations during periods of high volatility.  
• The model demonstrates how recurrent neural networks can learn temporal dependencies in financial time-series data.

## How to Run
1. Clone the repo
2. Install dependencies: `pip install tensorflow numpy pandas matplotlib`
3. Run `LSTM_stock_prediction.py` or open the Jupyter notebook

This project was developed as part of the WiDS 5.0 program at IIT Bombay.
