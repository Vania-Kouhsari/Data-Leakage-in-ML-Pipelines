# Data Leakage in Supervised Machine Learning Pipelines

Experimental implementation and taxonomy evaluation developed for the bachelor thesis:

**“Data Leakage in Supervised Machine Learning Pipelines: A Structured Taxonomy and Critical Evaluation of Detection and Mitigation Strategies.”**

---

## Overview

This repository contains the experimental implementation used to demonstrate and evaluate different forms of data leakage in supervised machine learning pipelines. The experiments were conducted using the Credit Card Fraud Detection dataset and focus on illustrating how leakage affects model evaluation and predictive performance.

The repository includes implementations of:

- Baseline (No Leakage)
- Target Leakage
- Train-Test Contamination
- Temporal Leakage

The experiments were performed using the following machine learning models:

- Logistic Regression
- Support Vector Machine (Linear Kernel)
- Random Forest

Evaluation was conducted using multiple performance metrics, including:

- Accuracy
- Precision
- Recall
- F1-Score

---

## Dataset

The dataset used in this study is publicly available from Kaggle:

Credit Card Fraud Detection Dataset:  
[Kaggle Dataset Link](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud?utm_source=chatgpt.com)

Due to file size limitations and dataset distribution considerations, the dataset is not included directly in this repository.
.
├── data_leakage_experiments.ipynb
├── README.md
