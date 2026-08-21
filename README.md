# Stock Prediction

**Repo:** https://github.com/shreyajainnx09/StockPrediction

## Description
A machine learning project aimed at predicting stock prices from historical data, starting with Google's stock price. The current code loads the training dataset and visualizes it as a first step toward building a predictive model.

## Current State
This repo is in an early stage. So far it:
- Loads `Google_Stock_Price_Train.csv` into a pandas DataFrame
- Prints the dataset shape and a preview of the first rows
- Extracts the "Open" price column as the training set
- Plots the historical Google stock price over time with matplotlib

No model has been trained yet in the current code — this is the data-loading and exploration stage.

## Tech Stack
- Python
- NumPy
- Pandas
- Matplotlib

## Requirements
```bash
pip install numpy pandas matplotlib
```

## Getting Started
```bash
git clone https://github.com/shreyajainnx09/StockPrediction.git
cd StockPrediction
```
Make sure `Google_Stock_Price_Train.csv` is in the same directory, then run the script:
```bash
python stock_prediction.py
```

## Data
- `Google_Stock_Price_Train.csv` — historical daily Google stock price data used for training/exploration. (Add this file to the repo if it isn't already tracked.)

## Roadmap Ideas
- Feature scaling/normalization of the price data
- Building an actual predictive model (e.g. LSTM for time-series forecasting, or a simpler regression baseline)
- Train/test split and evaluation metrics (RMSE, MAE)
- Comparing predicted vs. actual price on a test set
- Adding a `requirements.txt`

## Author
Shreya Jain
