DSCI 552 – Homework 4

Overview

This repository contains my Homework 4 submission for DSCI 552 – Machine Learning for Data Science at the University of Southern California.

In this assignment, I worked with time-series sensor data to understand how different machine learning models can classify human physical activities. I extracted statistical features, trained classification models, and compared their performance.

Dataset

I used the AReM (Activity Recognition System based on Multisensor Data Fusion) dataset, which contains sensor measurements collected during six physical activities:

* Bending
* Cycling
* Lying
* Sitting
* Standing
* Walking

The dataset is organized into seven folders because bending is divided into two categories: bending1 and bending2.

Methods Used

For this assignment, I worked with:

* Time-series feature extraction and exploratory data analysis
* Binary classification using logistic regression
* L1 regularization and feature selection
* Cross-validation and model evaluation
* Case-control sampling
* Multiclass logistic regression
* Gaussian and Multinomial Naive Bayes
* Confusion matrices and ROC curves
* Theoretical questions involving QDA and Bayes’ theorem

Results

Binary Classification

The L1-penalized logistic regression model achieved a test accuracy of 94.74%.

Multiclass Classification

I compared three different classification methods:

Model	Test Accuracy
L1-Penalized Logistic Regression	94.74%
Gaussian Naive Bayes	89.47%
Multinomial Naive Bayes	84.21%

L1-penalized logistic regression achieved the highest test accuracy among the three methods.

Repository Structure

DSCI-552_HW4/
├── data/
│   └── AReM/
│       ├── bending1/
│       ├── bending2/
│       ├── cycling/
│       ├── lying/
│       ├── sitting/
│       ├── standing/
│       └── walking/
├── NithyaPrasasthani_Eeri_HW4.ipynb
├── requirements.txt
├── .gitignore
└── README.md

How to Run

1. Clone the GitHub repository to your computer.
2. Open the project folder in VS Code or Jupyter Notebook.
3. Install the required Python libraries using:
    pip install -r requirements.txt
4. Open NithyaPrasasthani_Eeri_HW4.ipynb.
5. Select a Python kernel and run all cells in order.

The notebook uses relative paths to access the dataset from the data/AReM directory.

Conclusion

Through this assignment, I learned how time-series sensor measurements can be used to recognize different human activities. I also explored how feature extraction, regularization, and cross-validation can improve machine learning models.

Based on my results, L1-penalized logistic regression performed better than Gaussian and Multinomial Naive Bayes for multiclass classification. It achieved the highest test accuracy and made fewer classification mistakes.

Overall, this assignment helped me better understand how to prepare time-series data, select useful features, evaluate models, and compare different classification techniques.
