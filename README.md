# Stock Market Analysis

![Designer](https://github.com/AngadVM/Stock_Market_Analysis/assets/144656294/ec30c9bf-6e2d-4608-88b2-dc76e330117a)

Time Series data is a series of data points indexed in time order. Time series data is everywhere, so manipulating them is important for any data analyst or data scientist.

In this notebook, I explored data from the stock market, particularly focusing on some technology stocks (Apple, Amazon, Google, and Microsoft). During this project, I utilized yfinance to obtain stock information and employed Seaborn and Matplotlib to visualize different aspects of the data. I also analyzed the risk of these stocks based on their previous performance history. Additionally, I predicted future stock prices using a Long Short-Term Memory (LSTM) method.

The insights we will be discovering are as follows:
1. **What was the change in price of the stock over time?**
2. **What was the moving average of the various stocks?**
3. **What was the trading volume trend for the stock over time?**
4. **How did the closing prices of different stocks correlate with major market indices?**
5. **What is the Value at Risk (VaR) for the portfolio containing different stocks?**
6. **Predicting the stock price of APPLE Inc. using different machine learning models.( along with LSTM, we'll be using SVR )**

# Getting the Data

The first step is to get the data and load it to memory. We will get our stock data from the Yahoo Finance website. Yahoo Finance is a rich resource of financial market data and tools to find compelling investments. To get the data from Yahoo Finance, we will be using yfinance library which offers a threaded and Pythonic way to download market data from Yahoo. Check this article to learn more about yfinance: https://aroussi.com/post/python-yahoo-finance
