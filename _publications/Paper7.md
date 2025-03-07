---
title: "Kernel-Based State-Space Kriging for Predictive Control"
collection: publications
category: manuscripts
permalink: /publication/Paper7
excerpt: 'A.D. Carnerero, D.R. Ramirez, D. Limon, T. Alamo'
date: 2023-05-01
venue: 'IEEE/CAA Journal of Automatica Sinica'
slidesurl: #
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10113607'
citation: #
---

In this paper, we extend the state-space kriging (SSK) modeling technique presented in a previous work by the authors in order to consider non-autonomous systems. SSK is a data-driven method that computes predictions as linear combinations of past outputs. To model the nonlinear dynamics of the system, we propose the kernel-based state-space kriging (K-SSK), a new version of the SSK where kernel functions are used instead of resorting to considerations about the locality of the data. Also, a Kalman filter can be used to improve the predictions at each time step in the case of noisy measurements. A constrained tracking nonlinear model predictive control (NMPC) scheme using the black-box input-output model obtained by means of the K-SSK prediction method is proposed. Finally, a simulation example and a real experiment are provided in order to assess the performance of the proposed controller.