# SVM_on_MoonData

This repository contains a Jupyter Notebook that demonstrates how to apply Support Vector Machines (SVM) with both linear and non-linear (RBF) kernels on a classic “two moons” synthetic dataset. The project showcases data generation, visualization, model training, evaluation, and analysis of support vectors and dual coefficients.

📌 Project Overview

Support Vector Machines are powerful supervised learning algorithms for classification. This project focuses on:

Generating a non-linearly separable dataset using make_moons from sklearn.datasets.

Splitting the data into training and testing sets (80/20).

Training SVM classifiers with:

Linear kernel

Radial Basis Function (RBF) kernel

Evaluating performance and visualizing decision boundaries.

Examining support vectors, dual coefficients, and their implications for the model.

What’s Inside

SVM_on_Moon_Data.ipynb → Jupyter Notebook with step-by-step implementation, including code cells and explanations.

Key Steps in the Notebook

Data Preparation

Generate 10,000 samples with controlled noise.

Train-test split using train_test_split.

Linear SVM

Train a linear SVM model using sklearn.svm.SVC with kernel='linear'.

Visualize decision boundary and evaluate performance.

RBF SVM

Train a non-linear SVM with kernel='rbf'.

Analyze total number of support vectors (e.g., 342 in this example).

Examine dual coefficients and how many are non-zero.

Model Evaluation

Accuracy on test set

Visualization of support vectors

Dual coefficient analysis

Technologies Used

Python 3

NumPy

Matplotlib

scikit-learn

Jupyter Notebook
