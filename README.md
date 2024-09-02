
# Stock Price Prediction

This project focuses on predicting stock prices using machine learning models. The goal is to analyze historical stock market data and predict future stock prices based on various features.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Usage](#usage)
- [Models Used](#models-used)
- [Results](#results)

## Introduction
This case study demonstrates how to use Long Short-Term Memory (LSTM) units to build an Artificial Neural Network (ANN) for predicting Google stock prices (though it can be applied to other similar cases). The model takes into account multiple predictive factors (features). For instance, the final stock price can be predicted by analyzing the importance of features such as historical low prices, high prices, trading volume, adjusted prices, and more. The aim of this model is to provide a more accurate method for predicting stock market movements, helping investors make more informed decisions.

## Dataset
The dataset used in this project consists of historical stock prices. It includes features such as:
- Date
- Open Price
- High Price
- Low Price
- Close Price
- Volume

The dataset can be obtained from financial data sources such as Yahoo Finance, Alpha Vantage, or other stock market databases.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Cyanogen0305/Stock_Price_Prediction.git
   ```
2. Navigate to the project directory:
   ```bash
   cd stock_price_prediction
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook stock_price_prediction.ipynb
   ```
4. Run the cells in the notebook to execute the code and visualize the results.

## Models Used
This project primarily utilizes the Long Short-Term Memory (LSTM) neural network for stock price prediction. LSTM is particularly well-suited for this task due to its ability to capture temporal dependencies in sequential data, such as stock prices over time.

## Results
The results section of the notebook provides a detailed analysis. Charts and graphs are used to visualize the predicted vs. actual stock prices.
