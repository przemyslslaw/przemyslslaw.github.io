---
title: "Responsible Artificial Intelligence"
collection: teaching
type: "COMPSCI 690F"
permalink: /teaching/2023-fall_ResponsibleAI
venue: "University of Massachusetts Amherst"
date: 2023-09-01
# location: "Amherst, USA"
---

The real-world deployment of machine learning models faces a series of lateral challenges affecting model trustworthiness, such as domain generalization, dataset shifts, causal validity, explainability, fairness, representativeness, and transparency. These challenges become increasingly important in techno-social systems affecting human high-stake decision making, which is often regulated by law. In this course, students will learn techniques for robust model evaluation, model selection, causal discovery, explainable and fair artificial intelligence, and interpretable models. In addition, students will reason about representativeness, transparency, and legal aspects of techno-social systems. The course will review both cutting-edge research and relevant portions of recent open-access textbooks. Coursework includes reading recent research papers, programming assignments, and a final group project. After completing the course, students should be able to develop, investigate, evaluate, and deploy artificial intelligence systems more responsibly.

![image](/images/rai.jpg){: .align-center width="100%" }
Image generously contributed by [Mohamed Hassan](https://pxhere.com/en/photo/1638452).

## Course Objectives
Through this course students will:
* become familiar with outstanding challenges in artificial intelligence and techno-social systems,
* gain an understanding of various ways in which machine learning can be evaluated,
* practice the usage of tools explaining black-box models,
* learn to develop models meeting various fairness criteria,
* learn to develop interpretable machine learning models,
* learn to reason about trustworthiness of techno-social systems.

## Prerequisites
There are not official prerequisites for graduate students of computer science, but the following would be useful:
- comfort with programming in Python (libraries: numpy, pandas, matplotlib, sklearn),
- comfort with introductory data science, introductory machine learning, basic statistics.

## Grading Criteria 
### Breakdown:
- Quizzes – 25%
	- Ten weekly quizzes
- Homework assignments – 35%
	- Five assignments
- Final group project – 35%
	- Proposal – 7%
	- Progress report – 14%
	- Final report and poster – 14%
- Course participation and reflection – 5%


### Scale

| F    | C      | C+     | B-     | B      | B+     | A-     | A    |
| ---- | ------ | ------ | ------ | ---- | ---- | ---- | ---- |
| <70% | 70-73% | 74-77% | 78-81% | 82-85% | 86-89% | 90-92% | >93% | 

Fractional scores will be rounded down for the purpose of establishing the final grade. 


## Quizzes and Assignments

There will be a weekly quiz. It will cover the material from most recent two lectures and corresponding readings. If you attend the classes and read the assigned texts, it should be easy for you to answer the quiz. Homework assignments will be more intense in the first half od the semester, so that you have more time to focus on the final project in the second half of the semester.

## Final Group Project

You will complete a final project on a topic and environment/dataset of your choosing. This project will be broken into three graded components: project proposal, progress report with a presentation, and final report. Students will work in groups of 3-4. Each team is expected to meet the instructor to consult their project progress individually at least twice throughout the semester. The work on final project will begin at the end of first half of the semester and last until semester's end.

## Schedule

| Class | Area                                | Topic                                                                                                                                                                                                                                                                    | Readings                  |
| ----- | ----------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------- |
| 1     | Course                              | Introduction                                                                                                                                                                                                                                                             |                           |
| 2     | Course                              | Final projects introduction                                                                                                                                                                                                                                              |                           |
| 3     | Model evaluation                    | Overparametrization, model stability and confidence, underspecification and colinearity                                                                                                                                                                                  | D'Amour et al.            |
| 4     | Model evaluation                    | Covariate shifts                                                                                                                                                                                                                                                         | Sagawa et al.             |
| 5     | Model evaluation                    | Model evaluation and selection , model calibration                                                                                                                                                                                                                       |                           |
| 6     | Model evaluation                    | Bayesian statstics and model selection/checking, structured models, mixture models                                                                                                                                                                                       |                           |
| 7     | Interpretable structured models     | Generalized linear models, mixture models, mixed effect models                                                                                                                                                                                                           |                           |
| 8     | Open-world learning                 | Open-world learning, novelty, and concept drifts                                                                                                                                                                                                                         | Lu et al.                 |
| 9     | Techno-social systems               | Heavy-tailed distributions, Pareto distribution, Simon model, Polya urn                                                                                                                                                                                                  |                           |
| 10    | Techno-social systems               | Social networks, demographic inference, non-representativeness, post-stratification                                                                                                                                                                                      | Vosoughi et al.           |
| 11    | Techno-social systems               | Disinformation and polarization, echo chambers, biases in social media, information diffusion                                                                                                                                                                            | Huszar et al.             |
| 12    | Techno-social systems               | Quality vs popularity: click models and heterogenous preferential growth model. Social media audit and differential privacy.                                                                                                                                             | Michnik et al.            |
| 13    | Course                              | Final project proposal discussions                                                                                                                                                                                                                                       |                           |
| 14    | Legal notions of fairness           | FATE. Introduction to fairness and legal perspective, demographic parity and disparate treatment                                                                                                                                                                         |                           |
| 15    | Fairness vs causality               | Business necessity. Simpson paradox, causal graphical models introduction                                                                                                                                                                                                | Barocas et al.            |
| 16    | Fairness vs causality               | From legal notions to interventional mixtures                                                                                                                                                                                                                            | Barocas et al.            |
| 17    | Fairness vs causality               | Causal vs statistical fairness notions. Algorithmic discrimination more broadly.                                                                                                                                                                                         | Obermeyer et al.          |
| 18    | Causality and explainability        | Randomized experiments, d-separation, interventions, ATE, potential outcomes notation, multi-stage marginal interventional mixture, direct and indirect effects                                                                                                          | AI Bill of Rights         |
| 19    | Counterfactual fairness             | Counterfactuals, nested counterfactuals, causal fairness, path-specific counterfactual fairness, marginal counterfactual mixture                                                                                                                                         | Athey                     |
| 20    | Statistical fairness                | Mixture of discriminating and non-discriminating individuals vs human-in-the-loop. Other fairness criteria: sufficiency and separation, recall parity, calibration. Impossiblity of achieving multiple fairness objectives. Preprocessing, postprocessing, inprocessing. | NIST Sections 3.1 and 3.2 |
| 21    | Course                              | Final project progress discussions                                                                                                                                                                                                                                       |                           |
| 22    | Explainability                      | SHAP and its variants. Feature selection vs feature relevance on the case of SHAP with different baselines                                                                                                                                                               | Rudin                     |
| 23    | Explainability and causality vs law | Other explainability measures, causation in the law                                                                                                                                                                                                                      |                           |
| 24    | Causality                           | Bayesian networks and causal discovery methods based on conditional independence and scoring functions, model selection revisited. Temporal sense of causality, Autoregressive models, Granger causality, transfer entropy                                               |                           |
| 25    | Causality                           | Inverse probability weighting, propensity score matching, augmented inverse probability weighting                                                                                                                                                                        |                           |
| 26    | Course                              | Final project presentations                                                                                                                                                                                                                                              |                           |

### Readings (subject to change)

- D’Amour, A. et al., [Underspecification Presents Challenges for Credibility in Modern Machine Learning](http://arxiv.org/abs/2011.03395), Sections 5-8 correspond to case studies – feel free to skip them, except for the one that interests you the most.
- Sagawa, S., Raghunathan, A., Koh, P. W., & Liang, P. (2020). [An Investigation of Why Overparameterization Exacerbates Spurious Correlations](http://arxiv.org/abs/2005.04345). ICML'20.
- (Optional) Gelman, A., Hwang, J., & Vehtari, A. (2013). [Understanding predictive information criteria for Bayesian models](https://doi.org/10.1007/s11222-013-9416-2). Statistics and Computing, 24(6), 997–1016.
- Lu, J., Liu, A., Dong, F., Gu, F., Gama, J., & Zhang, G. (2019). [Learning under Concept Drift: A Review.](https://arxiv.org/abs/2004.05785) IEEE Transactions on Knowledge and Data Engineering, 31(12), 2346–2363.
- (Optional) Ben Recht’s blog posts: [post 1](https://www.argmin.net/2020/06/29/tour-revisited/) and [post 2](https://www.argmin.net/2020/07/08/gain-margin)
- Vosoughi, S., Roy, D., & Aral, S. (2018). [The spread of true and false news online](https://www.science.org/doi/10.1126/science.aap9559). Science, 359(6380), 1146–1151.
- Huszár, F., Ktena, S. I., OBrien, C., Belli, L., Schlaikjer, A., & Hardt, M. (2022). [Algorithmic amplification of politics on Twitter](https://doi.org/10.1073/pnas.2025334119). Proceedings of the National Academy of Sciences of the United States of America, 119 (1), 1–6.
- Salganik, M. J., Dodds, P. S., & Watts, D. J. (2006). [Experimental study of inequality and unpredictability in an artificial cultural market](https://www.princeton.edu/~mjs3/salganik_dodds_watts06_full.pdf). _Science (New York, N.Y.)_,_311_ (5762), 854–856.
- Hofman, J. M., Sharma, A., & Watts, D. J. (2017). [Prediction and explanation in social systems](https://redirect.cs.umbc.edu/courses/graduate/691/spring21/pdf/486.full.pdf). Science, 355, (6324), 486–488.
- Solon Barocas, Moritz Hardt, & Arvind Narayanan (2019). Fairness and Machine Learning. [Chapter 2](https://fairmlbook.org/legitimacy.html) and [Chapter 6](https://fairmlbook.org/legal.html). 
- Obermeyer, Z., Powers, B., Vogeli, C., & Mullainathan, S. (2019). [Dissecting racial bias in an algorithm used to manage the health of populations](https://doi.org/10.1126/science.aax2342). Science, 366(6464), 447–453.
- White House Office of Science and Technology Policy. [Blueprint for an AI Bill of Rights](https://www.whitehouse.gov/wp-content/uploads/2022/10/Blueprint-for-an-AI-Bill-of-Rights.pdf). (2022). Sections: "Safe and Effective Systems" and "Algorithmic Discrimination Protections"
- Athey, S. (2017). [Beyond prediction: Using big data for policy problems](https://scholar.harvard.edu/files/people_analytics/files/beyond_prediction.pdf). _Science_, _355_(6324), 483–485. 
- Rudin, C. (2019). [Stop explaining black box machine learning models for high stakes decisions and use interpretable models instead](https://arxiv.org/pdf/1811.10154.pdf). _Nature Machine Intelligence_, _1_(5), 206–215.


### Textbooks (optional)
The course does not have a required textbook, but we will discuss selected papers (listed above) and some chapters or materials from these textbooks. All readings for this course are available online.

* Barocas, S., Hardt, M., & Narayanan, A. (2019). [Fairness and Machine Learning: Limitations and Opportunities](https://fairmlbook.org).
* Pearl, J., Glymour, M., & Jewell, N. P. (2016). [Causal Inference in Statistics: A Primer](https://www.datascienceassn.org/sites/default/files/CAUSAL%20INFERENCE%20IN%20STATISTICS.pdf).
* Christoph, M. (2020). [Interpretable Machine Learning A Guide for Making Black Box Models Explainable](https://christophm.github.io/interpretable-ml-book/). 
	* Chapter 9.6.
* Hardt, M., & Recht, B. (2021). [Patterns, predictions, and actions: A story about machine learning](http://arxiv.org/abs/2102.05242)
	* Chapter 8.
* Hernán, M., & Robins, J. (2020). [Causal Inference: What If](https://www.hsph.harvard.edu/miguel-hernan/causal-inference-book). 
	* Chapters 12 and 13.
* Daume, H. (2022). [A course in machine learning](http://ciml.info/). 
	* Chapter 8.

## Policies

### Attendance Policies
While in-person class attendance is not obligatory, a small percentage of the grade reflects our assessment of student participation in the course. There are many ways to participate in classes, including asking and answering questions in class, asking and answering questions online, actively participating in meetings with course staff during office hours and feedback meetings, being active during poster presentations, and writing a course reflection. 

### Extensions on Deadlines
Course staff will grant additional extensions in the case of serious and documented medical or family emergencies. We will consider other serious reasons, such as religious observances (job interviews and other schoolwork are not excuses for late homework), but students must inform course staff substantially in advance of the deadline. Apart from that, for homework assignments all students have three late days to use. After all late days have been exhausted, future delays will involve 10% score penalty for each day of delay.
### Accommodation Statement
The University of Massachusetts Amherst is committed to providing an equal educational opportunity for all students.  If you have a documented physical, psychological, or learning disability on file with Disability Services (DS), you may be eligible for reasonable academic accommodations to help you succeed in this course.  If you have a documented disability that requires an accommodation, please notify me within the first two weeks of the semester so that we may make appropriate arrangements.  For further information, please visit Disability Services ([https://www.umass.edu/disability/](https://www.umass.edu/disability/))

### The use of Large Language Models (LLMs)
The use of LLMs is discouraged. However, LLMs can be useful for a limited set of tasks, especially to non-native speakers as a more sophisticated spell-checker to improve writing. Students are asked to disclose their use of LLMs briefly in 1-2 sentences. Students are responsible for all content they produce and submit.
### Academic Honesty Statement
Since the integrity of the academic enterprise of any institution of higher education requires honesty in scholarship and research, academic honesty is required of all students at the University of Massachusetts Amherst.  Academic dishonesty is prohibited in all programs of the University.  Academic dishonesty includes but is not limited to: cheating, fabrication, plagiarism, and facilitating dishonesty.  Appropriate sanctions may be imposed on any student who has committed an act of academic dishonesty.  Instructors should take reasonable steps to address academic misconduct.  Any person who has reason to believe that a student has committed academic dishonesty should bring such information to the attention of the appropriate course instructor as soon as possible.  Instances of academic dishonesty not related to a specific course should be brought to the attention of the appropriate department Head or Chair.  Since students are expected to be familiar with this policy and the commonly accepted standards of academic integrity, ignorance of such standards is not normally sufficient evidence of lack of intent ([http://www.umass.edu/dean_students/codeofconduct/acadhonesty/](https://www.umass.edu/dean_students/codeofconduct/acadhonesty/)).
### Inclusion Policy
In this course, each voice has something of value to contribute. Please take care to respect the different experiences, beliefs, and values expressed by students and staff involved in this course. We support UMass Amherst’s commitment to diversity, and welcome individuals of all ages, backgrounds, citizenships, disability, sex, education, ethnicities, family statuses, genders, gender identities, geographical locations, languages, military experience, political views, races, religions, sexual orientations, socioeconomic statuses, and work experiences.

*The instructor reserves the right to modify this syllabus to account for current events and to better support student learning.*
