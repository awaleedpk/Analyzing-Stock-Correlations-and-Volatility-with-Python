# Stock Correlation and Volatility Analysis Using Python

This repository contains a Python script for analyzing the correlations and volatility of selected semiconductor stocks: AMD, NVIDIA (NVDA), Intel (INTC), and TSMC (TSM). The analysis includes fetching historical stock data, calculating correlation matrices, visualizing these correlations using heatmaps, and analyzing the volatility of the stocks over a specified period.

## Overview

Understanding the relationship between different stocks and their associated risk (volatility) is crucial for effective portfolio management. This repository provides a step-by-step guide and the corresponding code to perform these analyses using Python.

## Features

- **Fetch Historical Stock Data**: Automatically download stock data from Yahoo Finance using the `yfinance` library.
- **Correlation Analysis**: Compute the correlation matrix to understand how stocks move relative to one another.
- **Heatmap Visualization**: Visualize the correlation matrix using a heatmap for easy interpretation.
- **Volatility Analysis**: Calculate the annualized volatility of each stock, providing insight into the risk associated with each asset.
- **Data Summary**: Generate summary statistics for stock prices over the selected time period.

## Requirements

Make sure you have the following Python packages installed:

- `yfinance`
- `pandas`
- `seaborn`
- `matplotlib`

You can install these dependencies using pip:

```bash
pip install yfinance pandas seaborn matplotlib
```

## Usage

1. **Clone the Repository**:



2. **Run the Script**:

   Execute the Python script to perform the analysis:

   ```bash
   python stock_analysis.py
   ```

3. **View the Outputs**:

   - **Summary Statistics**: Prints out summary statistics for the stock prices.
   - **Correlation Heatmap**: Displays a heatmap of the correlation matrix.
   - **Volatility Bar Chart**: Displays a bar chart of the annualized volatility for each stock.

## Script Details

### stock_analysis.py

This script performs the following tasks:

1. **Import Libraries**: The necessary Python libraries are imported, including `yfinance`, `pandas`, `seaborn`, and `matplotlib`.
   
2. **Define Stock Symbols and Date Range**: The stock symbols (AMD, NVDA, INTC, TSM) and the date range (from January 1, 2020, to August 17, 2024) are defined.

3. **Fetch Stock Data**: The script uses `yfinance` to download historical stock data for the defined symbols and date range.

4. **Summary Statistics**: The script outputs summary statistics for the adjusted closing prices of the stocks.

5. **Correlation Matrix and Heatmap**: The script calculates the daily percentage change for each stock, computes the correlation matrix, and visualizes it using a heatmap.

6. **Volatility Calculation and Visualization**: The script calculates the annualized volatility for each stock and displays it in a bar chart.

## Contributing

If you have suggestions for improving this analysis or want to add new features, feel free to fork the repository, make your changes, and submit a pull request. Contributions are welcome!


## Acknowledgments

- The `yfinance` library for providing a simple API to access financial data from Yahoo Finance.
- The Python community for the amazing tools and libraries that make data analysis accessible and powerful.


---

Thank you for checking out this project! We hope it helps you in your journey of stock market analysis using Python.
