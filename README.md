# Stock Price Prediction with S&P 500 Data

This project involves predicting the daily movements of the S&P 500 index using historical stock data from Yahoo Finance. The task is to predict whether the stock price will go up or down the following day based on the closing price.

## Project Overview

The goal of this project is to use machine learning techniques to predict whether the closing price of the S&P 500 index will increase or decrease the next day. The project utilizes historical stock data from Yahoo Finance and employs a binary classification approach where the target variable is 1 (price up) or 0 (price down).

## Data

The data is sourced from Yahoo Finance using the `yfinance` library. We collect historical stock data for the S&P 500 index (represented by the ticker symbol `^GSPC`) starting from January 1990 to the present.

The dataset includes the following columns:

- **Open**: Opening price of the stock
- **High**: Highest price during the trading day
- **Low**: Lowest price during the trading day
- **Close**: Closing price of the stock
- **Volume**: Number of shares traded
- **Tomorrow**: The closing price of the next day
- **Target**: 1 if the price will increase tomorrow, 0 if the price will decrease

## Installation

To run this project, ensure that you have Python 3.x installed. You will need the following libraries:

- `yfinance`
- `pandas`
- `numpy`
- `matplotlib`

Install the required libraries using the following:

```bash
pip install yfinance pandas numpy matplotlib
