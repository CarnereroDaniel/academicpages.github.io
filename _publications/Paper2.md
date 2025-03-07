---
title: "Receding Horizon Optimization of Large Trade Orders"
collection: publications
category: manuscripts
permalink: /publication/Paper2
excerpt: 'G. Alfonso, A.D. Carnerero, D.R. Ramirez, T. Alamo'
date: 2021-04-26
venue: 'IEEE Access'
slidesurl: #
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9416441'
citation: #
---

The optimal execution of stock trades is a relevant and interesting problem as it is key in maximizing profits and reducing risks when investing in the stock market. In the case of large orders, the problem becomes even more complex as the impact of the order in the market has to be taken into account. The usual solution is to split large orders into a set of smaller suborders that must be executed within a prescribed time window. This leads to the problem of deciding when in the time window execute each suborder. There are popular ways of executing the trading of these split orders like those which try to track the “Time Weighted Average Price” and the “Volume Weighted Average Price”, usually called TWAP and VWAP orders. This paper presents a strategy to optimize the splitting of large trade orders over a given time window. The strategy is based on the solution of an optimization problem that is applied following a receding horizon approach. This approach reduces the impact of prediction errors due to the uncertain market dynamics, by using new values of the price time series as they are available as time goes on. Suborder size constraints are taken into account in both market and limit orders. The strategy relies on price and traded volume forecast but it is independent of the prediction technique used. The performance index weighs not only the financial cost of the suborders, but also the impact on the market and the forecasting accuracy. A tailored optimization algorithm is proposed for efficiently solving the corresponding optimization problem. Most of the computations of the algorithm can be parallelized. Finally, the proposed approach has been tested through a case study composed by stocks of the Chinese A-share market.