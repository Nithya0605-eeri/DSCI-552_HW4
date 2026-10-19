DSCI 552 – Homework 4

Overview

This repository contains my Homework 4 submission for DSCI 552 – Machine Learning for Data Science at the University of Southern California.

The assignment focuses on time-series feature extraction, activity classification, and comparing different machine learning methods using the AReM dataset.

Dataset

The AReM dataset contains sensor measurements collected during six types of physical activities:

* Bending
* Cycling
* Lying
* Sitting
* Standing
* Walking

The dataset is organized into seven folders, with bending divided into two separate folders.

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

For binary classification, the L1-penalized logistic regression model achieved a test accuracy of 94.74%.

For multiclass classification, L1-penalized logistic regression also performed best, achieving 94.74% test accuracy, compared with 89.47% for Gaussian Naive Bayes and 84.21% for Multinomial Naive Bayes.

Repository Structure

DSCI-552_HW4/
├── data/
│   └── AReM/
├── NithyaPrasasthani_Eeri_HW4.ipynb
├── requirements.txt
├── .gitignore
└── README.md

How to Run

1. Clone the repository.
2. Install the required Python packages:
    pip install -r requirements.txt
3. Open the Jupyter notebook.
4. Run all cells in order.

The notebook uses relative dataset paths so it can run from the repository’s root directory.

Conclusion

This assignment helped me understand how different classification methods perform on time-series sensor data. Based on the results, L1-penalized logistic regression performed better than the Naive Bayes models for this dataset. It also showed how feature selection and regularization can help build effective classification models.
