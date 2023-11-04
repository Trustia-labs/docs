# Configuration

##

### Weighting Strategies

Each portfolio construction strategy offers distinct benefits and advantages. Consider your investment objectives, risk tolerance, and time horizon to determine the strategy that best suits your needs. Remember, diversification is key to managing risk effectively, and these methodologies provide you with powerful tools to achieve it.

The statistical algorithm helps you apply various strategies and determines the weighting of each asset within the index to find the approach best suited to your investment objectives :

1. **Equal Weighting :** The Equal Weighting strategy equally assigns weights to each digital asset in your portfolio, thereby treating all assets with equal significance. This approach democratizes your investment portfolio and promotes diversification, mitigating the influence of any single digital asset.
2. **Market Capitalization Weighting :** The Market Capitalization Weighting strategy is a method of portfolio construction that involves weighting assets based on their market capitalization. Assets with higher market capitalization will have a greater weighting in the portfolio compared to assets with lower market capitalization. This strategy suits investors seeking exposure to leading market players.
3. **Maximum Sharpe Ratio Weighting :** Maximizing the Sharpe ratio is an approach used in portfolio management to select assets or investments that offer the best risk-adjusted return. This strategy aims to construct a portfolio that provides the highest possible Sharpe ratio by combining assets with high returns and low volatility.
4. **Minimum Volatility Weighting :** Minimum Volatility Weighting (or minimum volatility allocation) is an approach used in finance to construct a portfolio of assets that aims to find an optimal combination of weights assigned to each asset in the portfolio in order to minimize overall volatility.
5. **Efficient Return :** In this solution, the goal is to maximize the portfolio's return based on a target risk value set by the investor. This is very similar to the "efficient risk" solution. The optimizer will determine the set of weights that effectively seeks to maximize the return while adhering to the provided volatility, hence the name "efficient return.&#x20;
6. **Efficient Risk :** This approach aims to reduce risk while adhering to a target return value determined by the investor. It is important to note that the risk value for this type of portfolio will not be minimal, unlike the minimum variance solution. However, the optimizer will determine the weights that effectively allocate risk while adhering to the target return, hence the term "efficient risk.&#x20;
7.  **Maximum Return – Minimum Volatility :** This is often referred to as quadratic risk utility. The objective function consists of both the portfolio return and the risk. Thus, minimising the objective relates to minimising the risk and correspondingly maximising the return. &#x20;

    The risk aversion parameter models the level of risk a user is willing to take. A higher value indicates that the investor will prioritize high defense against risk at the expense of lower returns, while a lower value places more emphasis on maximizing returns, disregarding the associated risk.&#x20;
8. **Inverse Variance :** For this solution, the diagonal of the covariance matrix is used for weight allocation. The weight assigned to the asset in a portfolio is the element on the main diagonal of the covariance matrix of the portfolio's elements divided by the number of elements in the portfolio.&#x20;
9. **Maximum Diversification :** The maximum diversification portfolio aims to allocate investments across the largest number of assets possible to achieve maximum diversification. Greater diversification within a portfolio reduces the denominator and leads to a higher diversification ratio.&#x20;
10. **Maximum Decorrelation :** In this solution, the objective is to minimize the correlation among the assets of a portfolio. The Maximum Decorrelation portfolio is closely related to Minimum Variance and Maximum Diversification approaches, but is applied in cases where an investor believes that all assets have similar returns and volatility but heterogeneous correlations. It is an optimization of Minimum Variance that is performed on the correlation matrix rather than the covariance matrix.&#x20;

### Asset Selection

When it comes to choosing digital assets for your strategy, a tool powered by statistical algorithms has the ability to examine over 800 digital assets based on their market capitalization, Sharpe ratio, minimum variance , their correlation, etc. This ensures that you only include reputable and reliable assets in your portfolio.

It is also possible to use filters to select assets based on specific activity sectors. For instance, you could select the nine assets with the best Sharpe ratio in the gaming sector, decentralized finance, and infrastructure. You can also exclude categories if you do not want to expose yourself to certain sectors.

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-04 à 17.30.57.png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
**Excluded categories take precedence over included categories :** For example, if you include the "infrastructure" category and exclude the "interoperability" category, all assets with both categories as tags will be excluded from the asset pool.
{% endhint %}

####

####

<figure><img src="../.gitbook/assets/baniere 2 (33) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### **Dynamic Asset Allocation**&#x20;

Our product doesn't just set and forget; it continuously analyzes market conditions to adjust your portfolio's asset allocation. This helps maintain a predefined level of risk or target a specific performance benchmark, adapting to market shifts and trends. Consider a market downturn where certain sectors are hit hard. Our dynamic asset allocation tool would adjust the weights of these underperforming assets to protect your portfolio.

{% hint style="info" %}
Over time, asset allocations can change as market performance alters the values of the assets. Rebalancing involves periodically buying or selling the assets in a portfolio to regain and maintain that original, desired level of asset allocation. Those levels are intended to match an investor's tolerance for risk and desire for reward.
{% endhint %}

#### Capital Protection

The next implementation that we will integrate into Systematic Portfolio Management is a capital protection module. We are going to use a concept known as Constant Proportion Portfolio Insurance (CPPI). The CPPI is a type of portfolio insurance in which the investor sets a floor on the percentage value of their portfolio, then structures the asset allocation around this condition.

The CPPI allows an investor to maintain exposure to the potential upside of risky assets while providing a capital guarantee against downside risk. To guarantee the invested capital, a position in dollars is maintained, in addition to the basket of assets that make up the performance driver.

1. **Risk Minimization** : By setting a floor for the portfolio value, investors can be assured that even in the case of unfavorable market movements, their portfolio's value will not fall below a certain level.&#x20;
2. **Growth Potential** : While capital protection can help minimize losses, it does not limit the potential for gain. If the risky assets in the portfolio increase in value, the portfolio will benefit from this growth. This offers a balance between security and potential for return.

{% hint style="info" %}
The value assigned to each asset depends on the "cushion value", defined as the current value of the portfolio, minus the floor value.
{% endhint %}

Our adaptation of the CPPI provides coverage for Trustia's Systematic Portfolio Management (SPM) strategies. The SPM strategies aim to eliminate human biases in investment decision making, by exploiting vast datasets for investment insights, and using sophisticated analytical techniques to transform these data into useful investment information. With the addition of our CPPI module, we can offer capital protection to our investors, adding an extra layer of security to our SPM strategies.

#### **Customized Strategy**&#x20;

Our statistical algorithms can create a personalized weighting strategy, uniquely tailored to your investment goals, risk tolerance, and market outlook. This means your portfolio isn't just efficient—it's efficient for you. For example, if you have a long-term investment horizon and a high-risk tolerance, the statistical algorithm could craft a strategy that leans heavily into high-growth, high-volatility assets.

#### Value propositions&#x20;

Our product offers a comprehensive suite of statistical algorithms powered tools for digital asset portfolio construction and management that cater to a wide range of investment strategies and goals. Alongside Dynamic Asset Allocation and Customized Strategy features, our product assures a flexible, adaptive, and bespoke approach to meet your unique investment needs. Utilizing these methodologies, you can manage risk effectively and achieve your investment objectives in the evolving digital financial landscape.
