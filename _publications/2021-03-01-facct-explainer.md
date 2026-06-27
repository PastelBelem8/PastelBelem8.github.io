---
title: "How Can I Choose an Explainer? An Application-grounded Evaluation of Post-hoc Explanations"
collection: publications
category: conferences
permalink: /publication/2021-facct-explainer
date: 2021-03-01
venue: 'ACM Conference on Fairness, Accountability, and Transparency (FAccT 2021)'
paperurl: 'https://arxiv.org/abs/2101.08758'
authors: 'S. Jesus, C. Belem, V. Balayan, J. Bento, P. Saleiro, P. Bizarro, J. Gama'
abstract: |
  There have been several research works proposing new Explainable AI (XAI) methods designed to generate model explanations having specific properties, or desiderata, such as fidelity, robustness, or human-interpretability. However, explanations are seldom evaluated based on their true practical impact on decision-making tasks. Without that assessment, explanations might be chosen that, in fact, hurt the overall performance of the combined system of ML model + end-users. This study aims to bridge this gap by proposing XAI Test, an application-grounded evaluation methodology tailored to isolate the impact of providing the end-user with different levels of information. We conducted an experiment following XAI Test to evaluate three popular post-hoc explanation methods -- LIME, SHAP, and TreeInterpreter -- on a real-world fraud detection use case, with real data, a deployed ML model, and fraud analysts as subjects. Our results show that showing Data Only results in the highest decision accuracy and the slowest decision time among all variants tested. All three explainers improve accuracy over Data + Model Score but LIME was the least preferred by users, probably due to its substantially lower variability of explanations from case to case.
figure: 'https://ai2-s2-public.s3.amazonaws.com/figures/2017-08-08/a1c5af2a531c64f1c06e806d7986cd878ec3c33a/1-Figure1-1.png'
figure_caption: 'Overview of the XAI Test evaluation methodology comparing LIME, SHAP, and TreeInterpreter against baseline conditions in a fraud detection task.'
bibtex: |
  @inproceedings{jesus2021facct,
    title={How Can {I} Choose an Explainer? {An} Application-grounded Evaluation of Post-hoc Explanations},
    author={Jesus, S{\'e}rgio and Belem, Catarina G. and Balayan, Varduhi and Bento, Jo{\~a}o and Saleiro, Pedro and Bizarro, Pedro and Gama, Jo{\~a}o},
    booktitle={ACM Conference on Fairness, Accountability, and Transparency},
    year={2021}
  }
---
