---
title: "Learning-based NMPC on SoC platforms for real-time applications using parallel Lipschitz interpolation"
collection: publications
category: conferences
permalink: /publication/Conference3
excerpt: 'J.M. Nadales, A.D. Carnerero, C. Moreno-Blazquez, R.M. Haes-Ellis, D Limon'
date: 2024-02-17
venue: 'IFAC World Congress 2023'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S2405896323011631'
citation: #
---
J.M. Nadales, A.D. Carnerero, C. Moreno-Blazquez, R.M. Haes-Ellis, D Limon

One of the main problems associated with advanced control strategies is their implementation on embedded and industrial platforms, especially when the target application requires real-time operation. Frequently, the dynamics of the system are totally or partially unknown, and data-driven methods are needed to learn an approximate model of the plant to control. On many occasions, these learning techniques use non-differentiable functions that cannot be handled by most traditional low-level gradient-based optimization methods. In addition, many data-driven techniques require the online processing of a vast amount of data, which may be exceedingly time-consuming for most real-time applications. To solve these two problems at once, we propose a low-cost solution based on a system on a chip (SoC) platform featuring an embedded microprocessor (MP) and a field programmable gate array (FPGA) to implement nonlinear model predictive control strategies. The model employed to make predictions about the future evolution of the system is learnt by means of a data-driven learning method know as parallel Lipschitz interpolation (LI) and implemented in the FPGA part. On the other hand, the optimization problem associated with the model predictive control strategy is solved by software in the MP using an adapted version of the particle swarm optimization method.