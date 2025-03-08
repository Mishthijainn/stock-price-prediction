# Stock Price Predictor App

This is a web-based stock price prediction app built using **Streamlit**, **Keras**, **Yahoo Finance (yfinance)**, **scikit-learn**, and **Matplotlib**. It fetches the stock data of a specified company, performs technical analysis (like moving averages), and uses a pre-trained machine learning model to predict future stock prices.

## Features

- **Stock Data Fetching**: Fetch historical stock data from Yahoo Finance.
- **Technical Analysis**: Plot various moving averages (100-day, 200-day, 250-day) along with the stock's closing price.
- **Stock Price Prediction**: Using a pre-trained Keras model to predict future stock prices.
- **Visualizations**: Interactive graphs to visualize the stock's historical data, moving averages, and predicted vs. actual prices.
- **Streamlit Interface**: A user-friendly interface built with **Streamlit** for easy interaction with the app.

## Prerequisites

Make sure to have the following libraries installed:

- `yfinance`: To fetch stock data.
- `streamlit`: For creating the web interface and running the app.
- `pandas`: For data manipulation.
- `numpy`: For numerical operations.
- `keras`: For the pre-trained stock price prediction model.
- `matplotlib`: For plotting graphs.
- `scikit-learn`: For data preprocessing.

You can install these dependencies by running:

```bash
pip install yfinance streamlit pandas numpy keras matplotlib scikit-learn
