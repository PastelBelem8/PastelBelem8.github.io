---
title: "Are Models Biased on Text without Gender-related Language?"
collection: publications
category: conferences
permalink: /publication/2024-iclr-gender-bias
date: 2024-01-15
venue: 'International Conference on Learning Representations (ICLR 2024)'
paperurl: 'https://arxiv.org/abs/2405.00588'
authors: 'C. Belem, P. Seshadri, Y. Razeghi, S. Singh'
abstract: |
  Gender bias research has been pivotal in revealing undesirable behaviors in large language models, exposing serious gender stereotypes associated with occupations, and emotions. A key observation in prior work is that models reinforce stereotypes as a consequence of the gendered correlations that are present in the training data. In this paper, we focus on bias where the effect from training data is unclear, and instead address the question: Do language models still exhibit gender bias in non-stereotypical settings? To do so, we introduce UnStereoEval (USE), a novel framework tailored for investigating gender bias in stereotype-free scenarios. USE defines a sentence-level score based on pretraining data statistics to determine if the sentence contains minimal word-gender associations. To systematically benchmark the fairness of popular language models in stereotype-free scenarios, we utilize USE to automatically generate benchmarks without any gender-related language. Surprisingly, we find low fairness across all 28 tested models. Concretely, models demonstrate fair behavior in only 9%-41% of stereotype-free sentences, suggesting that bias does not solely stem from the presence of gender-related words.
figure: 'https://arxiv.org/html/2405.00588v1/extracted/5569457/images/camera-ready/main/figure.png'
figure_caption: 'Preferences of 28 LMs for non-stereotypical sentence pairs. Despite being grammatically and semantically correct under both masculine and feminine completions and free of words with strong gender connotations, most LMs assign more probability mass to one completion over the other.'
bibtex: |
  @inproceedings{belem2024iclr,
    title={Are Models Biased on Text without Gender-related Language?},
    author={Belem, Catarina G. and Seshadri, Shubha and Razeghi, Yasaman and Singh, Sameer},
    booktitle={International Conference on Learning Representations},
    year={2024}
  }
---
