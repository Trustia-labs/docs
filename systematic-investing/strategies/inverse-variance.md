---
description: Learn more about Inverse Variance Strategy
cover: ../../.gitbook/assets/GitBook cover Trustia (3).png
coverY: 0
---

# Inverse Variance

In portfolio management, the inverse variance weighting strategy employs the covariance matrix, and more specifically its diagonal, to allocate weights to assets. This strategy aims to minimize the overall variance of the portfolio by assigning greater weight to assets with lower variances, thereby adjusting the portfolio according to the stability of each asset. It is a method that inherently leans towards a more conservative investment stance, by favoring assets that have demonstrated less fluctuation in their returns over time.

Imagine architects allocating budgets for construction projects. They first identify plots of land with the least seismic risk. On these safer plots, they invest more heavily, knowing that the risk of damage is lower. Similarly, in our strategy, assets with a lower variance, signifying less risk, are allocated a larger portion of the investment budget, reflecting increased confidence in their stable performance. This prudent approach to budget allocation in construction mirrors the inverse variance weighting in portfolio management, where investments are skewed towards assets deemed more stable and less likely to fluctuate unpredictably.

La pondération par inverse de la variance alloue les poids sur la base de l'élément diagonal de la matrice de covariance de chaque actif, qui représente sa propre variance au sein du portefeuille. Les actifs les moins volatils se voient attribuer des poids plus élevés, reflétant une plus grande confiance dans leur stabilité relative.

**The portfolio weighting is calculated using the following formula :**&#x20;

$$w_i = \frac{\sum {} ^{-1}}{\sum ^N _{j=1} (\sum_{j, j}) ^{-1}}$$

{% hint style="info" %}
Here, $$wi​$$ is the weight of the ith asset, $$σi2​$$ is the variance of the ith asset (represented by the diagonal element of the covariance matrix for the ith asset), and $$N$$ is the total number of assets in the portfolio.
{% endhint %}

### **Summary**&#x20;

For this solution, the diagonal of the covariance matrix is used for weight allocation. The weight assigned to the asset in a portfolio is the element on the main diagonal of the covariance matrix of the portfolio's elements divided by the number of elements in the portfolio.&#x20;

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.44.28.png" alt="Trustia logo over a city"><figcaption></figcaption></figure>
