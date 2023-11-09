---
description: Learn more about Maximum Decorrelation Strategy
---

# Maximum Decorrelation

The Maximum Decorrelation portfolio is one that, under a set of constraints selected by the manager, maximizes the decorrelation between assets, leading to a portfolio that offers diversification not just in terms of volatility but also in terms of the relative behavior of assets. This strategy seeks to construct a portfolio where the assets are as uncorrelated as possible, with the idea that by combining assets that do not move in tandem, the overall portfolio risk is reduced since not all assets will react in the same way to market events. It's an optimization of minimum variance carried out on the correlation matrix rather than on the covariance matrix.

Imagine a renowned chef, a specialist in fusion cuisine, who explores new culinary combinations to surprise the most discerning palates. For each recipe, he selects ingredients not only for their unique flavor but especially for their ability to harmonize with others, creating a complex and balanced taste experience. It's not just about mixing flavors, but finding the perfect combination where each flavor, without overpowering the others, brings its essential contribution to the final bouquet. Just as this chef carefully composes his dish to achieve a perfect balance, the Maximum Decorrelation strategy in portfolio management seeks to combine financial assets not on the basis of their individual performance, but for their ability to interact in a way that reduces overall correlation, thus leading to a symphony of investments more resilient to market uncertainties.

The technical approach of Maximum Decorrelation involves configuring a portfolio in such a way that the overall correlation between the assets is minimized. The process uses the correlation matrix of the portfolio's assets to determine the asset weightings. To achieve this, the portfolio manager must solve a linear optimization problem where the objective function to minimize represents the total weighted correlation of the portfolio. The constraints are that the sum of the asset weightings must equal 1, ensuring that the portfolio is fully invested, and each weighting must be non-negative, thereby excluding short positions. This method strategically allocates the capital across various assets in order to achieve a portfolio structure that is less likely to be affected by market movements in any single asset or common market factors.

**The portfolio weighting is calculated using the following formula :**&#x20;

$$\begin{align}         min  & & w^T Aw \\         s.t. & & \sum _{j=1} ^N w_j = 1 \\              & & w_j \geq 0, \ j = 1, \dots, N     \end{align}$$

{% hint style="info" %}
$$w$$ is the vector of portfolio weights, $$A$$ is the correlation matrix, which contains the Pearson correlation coefficients between the returns of all the assets in the portfolio, and $$wTAw$$ is the scalar product that quantifies the total weighted correlation of the portfolio.
{% endhint %}

### **Summary**&#x20;

In this solution, the objective is to minimize the correlation among the assets of a portfolio. The Maximum Decorrelation portfolio is closely related to Minimum Variance and Maximum Diversification approaches, but is applied in cases where an investor believes that all assets have similar returns and volatility but heterogeneous correlations. It is an optimization of Minimum Variance that is performed on the correlation matrix rather than the covariance matrix.&#x20;
