---
title: "Promoting Fairness through Hyperparameter Optimization"
collection: publications
category: conferences
permalink: /publication/2021-icdm-fairness-hyperparameter
date: 2021-11-01
venue: 'IEEE International Conference on Data Mining (ICDM 2021)'
paperurl: 'https://arxiv.org/abs/2103.12715'
authors: 'A. F. Cruz, P. Saleiro, C. Belem, C. Soares, P. Bizarro'
abstract: |
  Considerable research effort has been guided towards algorithmic fairness but real-world adoption of bias reduction techniques is still scarce. Existing methods are either metric- or model-specific, require access to sensitive attributes at inference time, or carry high development or deployment costs. This work explores the unfairness that emerges when optimizing ML models solely for predictive performance, and how to mitigate it with a simple and easily deployed intervention: fairness-aware hyperparameter optimization (HO). We propose and evaluate fairness-aware variants of three popular HO algorithms: Fair Random Search, Fair TPE, and Fairband. We validate our approach on a real-world bank account opening fraud case-study, as well as on three datasets from the fairness literature. Results show that, without extra training cost, it is feasible to find models with 111% mean fairness increase and just 6% decrease in performance when compared with fairness-blind HO.
figure: 'https://feedzai.github.io/fair-automl/imgs/AOF/AOF_fairness_performance_selected_by_model_type.png'
figure_caption: 'Fairness-accuracy trade-off across model types (NN, Random Forest, Decision Tree, Logistic Regression, LightGBM, Exponentiated Gradient) on the AOF fraud detection dataset.'
bibtex: |
  @inproceedings{cruz2021icdm,
    title={Promoting Fairness through Hyperparameter Optimization},
    author={Cruz, Andr{\'e} F. and Saleiro, Pedro and Belem, Catarina G. and Soares, Carlos and Bizarro, Pedro},
    booktitle={IEEE International Conference on Data Mining},
    pages={1036--1041},
    year={2021}
  }
---
