# Basic-Trading-Backtesting-System-
A simple backtesting system to evaluate basic stock trading strategies over historical data. Users can define strategies, simulate trades, and evaluate strategy performance using metrics and visualizations.

Features
- Load historical stock data using an external API.
- Define custom trading strategies.
- Simulate buy and sell actions based on strategy rules.
- Track and evaluate each trade.
- Calculate performance metrics such as total return, number of trades, and average profit per trade.
- Visualize the strategy's performance with portfolio value over time.

Key Class: Trade

Attributes

- symbol: Stock symbol (e.g., "AAPL")
- entry_date: Entry date of the trade
- exit_date: Exit date of the trade
- entry_price: Price at which the stock was bought
- exit_price: Price at which the stock was sold
- quantity: Number of shares bought

Methods

- calculate_profit(): Returns the profit or loss of the trade
- holding_period(): Returns the number of days between entry and exit
