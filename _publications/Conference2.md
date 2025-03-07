---
title: "Kernel based State-Space Kriging: Application to predictive control"
collection: publications
category: conferences
permalink: /publication/Conference2
excerpt: 'A.D. Carnerero, D.R. Ramirez, T. Alamo'
date: 2022-12-15
venue: '2022 IEEE 61st Conference on Decision and Control (CDC)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9993412'
citation: #
---
A.D. Carnerero, D.R. Ramirez, T. Alamo

In this paper, we extend the State-Space Kriging (SSK) modelling technique presented in a previous work by the authors so that non autonomous systems can be considered. The SSK method computes predictions as linear combinations of past outputs. In order to model nonlinearity, we develop here a new version of the SSK where kernel functions are used to model nonlinear dynamics instead of resorting on considerations about local data, which in practice is akin to a linearization. Also, a Kalman filter is used to improve the obtained predictions at each time step in the case of noisy measurements. A constrained Nonlinear Model Predictive Control (NMPC) scheme is built upon the black-box input-output system obtained by means of the SSK prediction method. Finally, a numerical example of a continuously stirred tank reactor (CSTR) is provided in order to assess the performance of the proposed controller.