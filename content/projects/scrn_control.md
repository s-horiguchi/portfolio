---
title: "Optimal Control of Stochastic Reaction Networks"
date: "2025-09-05T12:41:05-05:00"
image: "/img/reaction_control.png"
link: ""
description: "What is the best strategy to control a biological population?"
tags: ["control theory", "reaction network"]
fact: ""
featured: true
sitemap:
    priority: 0.8
---

### What is the best strategy to control a biological population?

Compared with the conventional settings such as Linear-Quadratic-Gaussian (LQG) in control theory, the optimal control problems of stochastic reaction networks (SRNs) is quite different in the following sense:

1. Nonlinearity due to many-body interactions
2. Discrete state space and Poissonian randomness
3. Nonnegativity constraints on the state and the control input
4. Absorbing boundaries (e.g., extinction of a species)

We found a trick to efficiently solve optimal control problems for SRNs. Consideration of the control cost function was a key to success. If the control cost function is carefully designed with information theoretic quantities, i.e., Kullback–Leibler divergence, the optimal control problems can be reduced to efficiently solvable linear equations. This trick applies to any SRNs with any objective function.


#### For details, see the following paper:

Shuhei A. Horiguchi, Tetsuya J. Kobayashi. Optimal Control of Stochastic Reaction Networks with Entropic Control Cost and Emergence of Mode-Switching Strategies. _PRX Life_ **3**, 033027

https://journals.aps.org/prxlife/abstract/10.1103/zttn-tpzq


You can also watch my talk from the 2nd Workshop on Biological Systems on YouTube:

{{< youtube bza-myjPvpM >}}
