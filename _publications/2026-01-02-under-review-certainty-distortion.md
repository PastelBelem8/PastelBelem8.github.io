---
title: "From 'May' to 'Is': Certainty Distortion in Language Model Rewriting"
collection: publications
category: under_review
permalink: /publication/2026-certainty-distortion
date: 2026-01-01
venue: 'Under review'
paperurl: 'https://arxiv.org/abs/2606.07951'
authors: 'C. Belem, S. Wu, H. Yao, M. Steyvers, S. Singh, P. Smyth'
abstract: |
  Humans increasingly turn to Language Models in ways that shape beliefs and drive decisions, including discussing, rewriting, and summarizing information from scientific articles, news, and medical reports. However, in these domains, where how confidently a claim is expressed matters, little is known about whether LMs faithfully preserve it. In this work, we investigate certainty distortion in LMs, defined as meaningful changes in expressed certainty when semantic content is preserved. We propose an LM-based evaluation metric that is consistent with population-level judgments of certainty. Using this metric, we characterize certainty distortion across different sizes and families of models in the context of scientific and medical communication tasks. Our results show that certainty distortion affects up to 75% of LM outputs and is systematically asymmetric: most LMs are 1.5-2x more likely to increase expressed certainty than to decrease it. These effects can compound over repeated paraphrasing. Prompt-based interventions reduce overall certainty distortion but do not eliminate it, revealing a general bias toward inflating expressed certainty with direct implications for users who rely on LMs in high-stakes domains.
figure: 'https://arxiv.org/html/2606.07951/figures/figure1.png'
figure_caption: 'A real example of certainty inflation: a model paraphrases a hedged radiology impression into a confident clinical attribution, shifting the reader from a tentative diagnostic to a definite conclusion.'
bibtex: |
  @article{belem2026certainty,
    title={From `{May}' to `{Is}': Certainty Distortion in Language Model Rewriting},
    author={Belem, Catarina G. and Wu, Steven and Yao, Hao and Steyvers, Mark and Singh, Sameer and Smyth, Padhraic},
    year={2026},
    note={Under review}
  }
---
