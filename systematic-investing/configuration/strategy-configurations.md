---
description: Tutorial for configuring a strategy
cover: ../../.gitbook/assets/GitBook cover Trustia (3).png
coverY: 0
---

# Strategy configurations

**1️⃣ - Go to the first configuration tab of a strategy (Strategy configurations) :**&#x20;

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 14.51.00.png" alt=""><figcaption></figcaption></figure>

## Weighting Strategy

<details>

<summary>Description</summary>

Over time, as a portfolio’s assets change in price it can easily move the portfolio to a position that risk and return become inconsistent with an investor’s goal and risk preferences. As some assets increase in weighting they make up a larger percentage of the portfolio; at the same time, the declining assets weighting falls and becomes a smaller percentage of the portfolio. If an investor does not rebalance the portfolio it will gradually move to high return and higher risk investments.

Portfolio rebalancing forces an investor to buy low and sell high. For example, let’s say you have a target asset allocation of 40% for asset category A and a target asset allocation of 40% for asset category B. Then let’s assume asset A increases 50% and asset B declines by 50%. Now you own 3 times as much of asset A compared to asset B because asset A has increased to 60% of the portfolio and asset B has declined to 20% of the portfolio.

After these fluctuations, not only is your asset allocation out of balance, but now you own more of an asset or category that has just risen 50% and may be overvalued, and own less of an asset or category that may be undervalued. Rebalancing allows an investor to sell overvalued assets and buy undervalue assets

Our statistical algorithms can create a personalized weighting strategy, uniquely tailored to your investment goals, risk tolerance, and market outlook. This means your portfolio isn't just efficient—it's efficient for you. For example, if you have a long-term investment horizon and a high-risk tolerance, the statistical algorithm could craft a strategy that leans heavily into high-growth, high-volatility assets.

</details>

**2️⃣  - Then select the strategy model that best suits you, based on your objectives, your risk tolerance and the time horizon of your investments :**&#x20;

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 15.21.03 (1).png" alt=""><figcaption></figcaption></figure>

{% tabs %}
{% tab title="Equal" %}
The Equal Weighting strategy equally assigns weights to each digital asset in your portfolio, thereby treating all assets with equal significance. This approach democratizes your investment portfolio and promotes diversification, mitigating the influence of any single digital asset.
{% endtab %}

{% tab title="Market Capitalization" %}
The Market Capitalization Weighting strategy is a method of portfolio construction that involves weighting assets based on their market capitalization. Assets with higher market capitalization will have a greater weighting in the portfolio compared to assets with lower market capitalization. This strategy suits investors seeking exposure to leading market players.
{% endtab %}

{% tab title="Maximum Sharpe Ratio" %}
Maximizing the Sharpe ratio is an approach used in portfolio management to select assets or investments that offer the best risk-adjusted return. This strategy aims to construct a portfolio that provides the highest possible Sharpe ratio by combining assets with high returns and low volatility.
{% endtab %}

{% tab title="Minimum Volatility" %}
Minimum Volatility Weighting (or minimum volatility allocation) is an approach used in finance to construct a portfolio of assets that aims to find an optimal combination of weights assigned to each asset in the portfolio in order to minimize overall volatility.
{% endtab %}

{% tab title="Efficient Return" %}
In this solution, the goal is to maximize the portfolio's return based on a target risk value set by the investor. This is very similar to the "efficient risk" solution. The optimizer will determine the set of weights that effectively seeks to maximize the return while adhering to the provided volatility, hence the name "efficient return.&#x20;
{% endtab %}

{% tab title="Efficient Risk" %}
This approach aims to reduce risk while adhering to a target return value determined by the investor. It is important to note that the risk value for this type of portfolio will not be minimal, unlike the minimum variance solution. However, the optimizer will determine the weights that effectively allocate risk while adhering to the target return, hence the term "efficient risk.&#x20;
{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="Maximum Return – Minimum Volatility" %}
This is often referred to as quadratic risk utility. The objective function consists of both the portfolio return and the risk. Thus, minimising the objective relates to minimising the risk and correspondingly maximising the return. &#x20;

The risk aversion parameter models the level of risk a user is willing to take. A higher value indicates that the investor will prioritize high defense against risk at the expense of lower returns, while a lower value places more emphasis on maximizing returns, disregarding the associated risk.&#x20;
{% endtab %}

{% tab title="Inverse Variance" %}
For this solution, the diagonal of the covariance matrix is used for weight allocation. The weight assigned to the asset in a portfolio is the element on the main diagonal of the covariance matrix of the portfolio's elements divided by the number of elements in the portfolio.&#x20;
{% endtab %}

{% tab title="Maximum Diversification" %}
The maximum diversification portfolio aims to allocate investments across the largest number of assets possible to achieve maximum diversification. Greater diversification within a portfolio reduces the denominator and leads to a higher diversification ratio.&#x20;
{% endtab %}

