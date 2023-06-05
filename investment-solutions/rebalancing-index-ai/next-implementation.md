---
cover: ../../.gitbook/assets/baniere 2 (33) (3).png
coverY: 0
---

# Next Implementation

## Capital Protection

The next implementation that we will integrate into Systematic Portfolio Management is a capital protection module. We are going to use a concept known as Constant Proportion Portfolio Insurance (CPPI). The CPPI is a type of portfolio insurance in which the investor sets a floor on the dollar value of their portfolio, then structures the asset allocation around this condition.

The CPPI allows an investor to maintain exposure to the potential upside of risky assets while providing a capital guarantee against downside risk. To guarantee the invested capital, a position in dollars is maintained, in addition to the basket of assets that make up the performance driver.

1. **Risk Minimization** : By setting a floor for the portfolio value, investors can be assured that even in the case of unfavorable market movements, their portfolio's value will not fall below a certain level.&#x20;
2. **Growth Potential** : While capital protection can help minimize losses, it does not limit the potential for gain. If the risky assets in the portfolio increase in value, the portfolio will benefit from this growth. This offers a balance between security and potential for return.

{% hint style="info" %}
The value assigned to each asset depends on the "cushion value", defined as the current value of the portfolio, minus the floor value.
{% endhint %}

Our adaptation of the CPPI provides coverage for Trustia's Systematic Portfolio Management (SPM) strategies. The SPM strategies aim to eliminate human biases in investment decision making, by exploiting vast datasets for investment insights, and using sophisticated analytical techniques to transform these data into useful investment information. With the addition of our CPPI module, we can offer capital protection to our investors, adding an extra layer of security to our SPM strategies.
