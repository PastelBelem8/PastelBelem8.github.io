---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

A PDF version of my CV is available [here](/files/CV_CatarinaBelem.pdf).

Education
======
* Ph.D., Computer Science, University of California, Irvine, 2021–Present
  * Advisors: Sameer Singh, Padhraic Smyth
  * Expected Graduation: December 2026
* M.Sc., Computer Science and Engineering, Instituto Superior Técnico, University of Lisbon, 2016–2019
  * Thesis: *Optimization of Time-Consuming Objective Functions: Derivative-Free Approaches and their Application in Architecture*
* B.Sc., Computer Science and Engineering, Instituto Superior Técnico, University of Lisbon, 2013–2016

Research Experience
======
* **Applied Research Intern** — Capital One, New York (Jun–Sep 2025)
  * Investigated controllability and style transfer of LLMs for readable and accurate outputs.
  * Proposed and implemented a reinforcement learning customization approach (GRPO via TRL).
  * Authored 2 papers: workshop paper at EMNLP 2025 TSAR; working towards a conference paper on RL-based readability/accuracy alignment.

* **Research Intern** — Megagon Labs, Mountain View (Jun–Sep 2024)
  * Analyzed hallucinations in multi-document summarization across 5 popular LLMs.
  * Proposed a taxonomy of error types through large-scale human annotation; evaluated adversarial robustness and mitigation strategies.
  * Resulted in a publication at NAACL 2025 Findings.

* **Graduate Student Researcher** — University of California, Irvine (2021–Present)
  * Uncertainty in LLMs: Studying LLM calibration and linguistic uncertainty and its effects on human-AI decision-making and alignment with human perceptions.
  * Constrained Decoding: Proposed a method leveraging an attribute verifier's gradient to efficiently steer LM generations by reweighting the next-token distribution.
  * Fair NLP: Developed an evaluation benchmark to uncover gender bias in non-stereotypical contexts (ICLR 2024).
  * NLG Evaluation: Applied PEFT and ICL for automatic evaluation of generative LLMs with few labeled examples.

* **Research Data Scientist** — Feedzai, Lisbon, Portugal (2019–2021)
  * Algorithmic Fairness: Developed bias mitigation methods for model selection and training via constrained optimization and hyperparameter selection. Authored 2 patents and 2 top-tier papers (ICDM 2021, ICLR 2023).
  * Explainable AI: Evaluated the impact of explanations on human decision-making. Implemented concept-based explanations for fraud detection. Authored 3 patents and 3 papers (NeurIPS'20 WS, FAccT'21, ICLR'21 WS).

* **Graduate Student Researcher** — INESC-ID, Lisbon, Portugal (2017–2019)
  * Investigated gradient-free methods (genetic algorithms, ML) for multi-objective optimization of time-consuming objective functions in architectural design.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* **Programming Languages**: Python, Java, Julia
* **ML Frameworks**: PyTorch, HuggingFace Transformers, scikit-learn, Apache Spark
* **Data Analysis**: NumPy, Pandas
* **Other**: Docker, PostgreSQL, SLURM

Awards & Fellowships
======
* ICS Steckler Family Endowed Fellowship (Sep 2024 – Jun 2025)
* Fulbright Scholar (Sep 2021 – Jun 2025)
* Grace Hopper Celebration Scholarship (2022)
* CS Department Excellence Fellowship (2021)
* Maria de Lourdes Pintasilgo Award — Young Alumna (2019)
* Teaching Excellency Award (2019)

Service
======
* **2026** — Conferences: ICML (Top Reviewer), ICLR, ARR (Jan, Mar, May), NeurIPS; Journal: CHBAH
* **2025** — Conferences: ICLR, NeurIPS (Top Reviewer)
* **2024** — Conferences: CoLM, ARR (Jun, Aug Top Reviewer, Oct Top Reviewer, Dec Top Reviewer); Journal: IEEE TNNLS; Workshops: XAI @ NeurIPS, RBFM @ NeurIPS, SeT LLM @ ICLR

Community Involvement
======
* Mentored an Undergraduate Honors Thesis on measuring gender-occupation bias amplification (Sep 2023 – Jun 2024)
* Mentorship in Machine Learning to a high school student (Jun 2023 – Sep 2023)
* Jury at World Data League Competition (2021, 2022)
* Organizer and host at Deep Learning Sessions Portugal (Mar 2021 – Jun 2023)
