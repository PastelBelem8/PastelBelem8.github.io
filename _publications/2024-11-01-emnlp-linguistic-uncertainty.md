---
title: "Perceptions of Linguistic Uncertainty by Language Models and Humans"
collection: publications
category: conferences
permalink: /publication/2024-emnlp-linguistic-uncertainty
date: 2024-11-01
venue: 'Empirical Methods in Natural Language Processing (EMNLP 2024)'
paperurl: 'https://aclanthology.org/2024.emnlp-main.483/'
authors: 'C. Belem*, M. Kelly*, S. Singh, M. Steyvers, P. Smyth'
abstract: |
  Uncertainty expressions such as "probably" or "highly unlikely" are pervasive in human language. While prior work has established that there is population-level agreement in terms of how humans quantitatively interpret these expressions, there has been little inquiry into the abilities of language models in the same context. In this paper, we investigate how language models map linguistic expressions of uncertainty to numerical responses. Our approach assesses whether language models can employ theory of mind in this setting: understanding the uncertainty of another agent about a particular statement, independently of the model's own certainty about that statement. We find that 7 out of 10 models are able to map uncertainty expressions to probabilistic responses in a human-like manner. However, we observe systematically different behavior depending on whether a statement is actually true or false. This sensitivity indicates that language models are substantially more susceptible to bias based on their prior knowledge (as compared to humans). These findings raise important questions and have broad implications for human-AI and AI-AI communication.
figure: 'https://arxiv.org/html/2407.15814v2/extracted/5982364/figures/fig1-alt.png'
figure_caption: 'Two interactions with ChatGPT concerning headline generation for passages qualified with "probable." LM responses differ depending on whether the topic aligns with or contradicts its prior knowledge — illustrating systematic bias in linguistic uncertainty interpretation.'
bibtex: |
  @inproceedings{belem2024emnlp,
    title={Perceptions of Linguistic Uncertainty by Language Models and Humans},
    author={Belem, Catarina G. and Kelly, Matthew and Singh, Sameer and Steyvers, Mark and Smyth, Padhraic},
    booktitle={Proceedings of the Conference on Empirical Methods in Natural Language Processing},
    pages={8467--8502},
    year={2024}
  }
---
