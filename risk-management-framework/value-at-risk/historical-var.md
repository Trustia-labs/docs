---
description: Learn more about Historical VaR
cover: ../../.gitbook/assets/GitBook cover Trustia (3).png
coverY: 0
---

# Historical VaR

The **Historical VaR** is a method for calculating VaR that is based on the **historical returns** of a portfolio or asset. It consists of estimating the **worst-case scenario** using historical returns for the period under consideration. This method assumes that future returns will be similar to past returns and that there will be no significant changes in market conditions.

To calculate Historical VaR, one starts by sorting the historical returns of the asset or portfolio in descending order, starting from the worst return. The percentage loss corresponding to each return is then calculated, and the VaR is derived based on a given level of confidence. For example, for a 95% VaR, the expected maximum loss is the one that is in the 5th worst position in the descending order of historical returns.

Although Historical VaR is simple to calculate and does not require sophisticated mathematical models, it also has certain limitations. In particular, it may not be suitable for periods of market stress or significant changes in economic conditions because it does not take into account variations in market volatility. Moreover, it is sensitive to extreme events in the history of returns, which can lead to an overvaluation or undervaluation of VaR.

<figure><img src="../../.gitbook/assets/image (2).png" alt="The Historical VaR calculating method"><figcaption></figcaption></figure>

More info : [_Investopedia_](https://www.investopedia.com/terms/h/historical-returns.asp)

<figure><img src="../../.gitbook/assets/bgfooter.webp" alt=""><figcaption></figcaption></figure>

{% @mailchimp/mailchimpSubscribe %}