{% tab title="Maximum Decorrelation" %}
In this solution, the objective is to minimize the correlation among the assets of a portfolio. The Maximum Decorrelation portfolio is closely related to Minimum Variance and Maximum Diversification approaches, but is applied in cases where an investor believes that all assets have similar returns and volatility but heterogeneous correlations. It is an optimization of Minimum Variance that is performed on the correlation matrix rather than the covariance matrix.&#x20;
{% endtab %}
{% endtabs %}

{% hint style="info" %}
[🔗 Learn more about weighting strategies](../strategies/)
{% endhint %}

### Max / Min Weighting

You can set the maximum or minimum weighting you want for each asset. For example, if you use a minimum weighting of 10%, each asset in your portfolio must represent at least 10% of the total portfolio value. Conversely, if you use a maximum weighting of 25% each asset in your portfolio must represent less than 25% of the total value of the portfolio.

If you do not want a minimum size set the parameter to 0% and if you do not want a maximum size set the parameter to 100%.

**3️⃣ - Choose the maximum and minimum weighting of each asset in your strategy :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 15.40.25.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
This function is not available for the strategies: Equal and market capitalization.
{% endhint %}

### Additional parameters

**Max Return / Min Volatility :** The additional parameter represents your risk aversion between 1 and 100. The higher your risk aversion, the larger the number and the lower your aversion, the smaller the risk.

**Efficient Risk & Efficient Return :** Target return is calculated as the capital invested in a portfolio, plus the profit the investor wishes to obtain in return. The additional parameter represents the percentage of your target return on the portfolio.

**4️⃣  - Indicate your risk aversion for Max Return / Min Volatility strategies and set your target return for Efficient Risk & Efficient Return strategies**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 15.45.19.png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
Additional parameters are only available for the strategies: Max Return / Min Volatility, Efficient Risk and Efficient Return strategies
{% endhint %}

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.47.06.png" alt=""><figcaption></figcaption></figure>

***

## Rebalancing occurrence

<details>

<summary>Description </summary>

Over time, asset allocations may change as market performance changes asset values. Rebalancing involves the periodic purchase or sale of assets in a portfolio to return to and maintain the desired initial level of asset allocation. These levels are intended to match your risk tolerance and desire for reward.

The rebalancing occurrence defines the time period between each reallocation of portfolio assets. Too short a period between each portfolio reallocation can result in a significant cost in transaction fees on your exchange platform and therefore harm the performance of your strategy. Conversely, too long a period between each rebalancing can also negatively impact your strategy.

</details>

**5️⃣ - Determine the temporality in each rebalancing :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 16.25.32 (1).png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.47.06.png" alt=""><figcaption></figcaption></figure>

***

## Capital Protection (CPPI)

<details>

<summary>Description </summary>

The CPPI allows an investor to maintain exposure to the potential upside of risky assets while providing a capital guarantee against downside risk. To guarantee the invested capital, a position in stablecoins dollars is maintained, in addition to the basket of assets that make up the performance driver.

One part of the portfolio is invested in a low-risk asset in an income instrument and another part in risky reference assets. The balance between the two components is determined such that the final assets of the portfolio are at least equal to the guaranteed capital.

* Low risk asset&#x20;
* Risky asset&#x20;

In rising markets, the strategy allocates more to the risky asset while in the falling market, the strategy allocates more to the safe asset.

**Risk Minimization** : By setting a floor for the portfolio value, investors can be assured that even in the case of unfavorable market movements, their portfolio's value will not fall below a certain level.&#x20;

**Growth Potential** : While capital protection can help minimize losses, it does not limit the potential for gain. If the risky assets in the portfolio increase in value, the portfolio will benefit from this growth. This offers a balance between security and potential for return.

</details>

### **CPPI Configuration**

* **Drawdown :** The floor value is represented by the predefined percentage, compared to the maximum value of the portfolio which is 100%. In the event of an increase in the value of the portfolio's assets, the new maximum value of the portfolio therefore becomes 100% for the predefined floor value.
* **Fixed :** The floor value is defined by the value of the initial investment, less the cushion value. The value of the initial investment therefore remains 100% of the floor value, even in the event of an increase in the maximum value of the portfolio.

**6️⃣ - If you want to use CPPI, choose a type of floor. If you don't want to use it, click on the button at the top right :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 16.43.07.png" alt=""><figcaption></figcaption></figure>

### Floor percentage&#x20;

**The “Floor” is defined as :** a fraction of the current value of the portfolio that the investor cannot afford to lose. The latter therefore represents the value at which the portfolio uses 100% of its capital in dollar stablecoins. This floor value is usually a percentage of the initial investment or a fixed dollar amount.

