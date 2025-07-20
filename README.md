🪙 Gold Price Forecasting Using Time Series Analysis (ARIMA & SARIMA)
This project performs time series analysis and forecasting on monthly gold prices using ARIMA and SARIMA models. The analysis is conducted in Python using yfinance for data extraction, statsmodels for modeling, and matplotlib for visualization. It includes a full Streamlit app for interactive forecasting and model comparison.

📦 Features
✅ Time Series Workflow:
📥 Data Source: Gold futures (GC=F) from Yahoo Finance

📊 Data Cleaning: Handling missing values, focusing on monthly close price

📈 Visualization: Trends from 2005–2025

⚙️ STL Decomposition: Extract trend and seasonality

📉 ADF Test: Check for stationarity

🔁 Differencing: Achieve stationarity

🧠 ACF & PACF Analysis: Identify ARIMA parameters

🔮 Forecasting:

ARIMA(1,1,1)

SARIMA with seasonal components

📉 Model Evaluation: Based on AIC scores

💾 Model Saving: Serialize the model using Pickle
