---
description: Tutorial for configuring a strategy
cover: ../../.gitbook/assets/GitBook cover Trustia.png
coverY: 0
---

# Strategy configurations

**1️⃣ - Go to the first configuration tab of a strategy (Strategy configurations) :**&#x20;



<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 14.51.00.png" alt=""><figcaption></figcaption></figure>

## Weighting Strategy

<details>

<summary>Weighting Strategy</summary>

Over time, as a portfolio’s assets change in price it can easily move the portfolio to a position that risk and return become inconsistent with an investor’s goal and risk preferences. As some assets increase in weighting they make up a larger percentage of the portfolio; at the same time, the declining assets weighting falls and becomes a smaller percentage of the portfolio. If an investor does not rebalance the portfolio it will gradually move to high return and higher risk investments.

Portfolio rebalancing forces an investor to buy low and sell high. For example, let’s say you have a target asset allocation of 40% for asset category A and a target asset allocation of 40% for asset category B. Then let’s assume asset A increases 50% and asset B declines by 50%. Now you own 3 times as much of asset A compared to asset B because asset A has increased to 60% of the portfolio and asset B has declined to 20% of the portfolio.

After these fluctuations, not only is your asset allocation out of balance, but now you own more of an asset or category that has just risen 50% and may be overvalued, and own less of an asset or category that may be undervalued. Rebalancing allows an investor to sell overvalued assets and buy undervalue assets

Our statistical algorithms can create a personalized weighting strategy, uniquely tailored to your investment goals, risk tolerance, and market outlook. This means your portfolio isn't just efficient—it's efficient for you. For example, if you have a long-term investment horizon and a high-risk tolerance, the statistical algorithm could craft a strategy that leans heavily into high-growth, high-volatility assets.

</details>

Over time, as a portfolio’s assets change in price it can easily move the portfolio to a position that risk and return become inconsistent with an investor’s goal and risk preferences. As some assets increase in weighting they make up a larger percentage of the portfolio; at the same time, the declining assets weighting falls and becomes a smaller percentage of the portfolio. If an investor does not rebalance the portfolio it will gradually move to high return and higher risk investments.

Portfolio rebalancing forces an investor to buy low and sell high. For example, let’s say you have a target asset allocation of 40% for asset category A and a target asset allocation of 40% for asset category B. Then let’s assume asset A increases 50% and asset B declines by 50%. Now you own 3 times as much of asset A compared to asset B because asset A has increased to 60% of the portfolio and asset B has declined to 20% of the portfolio.

After these fluctuations, not only is your asset allocation out of balance, but now you own more of an asset or category that has just risen 50% and may be overvalued, and own less of an asset or category that may be undervalued. Rebalancing allows an investor to sell overvalued assets and buy undervalue assets

Our statistical algorithms can create a personalized weighting strategy, uniquely tailored to your investment goals, risk tolerance, and market outlook. This means your portfolio isn't just efficient—it's efficient for you. For example, if you have a long-term investment horizon and a high-risk tolerance, the statistical algorithm could craft a strategy that leans heavily into high-growth, high-volatility assets.

**2️⃣  - Then select the strategy model that best suits you, based on your objectives, your risk tolerance and the time horizon of your investments :**&#x20;

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 15.21.03 (1).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
[🔗 Learn more about weighting strategies](../strategies/)
{% endhint %}

#### Max / Min Weighting

You can set the maximum or minimum weighting you want for each asset. For example, if you use a minimum weighting of 10%, each asset in your portfolio must represent at least 10% of the total portfolio value. Conversely, if you use a maximum weighting of 25% each asset in your portfolio must represent less than 25% of the total value of the portfolio.

If you do not want a minimum size set the parameter to 0% and if you do not want a maximum size set the parameter to 100%.

**3️⃣ - Choose the maximum and minimum weighting of each asset in your strategy :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 15.40.25.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
This function is not available for the strategies: Equal and market capitalization.
{% endhint %}

#### Additional parameters

**Max Return / Min Volatility :** The additional parameter represents your risk aversion between 1 and 100. The higher your risk aversion, the larger the number and the lower your aversion, the smaller the risk.

**Efficient Risk & Efficient Return :** Target return is calculated as the capital invested in a portfolio, plus the profit the investor wishes to obtain in return. The additional parameter represents the percentage of your target return on the portfolio.

**4️⃣  - Indicate your risk aversion for Max Return / Min Volatility strategies and set your target return for Efficient Risk & Efficient Return strategies**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 15.45.19.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Additional parameters are only available for the strategies: Max Return / Min Volatility, Efficient Risk and Efficient Return strategies
{% endhint %}

## Rebalancing occurrence

Over time, asset allocations may change as market performance changes asset values. Rebalancing involves the periodic purchase or sale of assets in a portfolio to return to and maintain the desired initial level of asset allocation. These levels are intended to match your risk tolerance and desire for reward.

The rebalancing occurrence defines the time period between each reallocation of portfolio assets. Too short a period between each portfolio reallocation can result in a significant cost in transaction fees on your exchange platform and therefore harm the performance of your strategy. Conversely, too long a period between each rebalancing can also negatively impact your strategy.

**5️⃣ - Determine the temporality in each rebalancing :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-11-05 à 00.33.11.png" alt=""><figcaption></figcaption></figure>

## Capital Protection (CPPI)

The CPPI allows an investor to maintain exposure to the potential upside of risky assets while providing a capital guarantee against downside risk. To guarantee the invested capital, a position in stablecoins dollars is maintained, in addition to the basket of assets that make up the performance driver.

#### **CPPI Configuration**

* **Drawdown :** The floor value is represented by the predefined percentage, compared to the maximum value of the portfolio which is 100%. In the event of an increase in the value of the portfolio's assets, the new maximum value of the portfolio therefore becomes 100% for the predefined floor value.
* **Fixed :** The floor value is defined by the value of the initial investment, less the cushion value. The value of the initial investment therefore remains 100% of the floor value, even in the event of an increase in the maximum value of the portfolio.

**6️⃣ - If you want to use CPPI, choose a type of floor :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-11-05 à 00.48.11.png" alt=""><figcaption></figcaption></figure>

#### Multiplier

The multiplier allows you to add leverage to the cushion value in order to increase returns.

For example, assume that the maximum potential loss between two rebalancing dates is 20% of the cushion value. In this case, you could use a multiplier of factor 5 to expose yourself to 100% of the cushion value, or a multiplier of factor 3 to expose yourself to 60% of the cushion value.

**7️⃣ - Adapt your multiplier based on the maximum potential loss between two rebalancing dates :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-11-06 à 17.58.14.png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
If you use a multiplier that is too high relative to the maximum potential loss between two rebalancing dates, there is a risk that capital protection will be breached if your risky assets experience a sudden steep decline.
{% endhint %}

#### Floor percentage&#x20;

The “Floor” is defined as a fraction of the current value of the portfolio that the investor cannot afford to lose.

**8️⃣ - Define the percentage of your capital you want to protect :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-11-06 à 00.29.45.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
[🔗 Learn more about CPPI](../capital-protection.md)
{% endhint %}

#### Continue

**9️⃣ - Once you have adjusted the various parameters of your strategy, click on “Portfolio Configuration” to continue :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-11-07 à 14.45.24.png" alt=""><figcaption></figcaption></figure>

