# Predicting Student Dropout with Supervised Learning

This project applies supervised learning models to predict student dropout from an online course platform. The focus is on modelling enrolment, engagement, and performance data to forecast course completion outcomes.

---

## Project Overview

The goal is to build classification models that can identify likely dropouts based on behavioural and academic indicators. Results are evaluated across accuracy, recall, precision, and AUC, with additional analysis of training dynamics and generalisation performance.

**Models used:**
- XGBoost (tuned with GridSearchCV)
- Neural Network (Keras-based MLP)

*Full PDF report included in the repo.*

---

## Key Steps

1. Preprocess enrolment and engagement data
2. Train and tune classification models
3. Evaluate using AUC, accuracy, precision, recall
4. Inspect training curves to detect overfitting

---

## Status

All analysis is presented in a structured Jupyter Notebook.  
Evaluation outputs are included, and the notebook is runnable without external dependencies.
