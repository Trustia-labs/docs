---
description: Tutorial for configuring a strategy
cover: >-
  .gitbook/assets/modern-architecture-building-office-geometric-blue-2560x1440-6640.jpeg
coverY: 62.41362290227048
---

# Configuration

### Weighting Strategies

Each portfolio construction strategy offers distinct benefits and advantages. Consider your investment objectives, risk tolerance, and time horizon to determine the strategy that best suits your needs. Remember, diversification is key to managing risk effectively, and these methodologies provide you with powerful tools to achieve it.

**1️⃣ - Go to the first configuration tab of a strategy (Model configuration) :**&#x20;

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-04 à 22.49.21.png" alt=""><figcaption></figcaption></figure>

**2️⃣  - Then select the strategy model that best suits you, based on your objectives, your risk tolerance and the time horizon of your investments :**&#x20;

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-04 à 22.48.52.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
[🔗 Learn more about weighting strategies](systematic-investing/strategies.md)
{% endhint %}

### Rebalancing occurrence

Over time, asset allocations may change as market performance changes asset values. Rebalancing involves the periodic purchase or sale of assets in a portfolio to return to and maintain the desired initial level of asset allocation. These levels are intended to match your risk tolerance and desire for reward.

**3️⃣ - Determine the temporality in each rebalancing :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-05 à 00.33.11.png" alt=""><figcaption></figcaption></figure>

### Capital Protection (CPPI)

The CPPI allows an investor to maintain exposure to the potential upside of risky assets while providing a capital guarantee against downside risk. To guarantee the invested capital, a position in stablecoins dollars is maintained, in addition to the basket of assets that make up the performance driver.

#### **CPPI Configuration**

* **Fixed :** The floor value is defined by the value of the initial investment, less the cushion value. The value of the initial investment therefore remains 100% of the floor value, even in the event of an increase in the maximum value of the portfolio.
* **Drawdown :** The floor value is represented by the predefined percentage, compared to the maximum value of the portfolio which is 100%. In the event of an increase in the value of the portfolio's assets, the new maximum value of the portfolio therefore becomes 100% for the predefined floor value.

**4️⃣ - If you want to use CPPI, choose a type of floor :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-05 à 00.48.11.png" alt=""><figcaption></figcaption></figure>

#### Multiplier

The multiplier allows you to add leverage to the cushion value in order to increase returns.

For example, assume that the maximum potential loss between two rebalancing dates is 20% of the cushion value. In this case, you could use a multiplier of factor 5 to expose yourself to 100% of the cushion value, or a multiplier of factor 3 to expose yourself to 60% of the cushion value.

**5️⃣ - Adapt your multiplier based on the maximum potential loss between two rebalancing dates :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 17.58.14.png" alt=""><figcaption></figcaption></figure>

{% hint style="danger" %}
If you use a multiplier that is too high relative to the maximum potential loss between two rebalancing dates, there is a risk that capital protection will be breached if your risky assets experience a sudden steep decline.
{% endhint %}

#### Floor percentage&#x20;

The “Floor” is defined as a fraction of the current value of the portfolio that the investor cannot afford to lose.

**6️⃣ - Define the percentage of your capital you want to protect :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 00.29.45.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
[🔗 Learn more about CPPI](systematic-investing/capital-protection.md)
{% endhint %}

### Trading platforms

**7️⃣ - Go to the second strategy configuration tab (Portfolio configuration) :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 18.09.40.png" alt=""><figcaption></figcaption></figure>

#### Setting amount

**7️⃣ - Set the amount you want to allocate to your strategy (in $USDT) :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 18.43.07.png" alt=""><figcaption></figcaption></figure>

#### API key

The API key is linked to your exchange platform, therefore provided by this same entity. If you have not yet added your API key to the Trustia application, go to the settings to add it to your account.

**7️⃣ - Select the API key with which you want to run your strategy :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 18.43.22.png" alt=""><figcaption></figcaption></figure>

### Asset Selection

#### Asset pool size

The asset pool represents the amount of assets that can potentially be included in your strategy.

**7️⃣ - Choose the maximum size of your asset pool :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 18.43.44.png" alt=""><figcaption></figcaption></figure>

#### Categories

When it comes to choosing digital assets for your strategy, a tool powered by statistical algorithms has the ability to examine over 800 digital assets based on their market capitalization, Sharpe ratio, minimum variance , their correlation, etc. This ensures that you only include reputable and reliable assets in your portfolio.

It is also possible to use filters to select assets based on specific activity sectors. For instance, you could select the nine assets with the best Sharpe ratio in the gaming sector, decentralized finance, and infrastructure. You can also exclude categories if you do not want to expose yourself to certain sectors.

**9️⃣ - Choose the categories you want to include and exclude to target specific sectors, but also to diversify your portfolio :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 18.10.00.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Excluded categories take precedence over included categories :** For example, if you include the "infrastructure" category and exclude the "interoperability" category, all assets with both categories as tags will be excluded from the asset pool.
{% endhint %}

#### Asset pool&#x20;

Depending on the strategy and parameters you have defined, the algorithm will build your asset pool. You can later modify the pool assets.

**9️⃣ - Once you have included and excluded your categories, click "Generate Portfolio" to build your asset pool :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 19.17.37.png" alt=""><figcaption></figcaption></figure>

After a few moments you can see your built asset pool. You can easily change the composition of your asset pool in the next step.

**9️⃣ - Then click on “Asset selection” to include or exclude assets from your pool :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 20.02.56.png" alt=""><figcaption></figcaption></figure>

Here you can see the assets that were selected by the algorithm for your asset pool. You can modify your pool by including or excluding assets, but you must select exactly the amount of assets that you previously chose for your pool. Refer to the purple bar to find your way.

If you want to change the size of your asset pool click on the “Portfolio configuration” button to go back.

**9️⃣ - You can easily remove an asset from your pool by clicking on the pre-selected asset :** &#x20;

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 20.19.54.png" alt=""><figcaption></figcaption></figure>

**9️⃣ - You can also add more to your asset pool by using the search bar or scrolling through the list of assets. Type the symbol of the asset you want in the search bar :**&#x20;

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 20.39.14.png" alt=""><figcaption></figcaption></figure>

**9️⃣ - Once you are satisfied with your asset pool click on "Backtest" to test your strategy :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 20.51.40.png" alt=""><figcaption></figcaption></figure>

### Backtest results

On the fourth tab, “Backtest results” you can analyze the different metrics of your strategy.

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 21.00.06.png" alt=""><figcaption></figcaption></figure>

**9️⃣ - Easily compare your strategies with the main cryptoassets :**

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 21.05.24.png" alt=""><figcaption></figcaption></figure>

#### Global information

Here you see the information relating to the strategy that you have just backtested. So these are all the settings you defined during the configuration step.

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 21.05.56.png" alt=""><figcaption></figcaption></figure>

#### Performance

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 22.38.03.png" alt=""><figcaption></figcaption></figure>

#### Returns

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 22.44.15.png" alt=""><figcaption></figcaption></figure>

#### Ratios

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 22.44.29.png" alt=""><figcaption></figcaption></figure>

#### Volatility

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 22.44.44.png" alt=""><figcaption></figcaption></figure>

#### Value at risk

<figure><img src=".gitbook/assets/Capture d’écran 2023-11-06 à 22.44.57.png" alt=""><figcaption></figcaption></figure>

#### Charts



Rebalancement stats

