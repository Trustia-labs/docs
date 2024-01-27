---
description: Learn more about Maximum Return – Minimum Volatility Strategy
cover: ../../.gitbook/assets/GitBook cover Trustia (3).png
coverY: 0
---

# Maximum Return / Minimum Volatility

The "Maximum Return - Minimum Volatility" strategy aims to create a portfolio that optimally balances return and risk. This balance is not one-size-fits-all but is instead tailored according to the risk profile of each investor. At the heart of this strategy is the risk aversion parameter, a fine-tuning tool that quantifies how much risk the investor is willing to undertake. A higher parameter indicates that the investor prefers a defensive stance, accepting lower returns to minimize risk. Conversely, a lower parameter suggests a more aggressive approach, aiming for higher returns despite increased risk. Therefore, the portfolio is constructed not only based on potential returns but also in alignment with the investor's risk tolerance, which dictates the selection and weighting of assets within the portfolio.

Imagine a real estate investor looking to purchase properties. Each property presents a potential income (return) and potential challenges (risks). Some may offer high returns but require significant renovations, while others provide stable income with little maintenance. The investor's choice depends on their risk tolerance: will they favor high-yield properties with more work (risk) or those with more modest but stable returns that are easy to manage? The risk aversion parameter guides this balance, similar to how an investor adjusts their strategy to maximize income while managing risks.

The technical approach is based on balancing the pursuit of high returns with the minimization of volatility, according to the investor's risk tolerance. The risk aversion parameter adjusts the weighting based on the investor's preference for security or return.

**The portfolio weighting is calculated using the following formula :**&#x20;

$$\begin{align}         min  & & \lambda \times w^T \sum{w} - \mu^T w\\         s.t. & & \sum _{j=1} ^N w_j = 1 \\              & & w_j \geq 0, \ j = 1, \dots, N     \end{align}$$

{% hint style="info" %}
where $$λ$$ is the risk aversion parameter, $$wTΣw$$ is the portfolio variance (representing risk), and $$μTw$$ is the expected return of the portfolio.
{% endhint %}

### **Summary**&#x20;

This is often referred to as quadratic risk utility. The objective function consists of both the portfolio return and the risk. Thus, minimising the objective relates to minimising the risk and correspondingly maximising the return. The risk aversion parameter models the level of risk a user is willing to take. A higher value indicates that the investor will prioritize high defense against risk at the expense of lower returns, while a lower value places more emphasis on maximizing returns, disregarding the associated risk.&#x20;

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.44.28.png" alt="Trustia logo over a city"><figcaption></figcaption></figure>
