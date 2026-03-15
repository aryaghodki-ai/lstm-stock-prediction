# LSTM-Based Stock Price Prediction

A deep learning project built during WiDS 5.0 at IIT Bombay.

## Overview
Predicts Apple Inc. stock prices using stacked LSTM networks trained 
on 10 years of historical data (2015–2024).

## Tech Stack
- Python, TensorFlow/Keras, NumPy, Pandas, Matplotlib

## Key Concepts
- Time-series preprocessing & sliding window sequence generation
- LSTM architecture with Dropout regularization
- Adam optimizer with MSE loss
- Train-test split and validation monitoring

## Results
Training predictions closely follow actual price trends.
Test predictions capture overall market movement with minor 
deviations during high-volatility periods.

## How to Run
1. Clone the repo
2. Install dependencies: `pip install tensorflow numpy pandas matplotlib`
3. Run `lstm_stock.py` or open the Jupyter notebook
