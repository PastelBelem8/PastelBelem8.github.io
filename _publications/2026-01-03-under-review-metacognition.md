---
title: "Improving Metacognition and Uncertainty Communication in Language Models"
collection: publications
category: under_review
permalink: /publication/2026-metacognition-uncertainty
date: 2026-01-02
venue: 'Under review'
paperurl: 'https://arxiv.org/abs/2510.05126'
authors: 'M. Steyvers, C. Belem, P. Smyth'
abstract: |
  Large language models are increasingly used in settings where confident but incorrect answers can mislead users. Reliable uncertainty communication requires a form of metacognition: monitoring when one's own answers are likely to be correct. We examine whether supervised fine-tuning improves this capability and test its transferability across domains. The study involves fine-tuning two models on general knowledge, mathematics, and trivia using two evaluation methods: single-question confidence estimation and pairwise confidence comparison. Performance is assessed on both training domains and new medical, legal, and truthfulness benchmarks. Results demonstrate that fine-tuning enhances alignment between stated confidence and actual accuracy. However, gains from single-task training do not reliably transfer between different confidence estimation approaches. Multitask fine-tuning proved more effective for broader generalization across models and tasks. While uncertainty communication in large language models is trainable, transfer between metacognitive tasks remains limited, and joint training on multiple confidence tasks may be necessary for more comprehensive generalization.
figure: 'https://arxiv.org/html/2510.05126v3/Figure1.png'
figure_caption: 'Two metacognitive tasks: in single-question confidence, the LLM provides a verbalized numeric confidence score with its answer; in pairwise confidence comparison, the LLM selects the question for which it is more confident before answering.'
bibtex: |
  @article{steyvers2026metacognition,
    title={Improving Metacognition and Uncertainty Communication in Language Models},
    author={Steyvers, Mark and Belem, Catarina G. and Smyth, Padhraic},
    year={2026},
    note={Under review}
  }
---
