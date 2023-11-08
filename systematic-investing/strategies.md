---
description: Learn more about weighting strategies of Systematic Portfolio Management
cover: >-
  ../.gitbook/assets/modern-architecture-building-office-geometric-blue-2560x1440-6640.jpeg
coverY: 58.25271470878578
---

# Strategies

Our statistical algorithms can create a personalized weighting strategy, uniquely tailored to your investment goals, risk tolerance, and market outlook. This means your portfolio isn't just efficient—it's efficient for you. For example, if you have a long-term investment horizon and a high-risk tolerance, the statistical algorithm could craft a strategy that leans heavily into high-growth, high-volatility assets.

## Weighting Strategies

### **Equal**&#x20;

Equal weight is a type of proportional measuring method that gives the same importance to each stock in a portfolio or index. So stocks of the smallest companies are given equal statistical significance, or weight, to the largest companies when it comes to evaluating the overall group's performance.

The concept of equally-weighted portfolios has gained interest due to the historical performance of small-cap stocks and the emergence of several exchange-traded funds (ETFs). Standard & Poor's has developed more than 80 different equal-weight indices based on combinations of market cap, market, and sector.

Small-cap stocks are generally considered to be higher risk, higher potential return investments compared to large-caps. In theory, giving greater weight to the smaller names of the S\&P 500 in an equal-weight portfolio should increase the return potential of the portfolio. Historically, this has been the case, in the short term. From September 2020 to September 2021, the total one-year return for the S\&P 500 Equal Weight Index (EWI) was 41.93%, vs. 33.72% for the traditional S\&P 500 Index.

However, over the long term, the gap narrows—and in fact, the returns flip. The 10-year annualized total return (September 2019-September 2021) for the S\&P 500 Equal Weight Index was 15.32%, but the S\&P 500 outperformed it, returning 16.32%.

Invesco offers more than a dozen different equal-weight funds covering not only major indices such as the S\&P 500 but also many of the market's major sectors. The Invesco S\&P 500 Equal Weight ETF (RSP), for example, provides the same exposure to the smallest companies in the S\&P 500 as it does to corporate giants such as General Electric.



**Summary :** The Equal Weighting strategy equally assigns weights to each digital asset in your portfolio, thereby treating all assets with equal significance. This approach democratizes your investment portfolio and promotes diversification, mitigating the influence of any single digital asset.

### **Market Capitalization**&#x20;

The weighted average market capitalization refers to a type of stock market index construction that is based on the market capitalization of the index's constituent stocks. Large companies would, therefore, account for a greater portion of an index than smaller stocks. This means the movement of an index would depend on a small set of stocks.

The most well-known market capitalization weight index is the S\&P 500, which tracks the 500 largest assets by market capitalization. The top four holdings combine for over 10% of the entire index. These include Apple (AAPL), Microsoft (MSFT), Amazon (AMZN), and Meta, formerly Facebook, (META). The S\&P 500 is widely considered a gauge of the strength of the broader market and a benchmark for performance.

The weighted average market capitalization is determined by multiplying the current market price by the number of outstanding shares and then taking an average to determine the weighting. For example, if a company's market capitalization is $1 million, and the market capitalization of all stocks in the index is $100 million, the company would represent 1% of the index. Morningstar calculates the metric by taking a geometric mean of the market capitalization of the stocks in a fund, whereas other providers use an arithmetic mean.



**Summary :** The Market Capitalization Weighting strategy is a method of portfolio construction that involves weighting assets based on their market capitalization. Assets with higher market capitalization will have a greater weighting in the portfolio compared to assets with lower market capitalization. This strategy suits investors seeking exposure to leading market players.

### **Maximum Sharpe Ratio**&#x20;

The Sharpe ratio, named after Nobel laureate William F. Sharpe, measures the risk-adjusted performance of a portfolio. It is calculated by subtracting the risk-free rate of return from a portfolio’s expected return and dividing the result by the portfolio’s standard deviation. Thus, a higher Sharpe ratio corresponds to more attractive risk-adjusted performance, as the portfolio’s returns are higher relative to the portfolio’s risk.

In practice, while a Sharpe ratio of 1 indicates that the investment is acceptable or good for investors, a value below 1 classifies the investment as suboptimal, and values above 1 and moving towards 2 or 3 classify the investment as highly superior.

Having understood the significance of the Sharpe Ratio, let us suppose an investor wishes to make an investment in assets in such a way that the Sharpe Ratio of the portfolio would be the best possible or the maximum, that can be ensured for the investment.

**The mathematical model for the Sharpe Ratio based Portfolio Optimization is given by :**&#x20;



**Summary :** Maximizing the Sharpe ratio is an approach used in portfolio management to select assets or investments that offer the best risk-adjusted return. This strategy aims to construct a portfolio that provides the highest possible Sharpe ratio by combining assets with high returns and low volatility.

### **Minimum Volatility**&#x20;

Minimum volatility investing seeks to build a portfolio of stocks that exhibits less variability than the broad market. It aims to provide investors with a smoother ride within equity allocations by creating a portfolio that exhibits less swings, up or down, than the market.

Imagine that you’re a hiker who has two potential paths to climb a mountain. One trail is very challenging. It’s steep, rocky, and has several parts where the path has sharp descents. While the trail is exhilarating, there is also the increased risk of injury or falling. Alternatively, there is a second trail that is more gradual and stable. While this trail may be less exciting, there is a much lower chance of getting injured or hurt.

In this analogy, a minimum volatility strategy would look more like the second trail — less risky and designed to be more stable. A min vol portfolio can help investors navigate the risks of big fluctuations in the market. Just as hikers can still reach the summit of the mountain on a less challenging trail, investors can still pursue their investment goals while seeking to avoid stomach churning volatility.



**Summary :** Minimum Volatility Weighting (or minimum volatility allocation) is an approach used in finance to construct a portfolio of assets that aims to find an optimal combination of weights assigned to each asset in the portfolio in order to minimize overall volatility.

### **Efficient Return**&#x20;



**Summary :** In this solution, the goal is to maximize the portfolio's return based on a target risk value set by the investor. This is very similar to the "efficient risk" solution. The optimizer will determine the set of weights that effectively seeks to maximize the return while adhering to the provided volatility, hence the name "efficient return.&#x20;

### **Efficient Risk**&#x20;



**Summary :** This approach aims to reduce risk while adhering to a target return value determined by the investor. It is important to note that the risk value for this type of portfolio will not be minimal, unlike the minimum variance solution. However, the optimizer will determine the weights that effectively allocate risk while adhering to the target return, hence the term "efficient risk.&#x20;

### **Maximum Return – Minimum Volatility**&#x20;



**Summary :** This is often referred to as quadratic risk utility. The objective function consists of both the portfolio return and the risk. Thus, minimising the objective relates to minimising the risk and correspondingly maximising the return. The risk aversion parameter models the level of risk a user is willing to take. A higher value indicates that the investor will prioritize high defense against risk at the expense of lower returns, while a lower value places more emphasis on maximizing returns, disregarding the associated risk.&#x20;

### **Inverse Variance**&#x20;



**Summary :** For this solution, the diagonal of the covariance matrix is used for weight allocation. The weight assigned to the asset in a portfolio is the element on the main diagonal of the covariance matrix of the portfolio's elements divided by the number of elements in the portfolio.&#x20;

### **Maximum Diversification**&#x20;



**Summary :** The maximum diversification portfolio aims to allocate investments across the largest number of assets possible to achieve maximum diversification. Greater diversification within a portfolio reduces the denominator and leads to a higher diversification ratio.&#x20;

### **Maximum Decorrelation**&#x20;



**Summary :** In this solution, the objective is to minimize the correlation among the assets of a portfolio. The Maximum Decorrelation portfolio is closely related to Minimum Variance and Maximum Diversification approaches, but is applied in cases where an investor believes that all assets have similar returns and volatility but heterogeneous correlations. It is an optimization of Minimum Variance that is performed on the correlation matrix rather than the covariance matrix.&#x20;

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-04 à 16.02.37.png" alt=""><figcaption></figcaption></figure>
