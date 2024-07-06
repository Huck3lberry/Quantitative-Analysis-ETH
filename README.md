# Quantitative-Analysis-ETH

Tasks:
Part 1. – Data Analysis
    1. Check for stationarity. Explain process and conclusion.
    2. Create stationary time series. Explain process and why chosen.
    3. Check for stationarity to confirm. How to we know it is now stationary?
    4. Show autocorrelation and partial autocorrelation function. What are the findings? What do they show for varying timeframes of the data (Hourly, Daily, Weekly, Monthly)?
    5. Are returns normally distributed?
    6. What other types of time series analysis might be useful here when looking at ETH price data?

Part 2. – Create simple MA strategy
For this section feel free to use a framework you are familiar with such as Backtrader or Zipline, or implement your own simple backtesting script.
    1. Create two exponential moving averages (EMAs) of difference length on price and plot. One 20day EMA and one 40day EMA
    2. Create a BUY signal when short EMA crosses above long EMA AND price is greater than short EMA.
    3. How many long signals are generated over the data?
    4. What was the return, no. of trades, drawdown and sharpe?
    5. How could you improve this strategy?
