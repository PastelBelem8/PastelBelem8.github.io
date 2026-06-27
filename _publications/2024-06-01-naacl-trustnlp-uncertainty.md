---
title: "Can LMs Interpret Verbalized Uncertainty?"
collection: publications
category: workshops
permalink: /publication/2024-naacl-trustnlp-uncertainty
date: 2024-06-01
venue: 'TrustNLP Workshop at NAACL 2024'
paperurl: 'https://arxiv.org/abs/2407.15814'
authors: 'C. Belem*, M. Kelly*, S. Singh, M. Steyvers, P. Smyth'
award: 'Runner-Up Best Short Paper'
abstract: |
  Uncertainty expressions such as "probably" or "highly unlikely" are pervasive in human language. While prior work has established that there is population-level agreement in terms of how humans quantitatively interpret these expressions, there has been little inquiry into the abilities of language models in the same context. In this paper, we investigate how language models map linguistic expressions of uncertainty to numerical responses. Our approach assesses whether language models can employ theory of mind in this setting: understanding the uncertainty of another agent about a particular statement, independently of the model's own certainty about that statement. We find that 7 out of 10 models are able to map uncertainty expressions to probabilistic responses in a human-like manner. However, we observe systematically different behavior depending on whether a statement is actually true or false. This sensitivity indicates that language models are substantially more susceptible to bias based on their prior knowledge (as compared to humans).
figure: 'https://arxiv.org/html/2407.15814v2/extracted/5982364/figures/fig1-alt.png'
figure_caption: 'Two interactions with ChatGPT concerning headline generation for passages qualified with "probable." For the climate change passage, ChatGPT generates a confident-sounding headline; for the vaccines-autism passage, it hedges — illustrating how LM prior knowledge biases uncertainty interpretation.'
bibtex: |
  @inproceedings{belem2024trustnlp,
    title={Can {LMs} Interpret Verbalized Uncertainty?},
    author={Belem, Catarina G. and Kelly, Matthew and Singh, Sameer and Steyvers, Mark and Smyth, Padhraic},
    booktitle={TrustNLP Workshop at NAACL},
    year={2024},
    note={Runner-Up Best Short Paper}
  }
---
