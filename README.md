# Data Poisoning Simulation on a Sentiment Classifier

## Overview

This project simulates a **data poisoning attack** on a basic sentiment classifier trained on the NLTK movie reviews dataset. The goal is to demonstrate how malicious manipulation of training data (i.e., label flipping) can degrade a model's performance.

---

## Student Details

- **Name**: Sony Pailla  
- **Course**: CS5720 – Neural Network and Deep Learning  
- **Semester**: Spring 2025  
- **University**: University of Central Missouri  

---

## Objectives

- Train a sentiment classifier using the `movie_reviews` dataset.
- Poison a subset of the training data by **flipping labels** for reviews mentioning a specific entity (e.g., "Berkeley").
- Evaluate the model **before and after poisoning** using accuracy and confusion matrix.

---

## Tools and Libraries

- Python 3.8+
- `nltk`
- `scikit-learn`
- `matplotlib`
- `seaborn`

### Installation
```bash
pip install nltk scikit-learn matplotlib seaborn
Dataset
Using the movie_reviews corpus from NLTK which includes:

1000 positive reviews

1000 negative reviews

Data Poisoning Method
Target keyword: "berkeley"

Poison fraction: 10% of the training dataset

Method: Flip the sentiment label if the review text contains the keyword "berkeley"
Evaluation
The model is evaluated before and after poisoning using:

Accuracy score

Confusion matrix

Results
Accuracy before poisoning: X.XX

Accuracy after poisoning: X.XX

Impact: Noticeable decrease in performance and reliability

Confusion Matrix
Before Poisoning

After Poisoning

Conclusion
The experiment highlights how targeted data poisoning—even on a small scale—can disrupt the performance of a sentiment classifier. This underlines the importance of data integrity in machine learning pipelines.
