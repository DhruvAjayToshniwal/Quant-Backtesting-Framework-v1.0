# Quant-Backtesting-Framework-v1.0

# Quantitative Trading Strategy Backtesting

This project demonstrates a quantitative trading strategy backtesting implementation using the `backtrader` library in Python.

## Description

The project includes a Python script that performs a backtest of a trading strategy using historical stock price data. The strategy is based on a simple moving average (SMA) crossover and relative strength index (RSI) conditions.

The script fetches historical stock price data from Yahoo Finance using the `yfinance` library. It then converts the data to a `backtrader` data feed and sets up the strategy using the `MyStrategy` class.

The strategy generates buy and sell signals based on the SMA crossover and RSI conditions. It executes the orders using the `backtrader` framework.

The project also includes a demonstration of calculating performance metrics such as final portfolio value, Sharpe Ratio, and drawdown using built-in analyzers from `backtrader`.

## Features

- Fetches historical stock price data from Yahoo Finance
- Calculates technical indicators such as SMA and RSI using `pandas_ta` library
- Implements a strategy based on SMA crossover and RSI conditions
- Executes buy and sell orders using `backtrader` framework
- Calculates performance metrics including final portfolio value, Sharpe Ratio, and drawdown
- Plots the equity curve of the backtest using `cerebro.plot()`

## Requirements

- Python 3.6+
- `backtrader` library: Install with `pip install backtrader`
- `yfinance` library: Install with `pip install yfinance`
- `pandas_ta` library: Install with `pip install pandas_ta`
