---
title: "Responsible Artificial Intelligence"
collection: teaching
type: "Graduate course"
permalink: /teaching/2022-fall_ResponsibleAI
venue: "University of Massachusetts Amherst"
date: 2022-09-01
# location: "Amherst, USA"
---

The real-world deployment of machine learning models faces a series of lateral challenges affecting model trustworthiness, such as domain generalization, dataset shifts, causal validity, explainability, fairness, representativeness, and transparency. These challenges become increasingly important in techno-social systems affecting human high-stake decision making, which is often regulated by law. In this course, students will learn techniques for robust model evaluation, model selection, causal discovery, explainable and fair artificial intelligence, and interpretable models. In addition, students will reason about representativeness, transparency, and legal aspects of techno-social systems. The course will review both cutting-edge research and relevant portions of recent open-access textbooks. Coursework includes reading recent research papers, programming assignments, and a final group project. After completing the course, students should be able to develop, investigate, evaluate, and deploy artificial intelligence systems more responsibly.

## Prerequisites
There are not official prerequisites, but the following would be useful:
* comfort with programming in Python,
* comfort with introductory data science, introductory machine learning, basic statistics.

## Learning Objectives
Through this course students will:
* become familiar with outstanding challenges in artificial intelligence,
* gain an understanding of various ways in which machine learning can be evaluated,
* practice the usage of tools explaining black-box models,
* learn to develop models meeting various fairness criteria,
* learn to develop interpretable machine learning models,
* learn to reason about trustworthiness of techno-social systems.


## Textbooks
The course does not have a required textbook, but we will follow selected chapters from multiple textbooks. All readings for this course are available online.

Textbooks:
* Barocas, S., Hardt, M., & Narayanan, A. (2019). [Fairness and Machine Learning: Limitations and Opportunities](https://fairmlbook.org).
* Pearl, J., Glymour, M., & Jewell, N. P. (2016). [Causal Inference in Statistics: A Primer](https://www.datascienceassn.org/sites/default/files/CAUSAL%20INFERENCE%20IN%20STATISTICS.pdf).
* Christoph, M. (2020). [Interpretable Machine Learning A Guide for Making Black Box Models Explainable](https://christophm.github.io/interpretable-ml-book/).
	* Chapter 9.6.
* Hardt, M., & Recht, B. (2021). [Patterns, predictions, and actions: A story about machine learning](http://arxiv.org/abs/2102.05242).
	* Chapter 8.
* Hernán, M., & Robins, J. (2020). [Causal Inference: What If](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book).
	* Chapters 12 and 13.
* Daume, H. (2022). [A course in machine learning](http://ciml.info/).
	* Chapter 8.

<br><br>

## Schedule
1. Introduction

* Area: model evaluation, stability, uncertainty, calibration, resilience
2. Uncertainty in labels, inter-labeler agreement, model evaluation, accuracy and f1 vs measures correcting for chance, inter-rater agreement measures
3. Model and parameter uncertainty, overparametrization, co-linearity, model stability
4. Dataset shifts and model resilience
5. Dataset shift as a novelty, causal representation learning, model uncertainty vs novelty detection and active learning, model uncertainty vs model selection, model uncertainty vs calibration

* Area: causality
6. Causal graphical models, d-separation, interventions, potential outcomes notation
7. Counterfactuals, nested counterfactuals
8. Inverse probability weighting, propensity score matching, doubly robust estimators, augmented inverse probability weighting
9. Causal discovery, bayes nets: conditional independence and score-based, model selection, information criteria

* Area: explainability
10. Direct and indirect effects
11. Shap variants
12. Other explainability measures, causation in the law

* Area: fairness
13. Introduction to fairness and legal perspective, standard supervised learning, demographic parity and disparate treatment
14. Other statistical fairness criteria: sufficiency and separation
15. Causal fairness, path-specific counterfactual fairness
16. Interventional mixtures
17. Resilience to discrimination
18. From interventional mixtures to impact parity, other fairness measures
19. Feedback-loops vs fairness

* Area: interpretable structured models and representativeness in techno-social systems
20. Heavy-tail distributions, heterogeneity, agent-based simulations
21. Generalized linear models, mixed effect models
22. Mixture models

* Area: transparency, representativeness, and privacy in techno-social systems
23. Disinformation and polarization, echo chambers, biases in social media, opaqueness
24. Demographic inference, non-representativeness, and post-stratification models
25. Differential privacy
26. Final project presentations

## Grading
##### Breakdown:
* Weekly quizes – 10%
* Homework assignments – 45%
* Final group project – 40%
* Course reflection – 5%


##### Scale

| F    | C      | C+     | B-     | B      | B+     | A-     | A    |
| ---- | ------ | ------ | ------ | ------ | ------ | ------ | ---- |
| <70% | 70-73% | 74-77% | 78-81% | 82-85% | 86-89% | 90-92% | >93% |



