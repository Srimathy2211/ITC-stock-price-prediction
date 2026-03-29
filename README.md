# ITC Stock Price Prediction

This project focuses on predicting the next day's closing price of ITC stock using machine learning techniques and historical market data.

---

## 📌 Project Overview

The objective of this project is to analyze historical stock data of ITC and build predictive models to estimate future closing prices. The approach involves data cleaning, exploratory analysis, feature engineering, and model training.

---

## 📂 Dataset

* Source: Kaggle (ITC Stock Data)
* Features include:

  * Date
  * Open, High, Low, Close prices
  * Volume

---

## 🧹 Data Preprocessing

The dataset was cleaned and prepared using the following steps:

* Checked and handled missing values
* Removed duplicate rows
* Filtered out zero-volume entries (non-trading days)
* Converted date column to datetime format
* Sorted data in chronological order
* Validated OHLC values for consistency

---

## 📊 Exploratory Data Analysis

* Analyzed price statistics (mean, min, max, etc.)
* Visualized long-term price trends
* Studied return distributions and yearly performance
* Identified patterns and fluctuations in stock behavior

---

## ⚙️ Feature Engineering

To improve model performance, several financial indicators were created:

### Trend Indicators

* Moving Averages (MA: 7, 20, 50, 200)
* Exponential Moving Averages (EMA: 12, 26)

### Momentum Indicators

* MACD (Moving Average Convergence Divergence)
* RSI (Relative Strength Index)

### Volatility Indicators

* Bollinger Bands
* Rolling volatility (standard deviation of returns)

### Additional Features

* Price Range (High - Low)
* Close - Open difference
* Volume moving average

---

## 🤖 Models Used

### 1. Linear Regression

* Used as a baseline model
* Assumes a linear relationship between features and target

### 2. Random Forest Regressor

* Ensemble learning model
* Captures complex and non-linear patterns in data

---

## 📏 Evaluation Metrics

The models were evaluated using:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)
* MAPE (Mean Absolute Percentage Error)
* R² Score

---

## 📈 Results

* Random Forest performed better than Linear Regression
* It was able to capture non-linear relationships more effectively
* Predictions were reasonably close to actual values in most cases

---

## ⚠️ Limitations

* Model uses only historical price and volume data
* External factors like news, economic events, and sentiment are not included
* Sudden market changes cannot be fully predicted

---

## 🚀 Future Improvements

* Include market indices (e.g., Nifty 50) as features
* Try classification approach (predicting price direction)
* Explore deep learning models like LSTM
* Incorporate sentiment analysis from financial news

---

## 📁 Project Structure

* `itc_stock_prediction.ipynb` → Main notebook
* `ITC.csv` → Dataset
* `viz*.png` → Visualizations

---

## 🧠 Key Learning

Through this project, I understood the importance of feature engineering in financial data and how different models perform on time-based datasets.

---

⭐ This project demonstrates practical application of machine learning techniques for financial data analysis.
