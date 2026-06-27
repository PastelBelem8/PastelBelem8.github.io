---
title: "Semantic Probabilistic Control of Language Models"
collection: publications
category: workshops
permalink: /publication/2025-neurips-spigm-semantic-control
date: 2025-12-01
venue: "NeurIPS 2025 Workshop on Structured Probabilistic Inference and Generative Modeling (SPIGM)"
paperurl: 'https://arxiv.org/abs/2505.01954'
authors: 'K. Ahmed*, C. Belem*, P. Smyth, S. Singh'
abstract: |
  Semantic control entails steering LM generations towards satisfying subtle non-lexical constraints, e.g., toxicity, sentiment, or politeness, attributes that can be captured by a sequence-level verifier. It can thus be viewed as sampling from the LM distribution conditioned on the target attribute, a computationally intractable problem due to the non-decomposable nature of the verifier. Existing approaches to LM control either only deal with syntactic constraints which cannot capture the aforementioned attributes, or rely on sampling to explore the conditional LM distribution, an ineffective estimator for low-probability events. In this work, we leverage a verifier's gradient information to efficiently reason over all generations that satisfy the target attribute, enabling precise steering of LM generations by reweighing the next-token distribution. Starting from an initial sample, we create a local LM distribution favoring semantically similar sentences, enabling tractable computation of an expected sentence embedding. We use this expected embedding, informed by the verifier's evaluation at the initial sample, to estimate the probability of satisfying the constraint, which directly informs the update to the next-token distribution. We evaluated the effectiveness of our approach in controlling the toxicity, sentiment, and topic-adherence of LMs, yielding generations satisfying the constraint with high probability (>95%) without degrading their quality.
bibtex: |
  @inproceedings{ahmed2025spigm,
    title={Semantic Probabilistic Control of Language Models},
    author={Ahmed, Kareem and Belem, Catarina G. and Smyth, Padhraic and Singh, Sameer},
    booktitle={NeurIPS Workshop on Structured Probabilistic Inference and Generative Modeling},
    year={2025}
  }
---
