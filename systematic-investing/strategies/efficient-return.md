---
description: Learn more about Efficient Return Strategy
---

# Efficient Return

The "Efficient Yield" strategy is a portfolio construction method that aims to maximize return for a predefined level of risk. It relies on the efficient frontier to identify the optimal combination of asset weights in the portfolio.

Imagine a sailing race where the objective is to sail as fast as possible while remaining within the confines of a defined wind area. Sailors are constantly adjusting their sails to capture as much wind as possible without leaving the safe zone. In this scenario, the "wind" represents return, and the "defined wind area" symbolizes the targeted risk level. The challenge is to maximize speed or return, without exceeding the acceptable risk.

According to modern portfolio theory, the efficient frontier is the foundation upon which this strategy is built. It refers to the set of portfolios offering the best return for a given level of risk. A portfolio is deemed efficient if there is no other portfolio offering a higher return for an equivalent or lower level of risk.

The efficient frontier is represented by a curve where each increase in risk translates into a relatively smaller amount of additional returns, signifying a diminishing return of risk. Portfolios located on this curve are considered optimal in terms of diversification and risk/return ratio.

In practice, an investor aims to position their portfolio on the efficient frontier, thus maximizing the expected return for a specific level of risk. The asset weights in the portfolio are adjusted accordingly to achieve this optimization objective.

**The portfolio weighting is calculated using the following formula :**&#x20;

$$\begin{align}         max  & & \mu^Tw \\         s.t. & & w^T \sum{w} = \sigma_t^2\\              & &  \sum _{j=1} ^N w_j = 1 \\              & & w_j \geq 0, \ j = 1, \dots, N     \end{align}$$

{% hint style="info" %}
where $$μ$$ is the vector of expected asset returns, $$w$$ is the portfolio weight vector, $$Σ$$ represents the covariance matrix of asset returns, $$σ2t​$$ is the target portfolio variance, and $$N$$ is the number of assets in the portfolio.
{% endhint %}

### **Summary**&#x20;

In this solution, the goal is to maximize the portfolio's return based on a target risk value set by the investor. This is very similar to the "efficient risk" solution. The optimizer will determine the set of weights that effectively seeks to maximize the return while adhering to the provided volatility, hence the name "efficient return".
