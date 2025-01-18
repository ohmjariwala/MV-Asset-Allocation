# Asset Allocation Framework with LSTM-Based Forecasting

## Overview
This repository contains a Jupyter Notebook that demonstrates a quantitative framework for optimizing asset allocation across a portfolio. It incorporates an **LSTM (Long Short-Term Memory) neural network** to forecast asset returns and uses these predictions to inform portfolio optimization strategies.

## Features
- **LSTM-Based Return Forecasting**:
  - Utilizes historical time-series data to predict future asset returns.
  - Employs LSTM to capture dependencies and forecast trends/returns in financial data.
  - Hyperparameter tuning to improve model accuracy.
  
- **Portfolio Optimization**:
  - Combines LSTM forecasts with Markowitz mean-variance optimization.
  - Considers risk-return trade-offs to construct efficient portfolios.
  - Implements constraints like sector caps or minimum allocations.

- **Data Visualization**:
  - Plots historical data and forecasted returns.
  - Visualizes the efficient frontier and portfolio weights.

## Requirements
- Libraries:
  - `NumPy`, `pandas`: Data processing and manipulation.
  - `matplotlib`: Data visualization.
  - `TensorFlow` or `PyTorch`: LSTM model implementation.
  - `sklearn`: Data preprocessing and evaluation metrics.
  - FRED API Key needed (https://fred.stlouisfed.org/docs/api/api_key.html)

