# Stock Market Analysis & Prediction Using LSTM

A Python-based deep learning project that performs stock market analysis and forecasts future stock closing prices using Long Short-Term Memory (LSTM) networks. The project includes data collection, exploratory data analysis, feature engineering, preprocessing, and time-series forecasting.

## Overview

This project uses historical stock market data to build an end-to-end time-series forecasting pipeline. It covers data acquisition, preprocessing, exploratory data analysis (EDA), feature engineering, sequence generation, and LSTM-based prediction of stock closing prices. The project demonstrates how deep learning models can capture temporal dependencies in financial time-series data.

---

## Features

- Downloaded and preprocessed historical stock market data using `yfinance` 
- Performed Exploratory Data Analysis (EDA) on multiple technology stocks
- Visualized stock prices, trading volume, moving averages, and daily returns
- Generated correlation heatmaps and comparative stock performance analysis
- Normalized sequential data using `MinMaxScaler`
- Designed a 60-day sliding window for time-series forecasting
- Built and trained an LSTM neural network using `TensorFlow/Keras`
- Compared predicted stock prices with actual market prices through visualization

---

##  Tech Stack

### Programming Language

- `Python`

### Libraries

#### Data Processing

- `Pandas`
- `NumPy`
- `yfinance`
- `pandas-datareader`

#### Machine Learning

- `TensorFlow`
- `Keras`
- `Scikit-learn`

#### Visualization

- `Matplotlib`
- `Seaborn`


## Workflow

1. Download historical stock market data
2. Perform data preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature scaling using MinMaxScaler
5. Generate time-series sequences
6. Train the LSTM model
7. Predict future stock prices
8. Compare predicted and actual prices




