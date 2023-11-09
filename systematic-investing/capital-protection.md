---
description: Learn more about CPPI of Systematic Portfolio Management
cover: >-
  ../.gitbook/assets/modern-architecture-building-office-geometric-blue-2560x1440-6640.jpeg
coverY: 104.61105626850937
---

# Capital Protection

### Constant Proportion Portfolio Insurance (CPPI)

The CPPI allows an investor to maintain exposure to the potential upside of risky assets while providing a capital guarantee against downside risk. To guarantee the invested capital, a position in stablecoins dollars is maintained, in addition to the basket of assets that make up the performance driver.

One part of the portfolio is invested in a low-risk asset in an income instrument and another part in risky reference assets. The balance between the two components is determined such that the final assets of the portfolio are at least equal to the guaranteed capital.

* Low risk asset&#x20;
* Risky asset&#x20;

In rising markets, the strategy allocates more to the risky asset while in the falling market, the strategy allocates more to the safe asset.

**Risk Minimization** : By setting a floor for the portfolio value, investors can be assured that even in the case of unfavorable market movements, their portfolio's value will not fall below a certain level.&#x20;

**Growth Potential** : While capital protection can help minimize losses, it does not limit the potential for gain. If the risky assets in the portfolio increase in value, the portfolio will benefit from this growth. This offers a balance between security and potential for return.

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-04 à 22.04.53.png" alt=""><figcaption></figcaption></figure>

### Floor strategies

**The “Floor” is defined as :** a fraction of the current value of the portfolio that the investor cannot afford to lose. The latter therefore represents the value at which the portfolio uses 100% of its capital in dollar stablecoins. This floor value is usually a percentage of the initial investment or a fixed dollar amount.

**The “Cushion” is defined as :** the difference between the current value of the portfolio and the floor value. The latter represents the current value of the guarantee. This is therefore the maximum theoretical amount that can be lost over a period without affecting the capital guarantee.

**There are two methods for setting the floor value :**

1. **Fixed :** The floor value is defined by the value of the initial investment, less the cushion value. The value of the initial investment therefore remains 100% of the floor value, even in the event of an increase in the maximum value of the portfolio.&#x20;
2. **Drawdown :** The floor value is represented by the predefined percentage, compared to the maximum value of the portfolio which is 100%. In the event of an increase in the value of the portfolio's assets, the new maximum value of the portfolio therefore becomes 100% for the predefined floor value.

**Fixed vs Drawdown :**

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-05 à 21.08.14.png" alt=""><figcaption></figcaption></figure>

### Multiplier

The value of the multiplier depends on the investor's risk tolerance because it determines the portfolio's exposure to risky assets. The multiplier allows you to add leverage to the cushion value in order to increase returns.

For example, assume that the maximum potential loss between two rebalancing dates is 20% of the cushion value. In this case, you could use a multiplier of factor 5 to expose yourself to 100% of the cushion value, or a multiplier of factor 3 to expose yourself to 60% of the cushion value. On the other hand, to guarantee that the value of the portfolio is greater than the floor value at the next rebalancing, the value of the multiplier must not be greater than 5.

If the value of the portfolio increases, the cushion widens, and the allocation to the risky asset increases accordingly. If the value of the portfolio decreases and approaches the floor value, the cushion is reduced, and the allocation to the risky asset decreases to protect against further losses.

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-06 à 12.51.50.png" alt=""><figcaption></figcaption></figure>

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

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-04 à 16.02.37.png" alt=""><figcaption></figcaption></figure>
