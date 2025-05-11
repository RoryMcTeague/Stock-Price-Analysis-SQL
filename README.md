
# Financial Data Analysis with yFinance & SQLite

This project utilizes `yfinance` to pull historical price data for any ticker (e.g., AAPL, BTC-USD), stores the data in a local SQLite database, calculates monthly returns and volatility, and visualizes the results using Matplotlib.

## Features

- Download historical price data from Yahoo Finance
- Store clean data in a local SQLite database
- Query monthly returns using SQL
- Calculate daily and annualized volatility
- Visualize closing prices and monthly returns

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/RoryMcTeague/quant-price-analysis-sql-python.git
   ```

2. Install the required packages:
   ```bash
   pip install pandas matplotlib yfinance
   ```

3. Run the Jupyter Notebook and follow the prompts to enter a ticker (e.g., `AAPL`, `BTC-USD`).

## Example Outputs

- Line plot of daily closing prices
- Bar chart displaying monthly returns with color-coded gains and losses
- Output of daily and annualized volatility calculations

## File Structure

- `project_notebook.ipynb`: Main notebook for data analysis
- `prices.db`: SQLite database generated during the analysis
- `README.md`: Project documentation

## Notes

- For equity assets, 252 trading days per year is assumed. For cryptocurrency, 365 days may be more accurate.
- Ensure your date range spans at least several years for meaningful trend analysis.

## License

MIT License

## Author

Rory McTeague

[GitHub](https://github.com/RoryMcTeague/)

[LinkedIn](https://www.linkedin.com/in/rory-mcteague-b78637161/)
