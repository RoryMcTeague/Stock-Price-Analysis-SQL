# Financial Data Analysis with yFinance & SQLite

This project pulls historical price data for any ticker (e.g., AAPL, BTC-USD) using `yfinance`, stores it in a SQLite database, calculates monthly returns and volatility, and visualizes the results using Matplotlib.

## 📌 Features

- ✅ Download historical data from Yahoo Finance
- ✅ Save clean data to a local SQLite database
- ✅ Query monthly returns using SQL
- ✅ Compute daily and annualised volatility
- ✅ Plot closing prices and monthly returns

## 🔧 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/RoryMcTeague/quant-price-analysis-sql-python.git
   ```
2. Install the required packages:
   ```bash
   pip install pandas matplotlib yfinance
   ```
3. Run the Jupyter Notebook and follow the prompts to enter a ticker (e.g., `AAPL`, `BTC-USD`).

## 📊 Example Outputs

- Line plot of daily closing prices
- Coloured bar chart of monthly returns
- Printed daily and annualised volatility

## 📁 Files

- `project_notebook.ipynb`: Main notebook for analysis
- `prices.db`: SQLite database created when you run the notebook
- `README.md`: This file

## 🧠 Notes

- Equities assume ~252 trading days/year, while crypto may use 365.
- Make sure your date range spans at least a few years for meaningful trends.

## 📜 License

MIT License
