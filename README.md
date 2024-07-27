
## Data Acquisition and Preparation

The `yfinance` library is used to gather daily historical price data for the top 20 stocks by market capitalization listed on the NSE over the past 5 years. The data includes necessary fields such as open, high, low, close, and volume.

## Strategy Implementation and Backtesting

A simple moving average (SMA) crossover strategy is implemented in Python. The strategy uses two SMAs: a short-term SMA (50 days) and a long-term SMA (200 days). Buy signals are generated when the short-term SMA crosses above the long-term SMA, and sell signals are generated when the short-term SMA crosses below the long-term SMA.

The backtest is run on each of the top 20 stocks using the implemented strategy. Key performance metrics are calculated, including:

- Total returns
- Annualized returns
- Maximum drawdown
- Sharpe ratio
- Win/Loss ratio
- Number of trades executed

## Analysis and Insights

The backtesting results are visualized using charts. The results are analyzed to identify the strengths and weaknesses of the strategy. The analysis discusses how market conditions (e.g., bull vs. bear markets) affected the strategy's performance and suggests potential improvements or modifications to the strategy.


## Usage

1. **Fetch Data**: The script fetches historical price data for the specified stocks.
2. **Implement Strategy**: The SMA crossover strategy is applied to each stock's data.
3. **Backtest Strategy**: The strategy is backtested, and performance metrics are calculated.
4. **Visualize Results**: The performance of each stock is visualized with charts.
5. **Generate Report**: A comprehensive report is generated, summarizing the results and analysis.

