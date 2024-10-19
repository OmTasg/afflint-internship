# Scenario

## Introduction

Bob is a 25-year-old young professional with a job in software development. He makes $70,000 a year and lives in Chicago. He is reasonably good at managing expenses, and after contributing to his 401(k), manages to save $500 every month.

He would like to grow his wealth and is tolerant of market ups and downs in the pursuit of that wealth. Bob has a starting capital of $10,000 and is planning on investing for the next 20 years.


## Comparisons
### High Yield Savings Account
For comparison, if Bob had put $10,000 into a high yields saving account that compounded at 3% annually, after 20 years, he would end up with $18,061 as follows:

$$A = P(1 + \frac{r}{n})^{nt}$$
$$A = 10,000 (1 + \frac{0.03}{1})^{1 * 20}$$
$$A = 18,061$$

### S&P 500
If he had put that money into S&P 500 and let that money sit for 20 years from July 2004 to July 2024, he would have $39,694.

<img src = "https://www.tradingview.com/x/hRF4p8Kb/"/>

*SPY indexed to 100*

### NASDAQ

If Bob had put the same $10,000 into the NASDAQ Index for 20 years from July 2004 to July 2024, he would have $136,240.

<img src = "https://www.tradingview.com/x/w9Ecrq0K/"/>

*QQQ indexed to 100*


| Asset Class           | Risk Level               | Return  | Max Drawdown | Sharpe Ratio (Last 10 Years) |
|-----------------------|--------------------------|---------|--------------|------------------------------|
| High Yield Savings     | Low / No Risk            | $18,061 | 0%           | ~0                            |
| S&P 500               | Moderate Risk            | $39,694 | 26%          | 0.9                           |
| NASDAQ                | High / Concentrated Risk | $136,240| 30%          | 0.76                          |


### Risk
Bob could very well invest in the NASDAQ for potentially higher returns. However, when considering risk, it’s important to recognize that NASDAQ tends to be much more volatile compared to other options. For example, during the 20-year period from March 2000 to March 2020, NASDAQ experienced significant fluctuations, including a steep decline after the dot-com bubble, which dramatically impacted returns. While NASDAQ eventually recovered, the journey was far riskier. This highlights the much higher risk associated with NASDAQ. In contrast, investing in a high-yield savings account carries almost no risk, but the returns are considerably lower, making it a safer yet less profitable option. Understanding the trade-off between risk and return is crucial when choosing what to invest in. 

### Objective
My objective is to create an investment strategy that not only beats the S&P 500 (SPY) but also does so with a lower level of risk. While the NASDAQ offers higher potential returns, it comes with substantial volatility and a lower Sharpe ratio, making it too risky for Bob's risk tolerance. The goal is to identify a strategy with a higher Sharpe ratio (ideally in the range of 2-3) to ensure that Bob can achieve better risk-adjusted returns. By prioritizing strategies that offer more stability and consistency while still outperforming SPY, Bob can grow his wealth without exposing himself to excessive market swings.


Systematic investing would be a good choice for Bob due to its structured approach, ability to manage risk, and potential to deliver consistent long-term results.

I explored these techniques:
 - Simple Moving Average Strategy
    - Description: This strategy uses two moving averages to generate buy and sell signals based on their crossovers. A buy signal occurs when a shorter-term moving average crosses above a longer-term moving average, and a sell signal occurs when the shorter-term moving average crosses below the longer-term moving average.
    - Why It Might Work: Moving averages help smooth out price data and identify trends. This strategy aims to capture long-term trends and avoid entering positions during downtrends, which can improve overall performance and reduce risk.
- Bollinger Bands Strategy
    - Description: This strategy involves buying when the price touches or falls below the lower Bollinger Band and selling when it touches or rises above the upper Bollinger Band.
    - Why It Might Work: Bollinger Bands reflect volatility and price extremes. By trading based on these extremes, the strategy attempts to capitalize on mean reversion, where prices are expected to revert to the average after reaching extreme levels, potentially leading to higher risk-adjusted returns.
- Relative Strength Index (RSI) Strategy

    - Description: This strategy uses the RSI to identify overbought and oversold conditions. Buy signals are generated when RSI crosses below a low threshold (e.g., 30), and sell signals occur when it crosses above a high threshold (e.g., 70).
    - Why It Might Work: RSI measures the speed and change of price movements, helping to identify momentum and potential reversals. By buying in oversold conditions and selling in overbought conditions, the strategy aims to benefit from price corrections and momentum shifts, improving risk-adjusted returns.



