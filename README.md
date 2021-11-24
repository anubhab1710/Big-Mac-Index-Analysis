# <p align = "center">  Correlating the Big Mac Index with the Net Hourly Wages of workers in 27 Countries </p>

<img src = "assets/Big Mac Index Poster.jpg" >

## What is the Big-Mac Index ? 🍔
***The Big Mac index*** is a survey created by The Economist magazine in 1986 to measure *Purchasing Power Parity (PPP)* between nations, using the price of a McDonald's Big Mac as the benchmark. Purchasing power parity is an economic theory which states that exchange rates over time should move in the direction of equality across national borders in the price charged for an identical basket of goods. In this case, the basket of goods is a Big Mac.  

One of the key insights of the Big Mac Index is that a basket of goods in one country can rarely be precisely duplicated in another country. For example, an American basket of groceries and a Japanese basket of groceries are likely to contain very different products. A Big Mac, though, is always a Big Mac, allowing for slight local differences in ingredients.

<img src = "/assets/img2.PNG" >

## Questions we are trying to answer ❓
* Is there a relationship between the price of a Big Mac and the net hourly wages of workers around the world? If so, how strong is the relationship? 
* Is it possible to develop a model to predict or determine the net hourly wage of a worker around the world by the price of a Big Mac hamburger in that country? If so, how good is the model? 

## ML and Statistical techniques used: ⚙
* Linear and Least Square Regression
* t-test, F-test
* Analysis of Variance (ANOVA)

## Importing the Libraries 📝
```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import statsmodels.api as sn
```

## Model Stats Summary 📊
<p align="center">
<img src = "/assets/img3.PNG" align = "center" width = "500px">
<img src = "/assets/img4.png" align = "center" width = "300px">  
</p>

## Model Correlation and Relevance 📈
Based on our regression model and hypothesis testing, we find a strong relationship between the net hourly wages of workers and the price of a Big Mac; with a correlation value of `81.33%`  
The present strength of the model is `66.2` and can be developed further since the F-Stats value is significant.

## Final Thoughts 💭
The editors of The Economist stress that the index should not be taken too seriously. "Burgernomics was never intended as a precise gauge of currency misalignment, merely a tool to make exchange-rate theory more digestible," an article on the site indicates. The GDP-adjusted index addresses the criticism that you would expect average burger prices to be cheaper in poor countries than in rich ones because labour costs are lower. PPP signals where exchange rates should be heading in the long run, as a country like China gets richer, but it says little about today's equilibrium rate. The relationship between prices and GDP per person may be a better guide to the current fair value of a currency.




*Information and Data Copyright©: Investopedia, The Economist*  
*All content rights reserved by their respectful owners. This project is only for a statistical case-study purpose*

