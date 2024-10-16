# Stock Data Analysis and Portfolio Optimization

This Jupyter Notebook provides a comprehensive guide to download and analyze historical stock data, visualize the data, and optimize a portfolio using various metrics. The code uses Python libraries such as `yfinance`, `pandas`, `numpy`, and `matplotlib` for data processing and visualization.

## Features

1. **Downloading Historical Stock Data**:
   - Utilizes `yfinance` to download historical stock prices for a list of tickers (e.g., SPY, AAPL, META, NVDA, AMZN) over a specified time range.
   - Displays key information such as adjusted close prices and trading volumes.

2. **Data Visualization**:
   - Plots the adjusted close prices for each ticker.
   - Includes visual aids like legends, gridlines, and labels for clarity.

3. **Statistical Analysis**:
   - Computes and displays essential statistical metrics (mean, median, standard deviation, variance, skewness, and kurtosis) for the adjusted close prices.
   - Generates box plots to visualize the distribution of stock prices and identify outliers.

4. **Portfolio Optimization**:
   - Analyzes log returns and visualizes the efficient frontier for portfolio optimization.
   - Calculates and highlights optimal portfolios, including:
     - Maximum Sharpe Ratio Portfolio
     - Minimum Volatility Portfolio
     - Minimum Value at Risk (VaR) Portfolio
   - Visualizes these portfolios and provides details on their weights, returns, and risk levels.

## Requirements

- Python 3.7+
- Libraries: `yfinance`, `pandas`, `numpy`, `matplotlib`

## Usage

1. **Install Dependencies**:
   ```bash
   pip install yfinance pandas numpy matplotlib
   ```

2. **Run the Notebook**:
   - Open the notebook in Jupyter or JupyterLab.
   - Execute the cells sequentially to download data, visualize, and analyze stock information.

3. **Modify Tickers or Date Range**:
   - Update the `tickers` list and the `from_time`/`to_time` variables to fetch data for different stocks or time ranges.

## Notes

- The notebook provides visualization tools to understand stock performance and portfolio risks.
- Ensure that you have a stable internet connection to download stock data via `yfinance`.

## License

This project is open-source and available for modification and redistribution.


