# Predicting Drug Interaction Risks Using Machine Learning
## Introduction

Drug interactions are a leading cause of adverse drug reactions, affecting patient safety. Predicting these interactions can help healthcare professionals make safer prescribing decisions and reduce the likelihood of harmful side effects.

### Dataset Overview

You are provided with three CSV files:

training.csv – Historical records containing the target column Deviation (MW).

test.csv – Unseen data for which you must generate predictions.

evaluation.csv – Final unseen dataset for testing your trained models.

### Objective

Develop a machine learning model to classify whether a medicine (from medicine_data.csv) is likely to have high-risk drug interactions based on features such as:

salt_composition

product_manufactured

medicine_desc

side_effects

drug_interactions

This is a binary classification task — predicting high-risk vs. low-risk interactions.
The goal is to identify medicines that may cause harmful interactions, thereby assisting doctors and pharmacists in safer prescription decisions.
