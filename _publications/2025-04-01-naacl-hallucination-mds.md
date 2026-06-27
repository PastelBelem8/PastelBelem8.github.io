---
title: "From Single to Multi: How LLMs Hallucinate in Multi-Document Summarization"
collection: publications
category: conferences
permalink: /publication/2025-naacl-hallucination-mds
date: 2025-04-01
venue: 'Findings of the Annual Conference of the North American Chapter of the ACL (NAACL 2025)'
paperurl: 'https://arxiv.org/abs/2410.13961'
authors: 'C. Belem, P. Pezeshkpour, H. Iso, S. Maekawa, N. Bhutani, E. Hruschka'
abstract: |
  Although many studies have investigated and reduced hallucinations in large language models (LLMs) for single-document tasks, research on hallucination in multi-document summarization (MDS) tasks remains largely unexplored. We create two novel benchmarks to investigate how hallucinations manifest when LLMs summarize topic-specific information across multiple documents. Our findings reveal that up to 75% of the content in LLM-generated summaries is hallucinated, with hallucinations more likely to occur towards the end of the summaries. When tasked with summarizing non-existent information, GPT-3.5-turbo and GPT-4o generated summaries approximately 79% and 44% of the time respectively. We identify that most errors stem from either failing to follow instructions or producing overly generic insights. While simple post-hoc baselines show only moderate effectiveness in reducing hallucinations, our work underscores the necessity for more systematic mitigation approaches in multi-document summarization tasks.
figure: 'https://arxiv.org/html/2410.13961/extracted/6390835/main/figures/motivation4.png'
figure_caption: 'An illustrative example of hallucination in multi-document summarization: the LLM summarizes information not shared across documents, raising concerns about trustworthiness in MDS settings.'
bibtex: |
  @inproceedings{belem2025naacl,
    title={From Single to Multi: How {LLMs} Hallucinate in Multi-Document Summarization},
    author={Belem, Catarina G. and Pezeshkpour, Pouya and Iso, Hayate and Maekawa, Seiji and Bhutani, Nikita and Hruschka, Estevam},
    booktitle={Findings of the Annual Conference of the North American Chapter of the Association for Computational Linguistics},
    year={2025}
  }
---
