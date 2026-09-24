---
title: 'Prevailing Bisimulation Metric Learning Is Biased: Implicit Regularization and Its Remedy'
authors:
- admin
date: '2026-09-24'
publishDate: '2026-09-24T00:00:00Z'
featured: true
publication_types:
- paper-conference
publication: '*NeurIPS 2026* (Accepted)'
abstract: 'Deep bisimulation metric learning methods rely on sample-based regression objectives that suffer from a double-sampling variance bias in stochastic environments. We identify this failure mode as the Variance Trap: target variance acts as an implicit Jacobian regularizer that can drive representation collapse. We propose Bisimulation Saddle-Point Optimization (BSPO), a primal-dual framework with an auxiliary network that estimates the expected Bellman error, decoupling structural error from transition noise and enabling unbiased optimization without infeasible double sampling. Experiments on stochastic continuous and discrete control tasks and visually distracting environments show that BSPO consistently outperforms representative baselines, especially in high-noise regimes.'
tags:
- Bisimulation metrics
- Reinforcement learning
- State representation
- Primal-dual optimization
- Stochastic environments
---
