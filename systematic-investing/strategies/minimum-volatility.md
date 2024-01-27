---
description: Learn more about Minimum Volatility Strategy
cover: ../../.gitbook/assets/GitBook cover Trustia (3).png
coverY: 0
---

# Minimum Volatility

### **Minimum Volatility**&#x20;

In the pursuit of stabilizing equity allocations, the Minimum Volatility strategy stands out as a pragmatic approach. The goal is to construct a portfolio of securities that exhibit less variability compared to the overall market. This strategy aims to provide investors with a more linear experience within their equity allocations by creating a portfolio that experiences fewer fluctuations, both upwards and downwards, than the market in general.

Consider the investor as a hiker facing two paths to climb a mountain. One of the routes is arduous, with steep slopes and sharp descents, promising an exciting but risky journey. The other path, smoother and more stable, though less thrilling, offers increased safety. In this metaphor, a minimum volatility strategy is akin to this second path: less perilous, it is designed to be more consistent.

In practice, minimum volatility strategies consider the fluctuations of individual asset prices as well as their mutual interactions in order to construct a portfolio with reduced risk compared to the overall market. This approach is a segment of factor investing, which focuses on specific characteristics such as the quality and value of investments.

A minimum volatility portfolio allows investors to better navigate through significant market fluctuations. Just as hikers reach the summit via a less steep path, investors can pursue their investment goals while seeking to dodge market turbulence.

**The portfolio weighting is calculated using the following formula :**&#x20;

$$\begin{align}         min  & & w^T \sum{w} \\         s.t. & &  \sum _{j=1} ^N w_j = 1 \\              & & w_j \geq 0, \ j = 1, \dots, N     \end{align}$$

{% hint style="info" %}
where $$w$$ represents the vector of weights assigned to each asset in the portfolio, $$Σ$$ is the covariance matrix of the asset returns, and $$N$$ is the total number of assets in the portfolio.
{% endhint %}

**Summary :** Minimum Volatility Weighting (or minimum volatility allocation) is an approach used in finance to construct a portfolio of assets that aims to find an optimal combination of weights assigned to each asset in the portfolio in order to minimize overall volatility.

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.44.28.png" alt="Trustia logo over a city"><figcaption></figcaption></figure>
