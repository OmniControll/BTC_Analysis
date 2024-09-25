# **Bitcoin (BTC) Price Prediction using Time-Series Analysis and Regression Models**

This project analyzes the historical price of Bitcoin (BTC-USD) using  time-series decomposition techniques and regression models, Linear and Polynomial Regression. The goal is to model and predict BTC's price trends based on historical data fetched via the Yahoo Finance API.

## **Project Overview**

The project covers several key areas of financial data analysis:
1. **Data fetching**: Historical price data of Bitcoin (BTC-USD) is retrieved using the `yfinance` API.
2. **Time-series decomposition**: Analyze the seasonality, trends, and residuals in Bitcoin prices using both multiplicative and additive models.
3. **Regression analysis**: Apply Linear and Polynomial Regression models to predict BTC's closing price.
4. **Moving Average Crossover**: Visualize short-term and long-term trends in Bitcoin prices with a moving average crossover strategy.
5. **Model evaluation**: Calculate performance metrics like Mean Squared Error (MSE) and R-squared scores to evaluate the accuracy of the models.

## **Features**

- **Time-Series Decomposition**: Examine the seasonal and trend components of BTC prices using both multiplicative and additive models.
- **Linear Regression**: A basic linear model is used to predict the price trends based on time as the independent variable.
- **Polynomial Regression**: Polynomial regression of degree 3 is applied to capture the non-linear trends in the BTC price.
- **Moving Average Crossover**: A crossover strategy is implemented using short (20-day) and long (100-day) moving averages to capture trends in price momentum.

## **Data Source**

The data used for this analysis is fetched from Yahoo Finance, covering the period from **January 2021** to **September 2024**.

## **Libraries Used**

- `yfinance`: For fetching historical stock data.
- `matplotlib`: For plotting and visualizing the data and model results.
- `pandas`: For data manipulation and handling time-series data.
- `sklearn`: For implementing regression models.
- `statsmodels`: For time-series decomposition to analyze trends and seasonality.
