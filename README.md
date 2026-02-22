Facial Recognition with PCA and NMF
Project Overview

This project explores dimensionality reduction techniques—Principal Component Analysis (PCA) and Non-Negative Matrix Factorization (NMF)—and their application to facial recognition and image reconstruction. The goal is to understand how high-dimensional image data can be efficiently represented, reconstructed, and analyzed using linear algebra–based methods.

The project is implemented in Python using NumPy, SciPy, and visualization libraries, and is structured as an interactive Jupyter Notebook.

Objectives

Reduce the dimensionality of facial image data while preserving important features

Compare PCA and NMF in terms of:

Representation

Reconstruction quality

Interpretability

Visualize principal components and basis vectors

Analyze reconstruction error as dimensionality changes

Develop intuition for when and why dimensionality reduction is useful in machine learning

Methods Used
Principal Component Analysis (PCA)

Singular Value Decomposition (SVD)

Orthogonal components

Captures directions of maximum variance

Allows image reconstruction from reduced subspaces

Non-Negative Matrix Factorization (NMF)

Non-negativity constraints for improved interpretability

Parts-based representation of facial features

Optimization-based matrix factorization

Project Structure
Facial_Recognition_PCA_NMF_ML_Project.ipynb
README.md
Key Features

Manual implementation of PCA using SVD

Custom NMF training using optimization techniques

Visualization of:

Principal components (eigenfaces)

NMF basis vectors

Original vs. reconstructed images

Comparative analysis of PCA vs. NMF

Discussion of real-world applications and trade-offs

Technologies & Libraries

Python 3

NumPy

SciPy

Matplotlib

Autograd

Jupyter Notebook / Google Colab

How to Run

Clone this repository:

git clone https://github.com/your-username/your-repo-name.git

Open the notebook:

jupyter notebook Facial_Recognition_PCA_NMF_ML_Project.ipynb

OR
Open directly in Google Colab using the badge at the top of the notebook.

Run all cells to reproduce results and visualizations.

Key Findings

PCA excels at global variance preservation but produces less interpretable components

NMF yields more intuitive, parts-based facial representations

Reconstruction quality improves with higher dimensionality but with diminishing returns

Dimensionality reduction significantly reduces computational complexity while retaining structure

Future Improvements

Add classification on reduced features (e.g., SVM or logistic regression)

Compare with nonlinear methods (e.g., autoencoders)

Evaluate reconstruction error quantitatively

Extend analysis to larger or color image datasets
