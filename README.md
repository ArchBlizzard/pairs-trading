## Pairs Trading Strategy for Nifty 50
This repository provides a Python script for running a pairs trading strategy on Nifty 50 stocks. It:

- Fetches Data: Downloads historical close prices for Nifty 50 stocks using yfinance.
- Identifies Pairs: Finds highly correlated pairs, then tests them for cointegration.
- Calculates Hedge Ratios: Uses covariance and variance to determine an optimal hedge ratio.
- Generates Signals: Based on the spread’s rolling z-score, issues entry/exit signals.
- Backtests: Allocates capital evenly, simulates trades, and computes performance metrics with quantstats.
- Visualizes: Plots the selected pair’s prices and the portfolio’s value over time.






