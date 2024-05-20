# Hamoye Project

# Stock Market Comparison Analysis using Web Scraping and Python
This project involves a methodical examination of multiple stocks within the stock market. By analyzing the performance of various stocks, the project aims to gain insights into their behavior relative to each other and the broader market. This analysis will assists investors, financial analysts, and decision-makers in making informed investment decisions about which stocks to buy, hold, or sellbased on financial metrics and market conditions.
* Python Code [Here](https://github.com/Mayreeobi/Stock-Market-Analysis/blob/main/most_active_stock.ipynb)

## Objectives:
- Scrape the most active stock symbols from Yahoo Finance.
- Retrieve real-time stock data for one day at one-minute intervals.
- Save the data to a CSV file.
- Perform analysis on selected stocks: Apple (AAPL), Tesla (TSLA), and Nvidia (NVDA).
- Calculate and analyze daily return, cumulative return, and volatility.
- Provide insights and recommendations based on the analysis.

## Libraries Used
- requests: For sending HTTP requests.
- BeautifulSoup: For parsing HTML content.
- yfinance: For downloading stock data from Yahoo Finance.
- pandas: For data manipulation and analysis.
- datetime: For handling date and time.
- matplotlib.pyplot: For plotting and visualization.

## Dataset Description: 
- Date: represent the date or time stamp of the data point, indicating when the data was scraped.
- Symbol: Represent the stock's symbol or ticker
- Open: The opening price of the stock at the begining of the trading day.
- High: The highest price at which the stock traded during trading day.
- Low: The lowest price at which the stock traded during the trading day.
- Close: The closing price of the stock at the end of the trading day.
- Volumne: The total number of shares traded during the trading day.

## Analysis Metrics
- Daily Return: The daily percentage change in the stock’s value.
- Cumulative Return: The total percentage change in the stock’s value over a given period, considering the compounding effect of daily returns.
- Volatility: The degree of variation in stock prices, measured using standard deviation.

## Findings
- Cumulative Returns
Tesla (TSLA): High cumulative return throughout the day.
Apple (AAPL): Moderate or average cumulative return.
Nvidia (NVDA): Negative cumulative returns over the course of the day.
- Volatility
Tesla (TSLA): Highest volatility at 0.000817.
Nvidia (NVDA): Moderate volatility at 0.000789.
Apple (AAPL): Lowest volatility at 0.000297.

## Recommendations
- For Short-term Investors/Traders:
Tesla’s high volatility offers opportunities for profit from price swings but comes with higher risk. Consider using stop-loss orders to limit potential losses.
- For Long-term Investors:
Apple and Nvidia, with their lower volatility, are more suitable for long-term investment due to more stable price movements. Consider fundamental analysis (e.g., company earnings, growth potential) alongside volatility.
- Portfolio Diversification:
Balance risk and return by including a mix of high and low volatility stocks.
Diversify across different sectors and industries to mitigate risk.

## Further Analysis
Extend the analysis period beyond one day to capture more comprehensive trends.
Perform a fundamental analysis of the companies to understand their financial health and growth prospects.

## Limitation
The scraping was done for just a day, making it difficult to calculate moving averages like MA5 or MA10.





