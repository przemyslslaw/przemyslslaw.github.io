---
title: "Responsible Artificial Intelligence"
collection: teaching
type: "COMPSCI 690F/490F"
permalink: /teaching/2022-fall_ResponsibleAI
venue: "University of Massachusetts Amherst"
date: 2022-09-01
# location: "Amherst, USA"
---

The real-world deployment of machine learning models faces a series of lateral challenges affecting model trustworthiness, such as domain generalization, dataset shifts, causal validity, explainability, fairness, representativeness, and transparency. These challenges become increasingly important in techno-social systems affecting human high-stake decision making, which is often regulated by law. In this course, students will learn techniques for robust model evaluation, model selection, causal discovery, explainable and fair artificial intelligence, and interpretable models. In addition, students will reason about representativeness, transparency, and legal aspects of techno-social systems. The course will review both cutting-edge research and relevant portions of recent open-access textbooks. Coursework includes reading recent research papers, programming assignments, and a final group project. After completing the course, students should be able to develop, investigate, evaluate, and deploy artificial intelligence systems more responsibly.

## Learning Objectives
Through this course students will:
* become familiar with outstanding challenges in artificial intelligence and techno-social systems,
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

## Grading
##### Breakdown:
* Quizzes – 10%
* Homework assignments – 45%
* Final group project – 40%
	* Project proposal - 10%
	* Final report - 30%
* Course reflection – 5%

##### Scale

| F    | D | D+ | C- | C      | C+     | B-     | B      | B+     | A-     | A    |
| ---- | ------ | ------ | ------ | ------ | ------ | ------ | ---- | ---- | ---- | ---- |
| <58% | 58-61% | 62-65% | 66-69% | 70-73% | 74-77% | 78-81% | 82-85% | 86-89% | 90-92% | >93% |

Fractional scores will be rounded down for the purpose of establishing the final grade.
The scale for graduate students ends at C, so graduate students with scores of less than 70% will yield an F.

## Differences between 490F and 690F
##### Prerequisites for 490F
Undergraduate students are required to have the following background: COMPSCI 348 or 383 or 389 with a grade C or better, COMPSCI 240 or STAT 240 or STAT 515 with C or better, MATH 233 and MATH 235 with C or better, and good programming skills in Python (libraries: numpy, pandas, matplotlib, sklearn). The number of available seats may be limited and preference will be given to seniors.

##### Prerequisites for 690F
There are not official prerequisites for graduate students of computer science, but the following would be useful:
* comfort with programming in Python,
* comfort with introductory data science, introductory machine learning, basic statistics.

##### Expectations and Workload
Students enrolled in 690F will have an expanded set of expectations and higher workload in comparison to students enrolled in 490F:
- Quizzes and homework assignments will include extra graduate-level questions and problems that will not be required from 490F students. These extra questions will be optional for 490F students and will not negatively impact their grades, i.e., they may impact their grades only positively.
- Final group project.
	- Projects pursued by teams composed of only 490F students will be less challenging and will result in final reports that are comparable to field reports. Students of 490F will be encouraged to select a project from a prepared list and their project proposals will be expected to be modest in comparison to projects of 690F students.
	- Projects pursued by teams composed of only 690F students will be expected to have a wider scope and a larger depth, such that they result in more developed project proposals and final reports comparable to workshop submissions.
	- Mixed teams, including both 690F and 490F students, are permitted after instructor's explicit approval under the following conditions: i) that the workload is non-overlapping and clearly separated between the 490F and 690F members of such team, ii) that this separation is clearly described in the project proposal, iii) expectations and workload per student are lower for 490F than for 690F members of the team, iv) and the team agrees for the possibility that the final project is graded separately for 490F and 690F members of the team. For instance, 490F students could focus on a literature review or data preprocessing within a project, while 690F students could focus on model development and analysis. Overall, mixed groups will be expected to deliver reports that have scope, depth, and length in between the above two extremes, in proportion to the number of 490F and 690F students on a team.
- Graduate section meetings. At most a couple of meetings will discuss course concepts, derivations, research projects, or course readings specifically designed for 690F students. These meetings may include quizzes for 690F students that will not be counted towards the grade of 490F students.

##### Overrides
Undergraduate students who want to participate in and get credit for 690F instead of 490F are encouraged to request an [override](https://www.cics.umass.edu/ugrad-education/overrides). Such students shall meet the above undergraduate prerequisites for 490F *with grades B+ or higher*.

As the course has interdisciplinary parts, toward statistics and behavioral sciences, graduate students from other departments may enroll by requesting an [override](https://www.cics.umass.edu/ugrad-education/overrides). Prerequisites for non-CS graduate students appear on SPIRE.


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
9. Bayesian networks and causal discovery methods based on conditional independence and scoring functions, model selection, information criteria.

* Area: explainability
10. Direct and indirect effects
11. SHAP and its variants
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

## Policies
### Accommodation Statement
The University of Massachusetts Amherst is committed to providing an equal educational opportunity for all students.  If you have a documented physical, psychological, or learning disability on file with Disability Services (DS), you may be eligible for reasonable academic accommodations to help you succeed in this course.  If you have a documented disability that requires an accommodation, please notify me within the first two weeks of the semester so that we may make appropriate arrangements.  For further information, please visit Disability Services ([https://www.umass.edu/disability/](https://www.umass.edu/disability/))

### Academic Honesty Statement
Since the integrity of the academic enterprise of any institution of higher education requires honesty in scholarship and research, academic honesty is required of all students at the University of Massachusetts Amherst.  Academic dishonesty is prohibited in all programs of the University.  Academic dishonesty includes but is not limited to: cheating, fabrication, plagiarism, and facilitating dishonesty.  Appropriate sanctions may be imposed on any student who has committed an act of academic dishonesty.  Instructors should take reasonable steps to address academic misconduct.  Any person who has reason to believe that a student has committed academic dishonesty should bring such information to the attention of the appropriate course instructor as soon as possible.  Instances of academic dishonesty not related to a specific course should be brought to the attention of the appropriate department Head or Chair.  Since students are expected to be familiar with this policy and the commonly accepted standards of academic integrity, ignorance of such standards is not normally sufficient evidence of lack of intent ([http://www.umass.edu/dean_students/codeofconduct/acadhonesty/](https://www.umass.edu/dean_students/codeofconduct/acadhonesty/)).

### Inclusion Policy
In this course, each voice has something of value to contribute. Please take care to respect the different experiences, beliefs, and values expressed by students and staff involved in this course. We support UMass Amherst’s commitment to diversity, and welcome individuals of all ages, backgrounds, citizenships, disability, sex, education, ethnicities, family statuses, genders, gender identities, geographical locations, languages, military experience, political views, races, religions, sexual orientations, socioeconomic statuses, and work experiences.

*The instructor reserves the right to modify this syllabus to account for current events and to better support student learning.*
