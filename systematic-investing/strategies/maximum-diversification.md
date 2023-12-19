---
description: Learn more about Maximum Diversification Strategy
cover: ../../.gitbook/assets/GitBook cover Trustia.png
coverY: 0
---

# Maximum Diversification

The maximum diversification strategy is centered on the formation of a portfolio that seeks to maximize the spread of investments across a wide array of assets, in order to reduce specific risk and to take advantage of diversification. This method aims to balance the portfolio by maximizing each asset's contribution to the overall diversity, while minimizing individual exposure to market fluctuations.

Consider a cautious gardener who diversifies their garden with a variety of plants, herbs, and flowers. They understand that a specific pest might devastate one particular species, but with a varied assortment, the garden as a whole continues to flourish, each plant playing a unique role in the garden's ecosystem. Similarly, a diversified portfolio can withstand market shocks affecting a specific asset, as the overall performance is supported by the variety of assets that respond differently to the same economic events.

The diversification ratio takes into account the average correlation between assets and the concentration of asset weightings in the portfolio. It is defined as the ratio of the weighted average of asset volatilities to the portfolio volatility. This formula aims to maximize the ratio of the sum of the products of weights and volatilities of the assets to the square root of the sum of the products of the weights and the covariance matrix. This reflects an allocation that increases with the decrease in the concentration of asset weights and with the decrease in the average correlation between the assets, leading to a well-diversified portfolio.

**The portfolio weighting is calculated using the following formula :**&#x20;

$$\begin{align}         max  & & D \\         s.t. & & \sum _{j=1} ^N w_j = 1 \\              & & w_j \geq 0, \ j = 1, \dots, N     \end{align}$$

{% hint style="info" %}
The diversification measure is $$D$$, $$w$$ is the vector of asset weightings, $$σ$$ is the vector of individual asset volatilities, and $$Σ$$ is the covariance matrix of the assets.
{% endhint %}

### **Summary**&#x20;

The maximum diversification portfolio aims to allocate investments across the largest number of assets possible to achieve maximum diversification. Greater diversification within a portfolio reduces the denominator and leads to a higher diversification ratio.&#x20;

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-11-04 à 16.02.37.png" alt=""><figcaption></figcaption></figure>
