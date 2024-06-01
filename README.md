# Time Series Forecasting of Stock Prices using SARIMAX and Trading Strategy Classification

## Introduction
This project was implemented as a part of Data Analytics Hackathon conducted by the CSE department of PES University. Our team consisted of H.V Siri, Harshitha Sai and myself. The project aims to forecast stock prices using SARIMAX(Seasonal AutoRegressive Integrated Moving Average with Exogeneous regressors) model for time series analysis, and classify optimal trading strategies (Buy, Hold, Sell) based on various technical indicators. The project is implemented in Python and also utilizes the XGBoost algorithm for trading strategy classification. 

## Project Overview
The main objectives of this project are:
  1. Time Series Forecasting of Stock Prices using SARIMAX:
     Forecast future closing stock prices using the SARIMAX model.

  2. Trading Strategy Classification:
     Train an XGBoost classifier to predict the optimal trading strategy (Buy, Hold, Sell) based on the forecasted closing prices and other technical indicators.

## Dataset
The dataset used in this project is obtained from Kaggle and consists of historical stock data with the following features:
  - Date
  - Open: Opening stock price
  - Close: Closing stock price
  - Volume: Trading volume
  Strategy: Trading strategy(Buy, Hold, Sell)
The dataset is split into training and testing sets for model evaluation.

## Prerequisites
To run this project, you need to have the following libraries installed:
  - Python (>=3.6)
  - Numpy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
  - Statsmodels
  - XGBoost

## Installation
To run this project locally, clone the following repository
```
git clone git@github.com:Sahana-Math/Time-Series-forecasting-of-stock-prices.git
```

## Results
The project generates the following outputs:
  1. Forecasted closing stock prices using the SARIMAX model.
  2. Predicted trading strategies using the XGBoost classifier.
  3. Performance evaluation metrics for both the forecasting and classification tasks. 
