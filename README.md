# Portfolio Monitoring Notebook

This Jupyter Notebook, `PORTFOLIO_MONITORING.ipynb`, provides a framework for tracking and analyzing a financial portfolio consisting of various stock tickers. It pulls historical price data, computes performance metrics, and visualizes trends to aid in portfolio monitoring and evaluation.

## Features

- **Ticker-Based Portfolio Tracking**  
  Define a custom list of stock tickers representing your portfolio holdings.

- **Historical Price Retrieval**  
  Automatically fetches adjusted closing prices for all tickers using Yahoo Finance data via the `yfinance` API.

- **Return Calculations**  
  Computes daily returns and cumulative returns for each stock in the portfolio.

- **Performance Visualization**  
  Plots:
  - Adjusted Close Prices
  - Daily Returns
  - Cumulative Returns over time

- **Portfolio Aggregation**  
  Supports simple portfolio aggregation using equal weighting (can be extended to custom weights).

- **Clean, Modular Code**  
  Makes use of Pandas for data wrangling and Matplotlib for visualizations, with clear code blocks for customization.

## Dependencies

To run this notebook, you will need the following Python libraries:

```bash
pip install pandas numpy yfinance matplotlib
```

## How to Use

1. Clone or download the notebook.
2. Install the dependencies listed above.
3. Define your list of stock tickers in the designated cell.
4. Run the notebook cell by cell to:
   - Fetch data
   - Calculate returns
   - Visualize portfolio performance


## Notes

- The notebook uses equal-weighting by default. If you want to adjust the portfolio to reflect actual investment amounts, modify the weighting logic accordingly.
- All data is retrieved from Yahoo Finance, which may have limitations in availability or accuracy depending on the ticker.



