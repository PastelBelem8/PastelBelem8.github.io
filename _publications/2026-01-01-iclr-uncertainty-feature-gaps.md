---
title: "Uncertainty as Feature Gaps: Epistemic Uncertainty Quantification of LLMs in Contextual Question-Answering"
collection: publications
category: conferences
permalink: /publication/2026-iclr-uncertainty-feature-gaps
date: 2026-01-15
venue: 'International Conference on Learning Representations (ICLR 2026)'
paperurl: 'https://openreview.net/forum?id=OWvvdl27CE'
authors: 'Y. F. Bakman, S. Kang, Z. Huang, D. N. Yaldiz, C. Belem, C. Zhu, A. Kumar, A. Samuel, D. Liu, S. Avestimehr, S. P. Karimireddy'
abstract: |
  Uncertainty Quantification (UQ) research has primarily focused on closed-book factual question answering (QA), while contextual QA remains unexplored, despite its importance in real-world applications. In this work, we focus on UQ for the contextual QA task and propose a theoretically grounded approach to quantify epistemic uncertainty. We begin by introducing a task-agnostic, token-level uncertainty measure defined as the cross-entropy between the predictive distribution of the given model and the unknown true distribution. By decomposing this measure, we isolate the epistemic component and approximate the true distribution by a perfectly prompted, idealized model. We then derive an upper bound for epistemic uncertainty and show that it can be interpreted as semantic feature gaps in the given model's hidden representations relative to the ideal model. We apply this generic framework to contextual QA and hypothesize that three features approximate this gap: context-reliance, context comprehension, and honesty. Using a top-down interpretability approach, we extract these features using only a small number of labeled samples and ensemble them to form a robust uncertainty score. Experiments on multiple QA benchmarks show that our method substantially outperforms state-of-the-art UQ methods, achieving up to a 13-point PRR improvement with negligible inference overhead.
bibtex: |
  @inproceedings{bakman2026iclr,
    title={Uncertainty as Feature Gaps: Epistemic Uncertainty Quantification of {LLMs} in Contextual Question-Answering},
    author={Bakman, Yosef Fridman and Kang, Sungmin and Huang, Zheng and Yaldiz, D. Nezih and Belem, Catarina G. and Zhu, Chen and Kumar, Aakriti and Samuel, Anand and Liu, Dong and Avestimehr, Salman and Karimireddy, Sai Praneeth},
    booktitle={International Conference on Learning Representations},
    year={2026}
  }
---
