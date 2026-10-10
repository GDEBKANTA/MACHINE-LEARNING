# Machine Learning & Optimization from Scratch

A comprehensive repository containing from-scratch implementations of fundamental machine learning algorithms, numerical optimization techniques, and graph analysis methods built using Python and NumPy[cite: 2, 3].

---

## Overview

This repository focuses on breaking down standard algorithmic frameworks into clear, mathematical building blocks without relying on high-level machine learning libraries[cite: 2, 3]. Each project explores core concepts including matrix formulation, gradient-based loss minimization, iterative convergence, and vectorization[cite: 2, 3].

---

## Implemented Modules

### 1. Gradient Descent Optimization Variants
Implemented inside `GD_OOP_Vanilla_SGD_MBGD_Synthetic.ipynb`, this module uses an Object-Oriented Programming (OOP) paradigm to demonstrate and evaluate three primary optimization routines:
* **Batch Gradient Descent (Vanilla BGD):** Computes weight updates across the entire dataset per iteration to ensure steady convergence.
* **Stochastic Gradient Descent (SGD):** Evaluates parameter steps per individual sample, trading off smooth trajectory for rapid iteration speeds.
* **Mini-Batch Gradient Descent (MBGD):** Balances computational efficiency and variance by dividing samples into small vector batches.
* **Evaluation:** Benchmarked on `Synthetic.csv` to compare convergence rates, loss decay curves, and computational overhead[cite: 3].

### 2. K-Means++ Clustering
Developed in `K_MEANS++.ipynb`, this module covers unsupervised partitioning and clustering[cite: 3]:
* **Smart Initialization:** Uses probability proportional to squared Euclidean distances ($D^2$) to select well-separated initial centroids, significantly reducing poor local minima traps.
* **Iterative Assignment:** Alternates between Voronoi-cell nearest-centroid mapping and mean-vector recalculation until cluster assignments stabilize.

### 3. Logistic Regression
Contained in `Logistic_Regression_From_Scratch_Assignment.ipynb`, this section builds a complete binary classification workflow[cite: 3]:
* **Loss & Activation:** Implements the standard sigmoid activation function paired with cross-entropy loss[cite: 2, 3].
* **Optimization:** Derives the analytical gradient for weight and bias terms, iteratively refining parameters via gradient descent.
* **Analysis:** Includes model evaluation, probability thresholding, and decision boundary visualization.

### 4. PageRank Algorithm
Implemented in `PageRank_Algorithm.ipynb`, this notebook translates web graph link analysis into matrix algebra[cite: 1, 2, 3]:
* **Graph Modeling:** Maps directed webpage graphs into column-stochastic transition matrices where outgoing weights distribute equally among destinations[cite: 1, 2].
* **Teleportation Handling:** Incorporates a damping factor ($d = 0.85$) with an evenly distributed base random jump probability ($\frac{1-d}{N}$) to handle dead ends and cyclic traps[cite: 1, 2].
* **Power Iteration:** Implements iterative vector updates until the L1 norm difference meets strict tolerance thresholds[cite: 2].

---