**7️⃣ - Define the percentage of your capital you want to protect :**&#x20;

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 17.11.42.png" alt=""><figcaption></figcaption></figure>

### Multiplier

The multiplier allows you to add leverage to the cushion value in order to increase returns.

**The “Cushion” is defined as :** the difference between the current value of the portfolio and the floor value. The latter represents the current value of the guarantee. This is therefore the maximum theoretical amount that can be lost over a period without affecting the capital guarantee.

<details>

<summary>Description </summary>

The value of the multiplier depends on the investor's risk tolerance because it determines the portfolio's exposure to risky assets. The multiplier allows you to add leverage to the cushion value in order to increase returns.

For example, assume that the maximum potential loss between two rebalancing dates is 20% of the cushion value. In this case, you could use a multiplier of factor 5 to expose yourself to 100% of the cushion value, or a multiplier of factor 3 to expose yourself to 60% of the cushion value. On the other hand, to guarantee that the value of the portfolio is greater than the floor value at the next rebalancing, the value of the multiplier must not be greater than 5.

If the value of the portfolio increases, the cushion widens, and the allocation to the risky asset increases accordingly. If the value of the portfolio decreases and approaches the floor value, the cushion is reduced, and the allocation to the risky asset decreases to protect against further losses.

<img src="../../.gitbook/assets/Capture d’écran 2023-11-06 à 12.51.50.png" alt="" data-size="original">

</details>

**8️⃣ - Adapt your multiplier based on the maximum potential loss between two rebalancing dates :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 16.53.50.png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
If you use a multiplier that is too high relative to the maximum potential loss between two rebalancing dates, there is a risk that capital protection will be breached if your risky assets experience a sudden steep decline.
{% endhint %}

{% hint style="info" %}
[🔗 Learn more about CPPI](../capital-protection.md)
{% endhint %}

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.47.06.png" alt=""><figcaption></figcaption></figure>

***

## Trading platforms

### API key

The API key is linked to your exchange platform, therefore provided by this same entity. If you have not yet added your API key to the Trustia application, go to the settings to add it to your account.

**9️⃣ - Select the API key with which you want to run your strategy :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 17.18.21.png" alt=""><figcaption></figcaption></figure>

### Setting amount

**1️⃣0️⃣ - Set the amount you want to allocate to your strategy (in $USDT) :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 17.18.42.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.47.06.png" alt=""><figcaption></figcaption></figure>

***

## Assets

### Asset pool size

The asset pool represents the amount of assets that can potentially be included in your strategy.

**1️⃣1️⃣ - Choose the size of your asset pool :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 17.21.19.png" alt=""><figcaption></figcaption></figure>

### Categories

<details>

<summary>Description </summary>

When it comes to choosing digital assets for your strategy, a tool powered by statistical algorithms has the ability to examine over 800 digital assets based on their market capitalization, Sharpe ratio, minimum variance , their correlation, etc. This ensures that you only include reputable and reliable assets in your portfolio.

It is also possible to use filters to select assets based on specific activity sectors. For instance, you could select the nine assets with the best Sharpe ratio in the gaming sector, decentralized finance, and infrastructure. You can also exclude categories if you do not want to expose yourself to certain sectors.

</details>

**1️⃣2️⃣ - Choose the categories you want to include and exclude to target specific sectors, but also to diversify your portfolio :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 17.23.27.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Excluded categories take precedence over included categories :** For example, if you include the "infrastructure" category and exclude the "interoperability" category, all assets with both categories as tags will be excluded from the asset pool.
{% endhint %}

#### Continue

Depending on the strategy and parameters you have defined, the algorithm will build your asset pool. You can later modify the pool assets. After a few moments you can see your built asset pool. You can easily change the composition of your asset pool in the next step.

**1️⃣3️⃣ - Once you have adjusted the various parameters of your strategy, then click on “Asset selection” to include or exclude assets from your pool :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 17.27.40.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.47.06.png" alt=""><figcaption></figcaption></figure>

***

### Assets selection

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.00.27.png" alt=""><figcaption></figcaption></figure>

Here you can see the assets that were selected by the algorithm for your asset pool. You can modify your pool by including or excluding assets, but you must select exactly the amount of assets that you previously chose for your pool. Refer to the purple bar to find your way.

**1️⃣4️⃣ - You can easily remove an asset from your pool by clicking on the pre-selected asset :** &#x20;

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.03.27.png" alt=""><figcaption></figcaption></figure>

**1️⃣5️⃣ - You can also add more to your asset pool by using the search bar or scrolling through the list of assets. Type the symbol of the asset you want in the search bar :**&#x20;

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.06.17.png" alt=""><figcaption></figcaption></figure>

#### Continue

**1️⃣6️⃣ - Once you are satisfied with your asset pool click on "Backtest" to test your strategy :**

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.10.44.png" alt=""><figcaption></figcaption></figure>
