# 📌 Stock Market Analysis

## 📜 Table of Contents

- Project Overview
- Dataset Description
- Stock Market Analysis
- Results & Insights
- Visualizations
- How to Use
- Future Scope
- Contributors
- License

## 📌 Project Overview

This project analyzes stock market data to track price movements, detect trends, and assess volatility. By applying moving averages, volatility analysis, and return calculations, this project helps investors and analysts make data-driven decisions.

## 📂 Dataset Description

The dataset (Stock_Data.csv) consists of 233 rows and includes:
- Date → Trading date
- Adj_Close → Adjusted closing price
- Close → Closing price
- High → Highest price of the day
- Low → Lowest price of the day
- Open → Opening price
- Volume → Shares traded

## 📈 Stock Market Analysis

1️⃣ Data Cleaning & Preparation
✅ Fixed column headers & converted data types.
✅ Handled missing values & duplicate entries.

2️⃣ Key Financial Metrics
✅ Moving Averages → Computed 20-day & 50-day moving averages.
✅ Daily Returns → Calculated percentage change in closing prices.
✅ Volatility Analysis → Measured 20-day rolling standard deviation of returns.

## 📊 Results & Insights

- Stock prices exhibit short-term fluctuations, but long-term trends align with moving averages.
- Volatility analysis reveals periods of high uncertainty in the market.
- Daily returns follow a near-normal distribution, but outliers indicate sharp market movements.

## 📊 Visualizations

- 📈 Stock Prices & Moving Averages
- 📊 Stock Volatility Over Time
- 📉 Distribution of Daily Returns

## 📷 Example Visuals

## 📎 How to Use
## 🖥️ Clone the repository:
git clone https://github.com/NiraliKhambhati/Stock-Market-Analysis.git

## 📦 Install dependencies:
pip install pandas matplotlib seaborn numpy scipy

## 📊 Run the Jupyter Notebook:
jupyter notebook Stock_Data.ipynb

## 📌 Future Scope
🔹 Implement Machine Learning models for stock price prediction.
🔹 Incorporate technical indicators like RSI & MACD.
🔹 Build an interactive dashboard for real-time stock tracking.

## 👥 Contributors
Nirali Khambhati - Project Lead & Data Analyst

## 📧 For Queries: Reach out via GitHub Issues or email!
## 🎯 Author: Nirali Khambhati

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

