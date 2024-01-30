---
description: >-
  Explore CPPI: A strategy balancing risky and stable investments to maintain
  upside potential while protecting against downside risk with a capital
  guarantee
cover: ../.gitbook/assets/GitBook cover Trustia (3).png
coverY: 0
---

# Capital Protection

## Navigating Investment Risks with Constant Proportion Portfolio Insurance (CPPI)

Constant Proportion Portfolio Insurance (CPPI) is an innovative investment strategy designed to balance the pursuit of growth through exposure to risky assets with the assurance of capital protection against downside risk. By allocating investments between stable value assets, such as stablecoins, and a diversified array of performance-driven assets, CPPI enables investors to participate in market upsides while guarding against significant downturns.

One part of the portfolio is invested in a low-risk asset in an income instrument and another part in risky reference assets. The balance between the two components is determined such that the final assets of the portfolio are at least equal to the guaranteed capital.

* Low risk asset&#x20;
* Risky asset

&#x20;In _**bull markets**_, CPPI allocates a larger portion of the portfolio towards risky assets, aiming to maximize return. Conversely, during _**bear markets**_, the strategy increases the allocation to safer assets, thereby protecting the portfolio's value. This adaptive mechanism ensures that, regardless of market fluctuations, the investor's initial capital is shielded from erosion, embodying a proactive approach to risk minimization and growth potential enhancement.

**Risk Minimization** : By setting a floor for the portfolio value, investors can be assured that even in the case of unfavorable market movements, their portfolio's value will not fall below a certain level.&#x20;

**Growth Potential** : While capital protection can help minimize losses, it does not limit the potential for gain. If the risky assets in the portfolio increase in value, the portfolio will benefit from this growth. This offers a balance between security and potential for return.

<figure><img src="../.gitbook/assets/Capture d’écran 2023-12-19 à 18.47.06.png" alt="Trustia logo over a city"><figcaption></figcaption></figure>

### Understanding Floor and Cushion Strategies in CPPI

**The Floor:** This critical component of CPPI is defined as the minimum value the investor is willing to accept for their portfolio. This floor value acts as a safety net, dictating the shift of the entire capital into low-risk assets, like dollar stablecoins, to preserve the guaranteed capital.

**The Cushion:** The cushion, representing the difference between the portfolio's current value and the floor, serves as the buffer or excess margin available for investment in riskier assets. It quantifies the leeway for pursuing higher returns without breaching the safety floor.

### Floor Value Setting Methods: Navigating Fixed and Drawdown Options

**There are two methods for setting the floor value :**

1. **Fixed Floor Value:** Here, the floor is anchored to the value of the initial investment minus the cushion. Regardless of any increases in the portfolio's maximum value, the initial investment amount forms the immutable floor value.
2. **Drawdown Floor Value:** Contrastingly, the drawdown method adjusts the floor value as a specific percentage relative to the portfolio's highest value, allowing the floor to rise with the portfolio's peak value, ensuring a proportionate protection level throughout the investment period.

### **Fixed vs Drawdown :**

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-05 à 21.08.14.png" alt="Explained CPPI floor value"><figcaption></figcaption></figure>

<figure><img src="../.gitbook/assets/Capture d’écran 2023-12-19 à 18.44.28.png" alt="Trustia logo over a city"><figcaption></figcaption></figure>

### Optimizing Returns with Multipliers

A pivotal element of CPPI is the use of a multiplier to calibrate the portfolio's exposure to risky assets based on the cushion size. This multiplier, reflective of the investor's risk appetite, effectively leverages the cushion to augment returns from risky assets. However, **caution is advised as an excessively high multiplier relative to the maximum potential loss could compromise the capital protection mechanism, particularly if a steep decline in risky assets occurs between rebalancing dates.**

For example, assume that the maximum potential loss between two rebalancing dates is 20% of the cushion value. In this case, you could use a multiplier of factor 5 to expose yourself to 100% of the cushion value, or a multiplier of factor 3 to expose yourself to 60% of the cushion value. On the other hand, to guarantee that the value of the portfolio is greater than the floor value at the next rebalancing, the value of the multiplier must not be greater than 5.

If the value of the portfolio increases, the cushion widens, and the allocation to the risky asset increases accordingly. If the value of the portfolio decreases and approaches the floor value, the cushion is reduced, and the allocation to the risky asset decreases to protect against further losses.

**In Summary**

Constant Proportion Portfolio Insurance (CPPI) provides a nuanced framework for investors seeking to capitalize on the growth opportunities presented by risky assets while maintaining a robust defense against downside risks. Through strategic allocation between high and low-risk assets, CPPI facilitates a disciplined approach to asset management, ensuring that investments are not only geared towards maximizing returns but are also buttressed against market volatilities. With CPPI, investors can navigate the complexities of financial markets with confidence, leveraging a strategy that harmonizes growth ambitions with capital preservation imperatives.

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-06 à 12.51.50.png" alt="Multiplier explained "><figcaption></figcaption></figure>

{% hint style="danger" %}
If you use a multiplier that is too high relative to the maximum potential loss between two rebalancing dates, there is a risk that capital protection will be breached if your risky assets experience a sudden steep decline.
{% endhint %}

### Mathematical formula

**Protection Floor :** the floor value represents the minimum level of value that the investor wishes to maintain in his portfolio.

$$
\text{Protection Floor}_{value} = \text{Portfolio Value} * (1- \text{Protection Floor}_{pct})
$$

**Cushion :** excess value of the portfolio compared to the level of protection floor (floor value) defined by the investor. It represents the margin of safety or the excess margin available to the portfolio in relation to the minimum acceptable level.

$$
Cusion = \frac{\text{Portfolio Value} - \text{Floor Value}}{\text{Floor Value}}
$$

**Multiplier :** coefficient or multiplier factor used to determine the proportion of the surplus (cushion) which will be invested in the risky asset.

$$
\text{Portfolio Weighting} = Cushion \times Multiplier
$$

<figure><img src="../.gitbook/assets/bgfooter.webp" alt=""><figcaption></figcaption></figure>

{% @mailchimp/mailchimpSubscribe %}
