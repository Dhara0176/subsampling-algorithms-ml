# Sub Sampling Algorithms for Machine Learning

## Overview

Machine Learning models usually require large amounts of training data. Training on the complete dataset takes more time, requires more computational resources, and produces higher carbon emissions.

The objective of this project is to study whether machine learning models can be trained on smaller samples of the training data while maintaining performance close to the model trained on the full dataset.

Different sampling techniques and classification algorithms are compared to observe their effect on model performance, training time, and carbon emissions.

---

## Problem Statement

The goal of this project is to compare different sampling techniques and classification algorithms to determine which combinations can produce results similar to those obtained using the full training dataset.


---

## Datasets Used

### Adult Income Dataset
- Records: 48,842
- Features: 15
- Target Variable: Income

### Law School Admission Bar Passage Dataset
- Records: 22,407
- Features: 39
- Target Variable: Pass Bar

---

## Sampling Techniques

The following sampling methods were implemented and compared:

- Uniform Sampling
- L1 Norm Sampling
- L2 Norm Sampling
- Leverage Score Sampling
- Square Root Leverage Sampling

---

## Classification Algorithms

The sampled datasets were trained using:

- Decision Tree
- Logistic Regression
- Support Vector Machine (SVM)

---

## Experimental Setup

- Split the dataset into 80% training and 20% testing data.
- Applied sampling only on the training dataset.
- Used sample sizes of 2%, 3%, 5%, 7%, 10%, 12%, 15%, and 20%.
- Repeated each experiment 5 times using different random samples.
- Calculated the mean and standard deviation of the evaluation metrics.

---

## Evaluation Metrics

The models were compared using:

- Accuracy
- Precision
- Recall
- F1 Score
- Training Time
- Prediction Time
- Carbon Emissions

---

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- CodeCarbon

---

## Results

The experiments showed that:

- Models trained on sampled datasets achieved performance very close to the model trained on the full dataset.
- Training time was significantly reduced.
- Carbon emissions were much lower for sampled datasets.
- Different sampling techniques performed differently on different datasets.
- Square Root Leverage Sampling showed the most stable performance across different sample sizes.
- Logistic Regression achieved the best overall classification performance.

---



## Author

**Dhara R. Jogadiya**

Summer Research Internship

Dhirubhai Ambani University
