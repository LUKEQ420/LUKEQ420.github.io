---
title: 'Prevailing Bisimulation Metric Learning Is Biased: Implicit Regularization and Its Remedy'
authors:
- Junqi Lu
- Ruixiang Sun
- Xin Li
- Gaopeng Peng
- Ao Zhang
- Mingzhong Wang
date: '2026-09-24'
publishDate: '2026-09-24T00:00:00Z'
featured: true
publication_types:
- paper-conference
publication: '*NeurIPS 2026* (Accepted)'
abstract: 'Deep bisimulation metric learning has emerged as a principled framework for learning robust state representations in reinforcement learning. However, prevailing methods rely on sample-based regression objectives that exhibit a critical stability flaw in stochastic environments. We identify this flaw as a manifestation of the double sampling problem: minimizing mean squared error against single-sample stochastic targets introduces an irreducible variance bias. Through the lens of stochastic differential equations, we prove that this bias leads to a Variance Trap, wherein target variance scales with encoder sensitivity and can drive representation collapse. To address this issue, we propose Bisimulation Saddle-Point Optimization (BSPO), a debiased primal-dual framework with an auxiliary network that estimates the expected Bellman error. BSPO decouples structural error from transition noise, eliminating the bias without requiring infeasible double sampling. Experiments on stochastic continuous and discrete control tasks and visually distracting environments show that BSPO significantly outperforms representative baselines, particularly in high-noise regimes.'
tags:
- Bisimulation metrics
- Reinforcement learning
- State representation
- Primal-dual optimization
- Stochastic environments
---
