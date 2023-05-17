---
description: Learn more about Moving Average
---

# Moving Average (SMA/EMA)

{% embed url="https://drive.google.com/file/d/1hHJxbVuMi59zilAW9tYh119sDT4RjhK8/view?usp=sharing" %}

## **Simple Moving Average (SMA)**

Is a technical analysis method that involves calculating the average price of a financial asset over a given period. This helps to smooth out price fluctuations and identify short or long-term trends.

Moving averages can be used in various ways. For example, a short-term moving average (e.g. 20-day) can be used to identify short-term trends, while a long-term moving average (e.g. 200-day) can be used to identify longer-term trends.

Investors can also use moving average crossovers to identify buy or sell signals. If the short-term moving average crosses above the long-term moving average, this can be a buy signal, known as the Golden Cross, while if the short-term moving average crosses below the long-term moving average, this can be a sell signal, known as the Death Cross.

**Formula for a moving average :**

$$
MovingAverage = \frac{1}{N} \sum _{i=1} ^{N} {return_i}
$$

Note that this simplistic strategy does not allow for outperforming the market.

{% hint style="info" %}
_N_ = moving average rolling period
{% endhint %}

More info : [_Investopedia_](https://www.investopedia.com/ask/answers/071414/whats-difference-between-moving-average-and-weighted-moving-average.asp)

## **Exponential Moving Average (EMA)**

An Exponential Moving Average (EMA) is a type of moving average that gives more weight to recent data. Unlike a Simple Moving Average (SMA), which gives equal weight to all data points, the EMA places greater emphasis on the most recent data and gradually decreases the importance of older data.

The EMA is calculated by taking a weighted average of past and present data, with weighting coefficients that decrease exponentially as the data becomes older.

$$
EMA_t = \text{Closing Price}_t \times \frac{2}{n+1} + EMA_{t-1} \bigg( 1 - \frac{2}{n+1} \bigg)
$$

More info : [_Investopedia_](https://www.investopedia.com/ask/answers/071414/whats-difference-between-moving-average-and-weighted-moving-average.asp)
