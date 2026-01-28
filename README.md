# 🎓 Classification with Academic Success

## Overview
This project predicts students’ academic outcomes by classifying them into three categories:  
**Graduate, Enroll, or Dropout**.

Using demographic and academic features, machine learning models are trained to capture patterns in student performance and generate predictions for a Kaggle competition.

The project was developed in **Jupyter Notebook**.

---

## Dataset
The dataset was generated using a deep learning model trained on the original *Predict Students' Dropout and Academic Success* dataset.  
Although feature distributions are similar, they are not identical.

**Files:**
- `train.csv` – training data with categorical target variable (`Target`)
- `test.csv` – test data for prediction
- `sample_submission.csv` – submission format

---

## Methodology
- Data preprocessing and feature engineering
- Encoding of categorical variables
- Evaluation of multiple classification models
- Validation-based model comparison

---

## Models & Performance
Several models were tested, including linear and tree-based approaches.

**Best performing model:**
- **Gradient Boosting**
  - Validation Accuracy: **82.64%**

Tree-based models (Gradient Boosting, Random Forest) outperformed linear models and Naive Bayes, highlighting the importance of capturing non-linear relationships.

---

## Conclusion
The Gradient Boosting model provides reliable predictions for student academic outcomes.  
This project demonstrates an effective and reusable pipeline for **tabular classification problems** in real-world educational data.

---

## Tools
Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook
