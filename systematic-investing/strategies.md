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



**Summary :** The Equal Weighting strategy equally assigns weights to each digital asset in your portfolio, thereby treating all assets with equal significance. This approach democratizes your investment portfolio and promotes diversification, mitigating the influence of any single digital asset.

### **Market Capitalization**&#x20;



**Summary :** The Market Capitalization Weighting strategy is a method of portfolio construction that involves weighting assets based on their market capitalization. Assets with higher market capitalization will have a greater weighting in the portfolio compared to assets with lower market capitalization. This strategy suits investors seeking exposure to leading market players.

### **Maximum Sharpe Ratio**&#x20;

The Sharpe ratio, named after Nobel laureate William F. Sharpe, measures the risk-adjusted performance of a portfolio. It is calculated by subtracting the risk-free rate of return from a portfolio’s expected return and dividing the result by the portfolio’s standard deviation. Thus, a higher Sharpe ratio corresponds to more attractive risk-adjusted performance, as the portfolio’s returns are higher relative to the portfolio’s risk.

In practice, while a Sharpe ratio of 1 indicates that the investment is acceptable or good for investors, a value below 1 classifies the investment as suboptimal, and values above 1 and moving towards 2 or 3 classify the investment as highly superior.

Having understood the significance of the Sharpe Ratio, let us suppose an investor wishes to make an investment in assets in such a way that the Sharpe Ratio of the portfolio would be the best possible or the maximum, that can be ensured for the investment.

**The mathematical model for the Sharpe Ratio based Portfolio Optimization is given by :**&#x20;



**Summary :** Maximizing the Sharpe ratio is an approach used in portfolio management to select assets or investments that offer the best risk-adjusted return. This strategy aims to construct a portfolio that provides the highest possible Sharpe ratio by combining assets with high returns and low volatility.

### **Minimum Volatility**&#x20;



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
