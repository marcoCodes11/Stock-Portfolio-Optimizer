# Robo-Stock Advisor

A Python-based portfolio optimization tool that analyzes historical stock market data and determines an optimal portfolio allocation based on risk-adjusted returns.

## Features

- Downloads 5 years of historical stock data using yfinance
- Analyzes AAPL, MSFT, GOOG, AMZN, and NVDA
- Calculates daily and annualized returns
- Calculates portfolio volatility and covariance
- Calculates Sharpe ratios
- Uses SciPy optimization to maximize risk-adjusted returns
- Determines optimal portfolio weights
- Visualizes historical prices, portfolio allocation, and risk vs. return

## Technologies

- Python
- Pandas
- NumPy
- SciPy
- yfinance
- Matplotlib

## Portfolio Optimization

The program uses constrained optimization to maximize the portfolio's Sharpe ratio while ensuring:

- Portfolio weights total 100%
- Each stock has a weight between 0% and 100%
- Short selling is not allowed
