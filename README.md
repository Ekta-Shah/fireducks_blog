# Pandas vs. Fireducks Performance Benchmark

This notebook compares the performance of Pandas and a hypothetical library called "Fireducks" for common financial data analysis tasks.

## Purpose

The goal is to evaluate the potential performance improvements offered by Fireducks, which leverages DuckDB, compared to traditional Pandas data manipulation.

## Methodology

The notebook performs the following operations using both Pandas and Fireducks, and measures the execution time for each:

1. **Daily Return Calculation:** Calculating the daily percentage change in stock prices.
2. **Cumulative Return Calculation:** Computing the cumulative return for each stock.
3. **30-Day Rolling Volatility Calculation:** Determining the 30-day rolling volatility of stock returns.
4. **Portfolio Optimization:** Using optimization techniques to find an optimal portfolio allocation based on Sharpe Ratio.

## Results

The notebook outputs the execution times for each operation using both Pandas and Fireducks. This allows for a direct comparison of their performance.

## Usage

1. **Installation:**
   - Install the required libraries: `!pip install fireducks pandas numpy scipy`
2. **Data:**
   - Replace `stocks.csv` with your stock data file. Ensure it has columns for 'date', 'symbol', and 'price'.
3. **Execution:**
   - Run all cells in the notebook.

