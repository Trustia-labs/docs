# Model configuration



**1️⃣ - Go to the first configuration tab of a strategy (Model configuration) :**&#x20;

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-04 à 22.49.21.png" alt=""><figcaption></figcaption></figure>

## Weighting Strategies

Over time, as a portfolio’s assets change in price it can easily move the portfolio to a position that risk and return become inconsistent with an investor’s goal and risk preferences. As some assets increase in weighting they make up a larger percentage of the portfolio; at the same time, the declining assets weighting falls and becomes a smaller percentage of the portfolio. If an investor does not rebalance the portfolio it will gradually move to high return and higher risk investments.

Portfolio rebalancing forces an investor to buy low and sell high. For example, let’s say you have a target asset allocation of 40% for asset category A and a target asset allocation of 40% for asset category B. Then let’s assume asset A increases 50% and asset B declines by 50%. Now you own 3 times as much of asset A compared to asset B because asset A has increased to 60% of the portfolio and asset B has declined to 20% of the portfolio.

After these fluctuations, not only is your asset allocation out of balance, but now you own more of an asset or category that has just risen 50% and may be overvalued, and own less of an asset or category that may be undervalued. Rebalancing allows an investor to sell overvalued assets and buy undervalue assets

**2️⃣  - Then select the strategy model that best suits you, based on your objectives, your risk tolerance and the time horizon of your investments :**&#x20;

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-04 à 22.48.52.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
[🔗 Learn more about weighting strategies](../systematic-investing/strategies.md)
{% endhint %}

## Rebalancing occurrence

Over time, asset allocations may change as market performance changes asset values. Rebalancing involves the periodic purchase or sale of assets in a portfolio to return to and maintain the desired initial level of asset allocation. These levels are intended to match your risk tolerance and desire for reward.

**3️⃣ - Determine the temporality in each rebalancing :**

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-05 à 00.33.11.png" alt=""><figcaption></figcaption></figure>

## Capital Protection (CPPI)

The CPPI allows an investor to maintain exposure to the potential upside of risky assets while providing a capital guarantee against downside risk. To guarantee the invested capital, a position in stablecoins dollars is maintained, in addition to the basket of assets that make up the performance driver.

#### **CPPI Configuration**

* **Fixed :** The floor value is defined by the value of the initial investment, less the cushion value. The value of the initial investment therefore remains 100% of the floor value, even in the event of an increase in the maximum value of the portfolio.
* **Drawdown :** The floor value is represented by the predefined percentage, compared to the maximum value of the portfolio which is 100%. In the event of an increase in the value of the portfolio's assets, the new maximum value of the portfolio therefore becomes 100% for the predefined floor value.

**4️⃣ - If you want to use CPPI, choose a type of floor :**

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-05 à 00.48.11.png" alt=""><figcaption></figcaption></figure>

#### Multiplier

The multiplier allows you to add leverage to the cushion value in order to increase returns.

For example, assume that the maximum potential loss between two rebalancing dates is 20% of the cushion value. In this case, you could use a multiplier of factor 5 to expose yourself to 100% of the cushion value, or a multiplier of factor 3 to expose yourself to 60% of the cushion value.

**5️⃣ - Adapt your multiplier based on the maximum potential loss between two rebalancing dates :**

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-06 à 17.58.14.png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
If you use a multiplier that is too high relative to the maximum potential loss between two rebalancing dates, there is a risk that capital protection will be breached if your risky assets experience a sudden steep decline.
{% endhint %}

#### Floor percentage&#x20;

The “Floor” is defined as a fraction of the current value of the portfolio that the investor cannot afford to lose.

**6️⃣ - Define the percentage of your capital you want to protect :**

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-06 à 00.29.45.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
[🔗 Learn more about CPPI](../systematic-investing/capital-protection.md)
{% endhint %}
