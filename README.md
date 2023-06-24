# Quant-Backtesting-Framework-v1.0

# Quantitative Trading Strategy Backtesting

This project demonstrates a quantitative trading strategy backtesting implementation using the `backtrader` library in Python.

## Description

The project includes a Python script that performs a backtest of a trading strategy using historical stock price data. The strategy is based on a simple moving average (SMA) crossover and relative strength index (RSI) conditions.

The script fetches historical stock price data from Yahoo Finance using the `yfinance` library. It then converts the data to a `backtrader` data feed and sets up the strategy using the `MyStrategy` class.

The strategy generates buy and sell signals based on the SMA crossover and RSI conditions. It executes the orders using the `backtrader` framework.

The project also includes a demonstration of calculating performance metrics such as final portfolio value, Sharpe Ratio, and drawdown using built-in analyzers from `backtrader`. Additionally, it saves the equity curve plot as an image file.

## Features

- Fetches historical stock price data from Yahoo Finance
- Calculates technical indicators such as SMA and RSI using `pandas_ta` library
- Implements a strategy based on SMA crossover and RSI conditions
- Executes buy and sell orders using `backtrader` framework
- Calculates performance metrics including final portfolio value, Sharpe Ratio, and drawdown
- Saves the equity curve plot as an image file

## Requirements

- Python 3.6+
- `backtrader` library: Install with `pip install backtrader`
- `yfinance` library: Install with `pip install yfinance`
- `pandas_ta` library: Install with `pip install pandas_ta`
- `matplotlib` library: Install with `pip install matplotlib`

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/DhruvAjayToshniwal/Quant-Backtesting-Framework-v1.0.git
Install the required libraries:

Modify the script to define your desired stock symbol, date range, and strategy parameters.

Run the script:

bash
Copy code
python backtest.py
View the backtest results, including final portfolio value, performance metrics, and the equity curve plot image saved as equity_curve.png.

Results
The backtest script generates the following results:

Final Portfolio Value: The final value of the portfolio after running the backtest.
Performance Metrics: The Sharpe Ratio and drawdown of the backtested strategy.
Equity Curve Plot: The equity curve plot is saved as an image file named equity_curve.png.
License
This project is licensed under the MIT License.

Feel free to modify and customize the code to suit your needs.

Acknowledgements
backtrader documentation
yfinance documentation
pandas_ta documentation
matplotlib documentation

![image](https://github.com/DhruvAjayToshniwal/Quant-Backtesting-Framework-v1.0/assets/57616258/59bdbf54-9fac-4f6f-a695-186449307552)

