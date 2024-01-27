---
description: Learn more about Monte Carlo Simulations
cover: ../../.gitbook/assets/GitBook cover Trustia (3).png
coverY: 0
---

# Monte Carlo Simulations

{% embed url="https://drive.google.com/file/d/1WPMHPmoDh6xnL7C_IeHHp2yWRjep4jN2/view?usp=sharing" %}

## **Monte Carlo Simulations : A Powerful Tool for Analyzing Investment Portfolios Under Uncertain Conditions**

Monte Carlo simulations are a sophisticated mathematical modeling technique that employs random numbers to mimic intricate and unpredictable situations. This method is commonly utilized to evaluate the performance of an investment portfolio under uncertain conditions. By simulating various combinations of potential returns for each asset in the portfolio, thousands of possible outcomes can be generated. These outcomes can then be analyzed to determine the likelihood of different overall portfolio returns under varying market conditions.

#### **Geometric Brownian Motion : A Mathematical Model for Financial Asset Price Fluctuations**

Geometric Brownian motion is a mathematical model designed to depict the fluctuations of financial asset prices over time. This model is grounded in the assumption that price changes are random and adhere to a normal distribution, and that the rate of price growth is directly proportional to the price itself.

#### **Ito's Lemma : The Foundation of Geometric Brownian Motion**

At the core of the geometric Brownian motion model lies a general process known as Ito's lemma. This foundational concept serves as the basis for modeling the seemingly unpredictable behavior of financial asset prices.

By combining the power of Monte Carlo simulations with the insights provided by geometric Brownian motion and Ito's lemma, investors can gain a deeper understanding of their investment portfolios' potential performance under a wide range of market conditions. This valuable knowledge empowers them to make more informed decisions, optimize their portfolios, and better navigate the ever-changing financial landscape.

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.47.06.png" alt="Trustia logo over a city"><figcaption></figcaption></figure>

#### **Ito Process :**

$$
\Delta S = a(x, t) \Delta t + b(x, t) \Delta z
$$

And :

$$
\Delta z = \varepsilon \sqrt{\Delta t}
$$

$$
\varepsilon \to \mathcal{N}(0, 1)
$$

#### **Mouvement Brownien Géométrique:**

$$
\Delta S = \mu S \Delta t + \sigma S \Delta z
$$

In this particular case :

$$
a(x, t) = \mu S
$$

$$
b(x, t) = \sigma S
$$

$$
\Leftrightarrow \frac{\Delta S}{S} = \mu \Delta t + \sigma \Delta z
$$

The geometric Brownian motion as described above will be the mathematical basis of our simulations.

<figure><img src="../../.gitbook/assets/Capture d’écran 2023-12-19 à 18.42.18.png" alt="Trustia logo over a city"><figcaption></figcaption></figure>
