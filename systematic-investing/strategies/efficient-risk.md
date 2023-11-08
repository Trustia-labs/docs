---
description: Learn more about Efficient Risk Strategy
---

# Efficient Risk

The "Efficient Risk" strategy focuses on reducing the risk of the portfolio while aiming for a set target return. It relies on an asset weight allocation that moderates risk while striving to achieve the desired return.

Imagine an architect designing a building. His goal is not only to create an aesthetically pleasing edifice but also to ensure that it withstands harsh weather and earthquakes. The target return is like the design of the building, it must be visually satisfying, while the ability to withstand extreme conditions represents risk control. The architect must, therefore, balance beauty and robustness to achieve the desired goal without compromising safety.

The Efficient Risk strategy is designed for investors who wish to minimize risk without sacrificing the expected return. It is ideal for investors who have a specific target return in mind and seek to achieve it by taking the least amount of risk possible.

**The portfolio weighting is calculated using the following formula :**&#x20;

$$\begin{align}         min  & & w^T \sum{w} \\         s.t. & & \mu^Tw = \mu_t \\              & &  \sum _{j=1} ^N w_j = 1 \\              & & w_j \geq 0, \ j = 1, \dots, N     \end{align}$$

{% hint style="info" %}
Where $$w$$ is the vector of portfolio weights, $$Σ$$ eis the covariance matrix of asset returns, $$μ$$ is the vector of expected returns, $$μt​$$ is the target return, and $$N$$ is the number of assets in the portfolio.
{% endhint %}

### **Summary**&#x20;

This approach aims to reduce risk while adhering to a target return value determined by the investor. It is important to note that the risk value for this type of portfolio will not be minimal, unlike the minimum variance solution. However, the optimizer will determine the weights that effectively allocate risk while adhering to the target return, hence the term "efficient risk.



\
