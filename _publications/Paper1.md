---
title: "Stock forecasting using local data"
collection: publications
category: manuscripts
permalink: /publication/Paper1
excerpt: 'G. Alfonso, A.D. Carnerero, D.R. Ramirez, T. Alamo'
date: 2020-12-24
venue: 'IEEE Access'
slidesurl: #
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9306750'
citation: #
---

Stock price forecasting is a relevant and challenging problem that has attracted a lot of interest from engineers and scientists. In this paper we apply two techniques for stock price and price intervals forecasting. Both techniques, derived from previous works by the authors, are based on the use of local data extracted from a database. These data are those that correspond to similar market states to the current one. The first technique uses these local data to compute a price forecast by finding an optimal combination of past states that equals the current state. The price forecast is then obtained by combining the past actual prices associated to the past market states. The second technique can be used to forecast prices but its main use is to forecast price intervals that will contain the real future price with a guaranteed probability. This is accomplished by building a probability distribution for the forecasted price and then setting the intervals by a choice of desired percentiles. Thus, this technique can be used in financial risk management. Both techniques are purely data driven and do not need a theoretical description or model of the price trend being forecasted. The proposed techniques adapt very easily to market changes because they use only the subset of the database that it is closer to the current state. Furthermore, the database can be updated as new data is available. Finally, both approaches are highly parallelizable, thus making possible to manage large data sets. As a case study, the proposed approaches have been applied to the k-step forecasting of the Dow Jones Industrial Average index. The results have been validated in relation with some baseline approaches, such as martingale and neural network predictors and quantile regression for the interval forecasting.