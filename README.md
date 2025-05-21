# 📈 Stock Portfolio Monitoring & Visualization (2015–2025)

This project builds an intelligent stock portfolio tracking and visualization system that helps investors monitor, analyze, and optimize their equity investments. Using real-time and historical market data, it calculates performance metrics, generates insightful visualizations, and suggests future investment plans based on market capitalization. Ideal for personal finance enthusiasts, beginner investors, and anyone looking to manage portfolios with a data-driven approach.

## 📌 Features

* Tracks 10 major Indian stocks listed on the NSE from 2015 to 2025
* Allows users to build custom portfolios (by amount or percentage weights)
* Calculates key metrics like total return, CAGR, and individual stock gains
* Suggests optimized rebalanced portfolio based on 2025 market cap weights
* Visualizes portfolio trends with dynamic charts and plots
* Real-time stock price fetching using Yahoo Finance (yfinance API)

## 🔧 Requirements

This notebook is designed to run in **Jupyter Notebook**. It uses the following libraries:

* Python 3.9+
* [yfinance](https://github.com/ranaroussi/yfinance)
* pandas
* matplotlib

## 🚀 Setup and Usage

1. **Open in Jupyter Notebook**
   Run the Python notebook in any Jupyter environment (local or cloud-based).

2. **Install dependencies**

   ```bash
   pip install yfinance pandas matplotlib
   ```

3. **Customize Your Investment**

   * Input your total investment amount (e.g., ₹5,00,000).
   * Choose your allocation method:

     * **Manual Weights** (percentage allocation)
     * **Fixed Amounts** (specific amount per stock)

4. **Run Portfolio Tracking**
   The script:

   * Loads historical stock data (2015–2025)
   * Calculates purchased shares based on 2015 prices
   * Tracks daily portfolio value over time
   * Computes performance metrics:

     * **Total Return**
     * **CAGR (Compound Annual Growth Rate)**
     * **Gains per stock**

5. **Visual Output**
   Generates easy-to-understand charts:

   * 📈 Portfolio growth over time
   * 🥧 Current allocation pie chart
   * 📊 Gains per stock bar chart

6. ⚙️ Configuration

   * `investment_amount`: Total lump-sum invested (e.g., ₹5,00,000)
   * `start_year`: Portfolio start year (default: 2015)
   * `tickers`: List of NSE stock tickers (default: 10 selected Indian companies)
   * `allocation_method`: Choose between `'weights'` or `'amounts'`
   * `rebalancing`: Option to compute an optimized portfolio based on 2025 market capitalization

7. 📁 Output

   * Interactive plots and performance tables directly in the notebook
   * Suggested rebalanced investment plan for 2025 based on current market cap weights

## 🧠 Model Info

* **Selected Nifty-50 Stocks**:

  * RELIANCE.NS, TCS.NS, INFY.NS, HDFCBANK.NS, ICICIBANK.NS, ITC.NS, LT.NS, SBIN.NS, HINDUNILVR.NS, ASIANPAINT.NS
  * | S. No. | Company Name                     | Ticker       |
    |--------|----------------------------------|--------------|
    | 1      | Reliance Industries Ltd.         | RELIANCE.NS
    | 2      | Tata Consultancy Services Ltd.   | TCS.NS       |
    | 3      | Infosys Ltd.                     | INFY.NS      |
    | 4      | HDFC Bank Ltd.                   | HDFCBANK.NS  |
    | 5      | ICICI Bank Ltd.                  | ICICIBANK.NS |
    | 6      | ITC Ltd.                         | ITC.NS       |
    | 7      | Larsen & Toubro Ltd.             | LT.NS        |
    | 8      | State Bank of India              | SBIN.NS      |
    | 9      | Hindustan Unilever Ltd.          | HINDUNILVR.NS|
    | 10     | Asian Paints Ltd.                | ASIANPAINT.NS|

* **Data Source**: Yahoo Finance via yfinance API
* **Performance Metrics**:

  * Total Return: 294.83%
  * CAGR: 14.19%
  * Top Gainer: RELIANCE.NS (+₹3,03,028)

## 📝 Notes

* The portfolio assumes lump-sum investment and whole-share purchases (no fractional shares).
* Real-time data fetching ensures up-to-date performance tracking.
* The optimized plan uses 2025 market cap weights to suggest a balanced portfolio aligned with NSE structure.
* The project simulates realistic investor scenarios (excluding fractional shares, respecting cash balances).

---

