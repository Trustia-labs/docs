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

**Risk Minimization** : By setting a floor for the portfolio value, investors can be assured that even in the case of unfavorable market movements, their portfolio's value will not fall below a certain level.&#x20;

**Growth Potential** : While capital protection can help minimize losses, it does not limit the potential for gain. If the risky assets in the portfolio increase in value, the portfolio will benefit from this growth. This offers a balance between security and potential for return.

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-04 à 22.04.53.png" alt=""><figcaption></figcaption></figure>

### Floor strategies

**The “Floor” is defined as :** a fraction of the current value of the portfolio that the investor cannot afford to lose. The latter therefore represents the value at which the portfolio uses 100% of its capital in dollar stablecoins.

**The “Cushion” is defined as :** the difference between the current value of the portfolio and the floor value. The latter represents the current value of the guarantee. This is therefore the maximum theoretical amount that can be lost over a period without affecting the capital guarantee.

**There are two methods for setting the floor value :**

1. **Fixed :** The floor value is defined by the value of the initial investment, less the cushion value. The value of the initial investment therefore remains 100% of the floor value, even in the event of an increase in the maximum value of the portfolio.
2. **Drawdown :** The floor value is represented by the predefined percentage, compared to the maximum value of the portfolio which is 100%. In the event of an increase in the value of the portfolio's assets, the new maximum value of the portfolio therefore becomes 100% for the predefined floor value.

**Fixed vs Drawdown :**

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-05 à 21.08.14.png" alt=""><figcaption></figcaption></figure>

### Multiplicator

The value of the multiplier depends on the investor's risk tolerance because it determines the portfolio's exposure to risky assets. The multiplier allows you to add leverage to the cushion value in order to increase returns.

For example, assume that the maximum potential loss between two rebalancing dates is 20% of the cushion value. In this case, you could use a multiplier of factor 5 to expose yourself to 100% of the cushion value, or a multiplier of factor 3 to expose yourself to 60% of the cushion value.

On the other hand, to guarantee that the value of the portfolio is greater than the floor value at the next rebalancing, the value of the multiplier must not be greater than 5.

{% hint style="warning" %}
If you use a multiplier that is too high relative to the maximum potential loss between two rebalancing dates, there is a risk that capital protection will be breached if your risky assets experience a sudden steep decline.
{% endhint %}

<figure><img src="../.gitbook/assets/Capture d’écran 2023-11-04 à 16.02.37.png" alt=""><figcaption></figcaption></figure>
