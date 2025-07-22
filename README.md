# 📈 Time Series Analysis and Forecasting of Stock Market Using ARIMA

This project focuses on predicting future stock market trends using the ARIMA model, implemented in Python via Jupyter Notebook. The final results are visualized using an interactive dashboard in Power BI.

---

## 🧠 Objective

To forecast future stock prices using time series analysis and ARIMA modeling, and visualize the trends and predictions in a user-friendly Power BI dashboard.

---

## 🚀 Technologies Used

- **Python** – For data analysis and ARIMA modeling
- **Jupyter Notebook** – Development and code execution environment
- **Pandas & Numpy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **statsmodels** – ARIMA implementation
- **Power BI** – Dashboard for visual analysis
- **Excel** – Intermediate storage of model output for dashboard creation

---

## 📊 Workflow Overview

1. **Data Collection**
   - Historical stock data was downloaded using Yahoo Finance or CSV files.

2. **Data Preprocessing**
   - Converted date columns to datetime format
   - Cleaned missing values
   - Visualized and tested for stationarity (using rolling mean and ADF test)

3. **Model Building (ARIMA)**
   - Identified the best (p, d, q) values using ACF and PACF plots
   - Trained ARIMA model on the historical data
   - Forecasted stock prices for the next 15/30 days

4. **Exporting Results**
   - Forecast results were saved into an Excel file for integration with Power BI

5. **Power BI Dashboard**
   - An interactive dashboard was built showing:
     - Actual vs Forecasted prices
     - Trendlines
     - Date-wise predictions
     - Summary statistics

---

## 📂 Project Structure

