# 📈 Stock Analysis and Prediction

This project leverages Long Short-Term Memory (LSTM), a type of recurrent neural network, to analyze and predict stock closing prices for four major tech companies: *Tesla (TSLA), **NVIDIA (NVDA), **Netflix (NFLX), and **Meta Platforms (META)*.

---

## 🚀 Project Overview

The goal of this project is to:
* Collect historical stock data using yfinance
* Visualize trends, volumes, and moving averages
* Build an LSTM model to predict closing prices
* Evaluate the model using RMSE and visual comparison

---

## 📊 Technologies Used

* Python 3.x
* [yfinance](https://pypi.org/project/yfinance/)
* NumPy & Pandas
* Matplotlib & Seaborn
* scikit-learn
* Keras & TensorFlow (LSTM implementation)
* Google Colab (for running notebooks)

---

## 📁 Dataset

Stock data is fetched live using the yfinance library for:
* Tesla (TSLA)
* NVIDIA (NVDA)
* Netflix (NFLX)
* Meta (META)

Timeframe: Past 1 year from the current date.

---

## 📉 Features and Steps

### 🔹 1. Data Collection
* Fetched historical data using yfinance.download()
* Stored daily stock data for each company

### 🔹 2. Visualization
* Plotted:
  - Adjusted Close price over time
  - Daily return percentage
  - Moving averages (10, 20, 50 days)
  - Volume traded
* Used subplots for comparative visualization

### 🔹 3. Data Preprocessing
* Used MinMaxScaler to normalize stock prices between 0 and 1
* Created training and test datasets (60-day sliding window)

### 🔹 4. LSTM Model
* 2 stacked LSTM layers
* 1 dense output layer
* Loss function: Mean Squared Error
* Optimizer: Adam

### 🔹 5. Evaluation
* Plotted actual vs predicted closing prices
* Calculated RMSE to evaluate model accuracy

---

## 📷 Sample Outputs

* *Closing price trend*
* *Prediction vs Actual*
* *Daily Returns*
* *Moving Averages*

---

## 👨‍💻 Author

*Suraj Pradhan*  
IIT ISM Dhanbad

---
