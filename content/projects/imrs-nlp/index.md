+++
title = "IMRS: Production Multi-Label NLP for Incident Narratives"
date = "2023-05-01"
+++

End-to-end NLP system replacing manual labeling of correctional incident free text with automated multi-label prediction across facilities.
<!--more-->

**Role:** Technical lead / product owner (BIOS program)
**Partners:** [Recidiviz](https://recidiviz.org); Council of State Governments

**Highlights:**
- 73 binary incident-type labels across 110,928 labeled incidents from 24-table relational export
- One-vs-rest `MultiOutputClassifier` with logistic regression; ongoing SVM experimentation (+~5 F1)
- k-fold cross-validation with Jaccard scoring on 27,700 held-out records
- Human-in-the-loop quality controls for continuous refinement

**Outcomes:** 75.6% micro-F1, 88.3% precision, 66.1% recall, 60.8% micro-Jaccard, 60.6% exact match; ~30x vs. random baseline

`Python` `scikit-learn` `pandas` `TF-IDF` `Oracle/SQL` `NLP` `production ML`
