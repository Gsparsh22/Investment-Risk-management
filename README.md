# Investment-Risk-management

This repository contains a Python script for analyzing stock performance. The script uses historical stock price data to calculate various metrics and perform financial analysis. The metrics calculated include standard deviation, beta, Treynor Ratio, and Value at Risk (VaR) for a set of predefined stocks.

## Overview

The script performs the following tasks:

1. **Data Fetching**: Retrieves historical stock data from Yahoo Finance for a predefined set of stock symbols and the S&P 500 index.
2. **Data Processing**: Cleans the data, resamples it to a monthly frequency, and calculates monthly percentage returns.
3. **Risk Metrics Calculation**:
   - Calculates the standard deviation of monthly returns for each stock.
   - Computes the beta of each stock relative to the S&P 500 index.
   - Determines the Treynor Ratio for each stock based on a predefined risk-free rate.
   - Computes Value at Risk (VaR) at 95% and 99% confidence levels.
4. **Results**: Aggregates the results into a DataFrame and prints the calculated metrics.

## Dependencies

The script requires the following Python packages:

- `numpy`
- `pandas`
- `yfinance`

Install the dependencies using pip:

```bash
pip install numpy pandas yfinance
