---
title: "FairGBM: Gradient Boosting with Fairness Constraints"
collection: publications
category: conferences
permalink: /publication/2023-iclr-fairgbm
date: 2023-01-15
venue: 'International Conference on Learning Representations (ICLR 2023)'
paperurl: 'https://arxiv.org/abs/2209.07850'
authors: 'A. F. Cruz, C. Belem, J. Bravo, P. Saleiro, P. Bizarro'
abstract: |
  Machine Learning (ML) algorithms based on gradient boosted decision trees (GBDT) are still favored on many tabular data tasks across various mission critical applications, from healthcare to finance. However, GBDT algorithms are not free of the risk of bias and discriminatory decision-making. Despite GBDT's popularity and the rapid pace of research in fair ML, existing in-processing fair ML methods are either inapplicable to GBDT, incur in significant train time overhead, or are inadequate for problems with high class imbalance. We present FairGBM, a learning framework for training GBDT under fairness constraints with little to no impact on predictive performance when compared to unconstrained LightGBM. Since common fairness metrics are non-differentiable, we employ a proxy-Lagrangian formulation using smooth convex error rate proxies to enable gradient-based optimization. Additionally, our open-source implementation shows an order of magnitude speedup in training time when compared with related work, a pivotal aspect to foster the widespread adoption of FairGBM by real-world practitioners.
bibtex: |
  @inproceedings{cruz2023iclr,
    title={{FairGBM}: Gradient Boosting with Fairness Constraints},
    author={Cruz, Andr{\'e} F. and Belem, Catarina G. and Bravo, Joao and Saleiro, Pedro and Bizarro, Pedro},
    booktitle={International Conference on Learning Representations},
    year={2023}
  }
---
