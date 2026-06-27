---
title: "What Large Language Models Know and What People Think They Know"
collection: publications
category: manuscripts
permalink: /publication/2025-nature-mi-llm-knowledge
date: 2025-01-01
venue: 'Nature Machine Intelligence'
paperurl: 'https://doi.org/10.1038/s42256-024-00976-7'
authors: 'M. Steyvers, H. Tejeda, A. Kumar, C. Belem, S. Karny, X. Hu, L. W. Mayer, P. Smyth'
abstract: |
  As artificial intelligence (AI) systems, particularly large language models (LLMs), become increasingly integrated into decision-making processes, the ability to trust their outputs is crucial. To earn human trust, LLMs must be well calibrated such that they can accurately assess and communicate the likelihood of their predictions being correct. Whereas recent work has focused on LLMs' internal confidence, less is understood about how effectively they convey uncertainty to users. Here we explore the calibration gap, which refers to the difference between human confidence in LLM-generated answers and the models' actual confidence, and the discrimination gap, which reflects how well humans and models can distinguish between correct and incorrect answers. Our experiments with multiple-choice and short-answer questions reveal that users tend to overestimate the accuracy of LLM responses when provided with default explanations. Moreover, longer explanations increased user confidence, even when the extra length did not improve answer accuracy. By adjusting LLM explanations to better reflect the models' internal confidence, both the calibration gap and the discrimination gap narrowed, significantly improving user perception of LLM accuracy.
figure: 'https://arxiv.org/html/2401.13835v2/x1.png'
figure_caption: 'Evaluation methodology: (1) prompt the LLM to obtain internal confidence; (2) generate an explanation; (3) show users the question and explanation to obtain human confidence. The calibration gap is the difference between model and human confidence.'
bibtex: |
  @article{steyvers2025nature,
    title={What Large Language Models Know and What People Think They Know},
    author={Steyvers, Mark and Tejeda, Heliodoro and Kumar, Aakriti and Belem, Catarina G. and Karny, Sherry and Hu, Xinyue and Mayer, Louis W. and Smyth, Padhraic},
    journal={Nature Machine Intelligence},
    year={2025},
    doi={10.1038/s42256-024-00976-7}
  }
---
