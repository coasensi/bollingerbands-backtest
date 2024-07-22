This Python program is designed to backtest a technical analysis based algorithmic trading strategy. 

**The strategy**

The Bollinger Bands strategy is a technical analysis tool used to identify overbought and oversold conditions in the market. It involves calculating three lines: a simple moving average (SMA, 20 days in our example) of the stock price, an upper band set at 2 standard deviations above the SMA, and a lower band set at 2 standard deviations below. 
Signals are the following:

BUY when the price crosses the lower band from the top. Hold until it crosses the upper band from below.

SELL when the price crosses the upper band from below. Hold until it crosses the lower band from the top.

This strategy leverages mean reversion, expecting prices to revert back to the mean (SMA) over time.
