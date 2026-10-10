# Machine Learning Algorithms from Scratch

A collection of foundational machine learning algorithms implemented from scratch in Python using NumPy and Jupyter Notebooks[cite: 2, 3].

---

## Repository Structure

```text
├── GD_OOP_Vanilla_SGD_MBGD_Synthetic.ipynb
├── K_MEANS++.ipynb
├── Logistic_Regression_From_Scratch_Assignment.ipynb
├── PageRank_Algorithm.ipynb
└── Synthetic.csv
```[cite: 3]

---

## Notebooks Overview

### 1. Gradient Descent Variants (`GD_OOP_Vanilla_SGD_MBGD_Synthetic.ipynb`)
* **Topic:** Optimization algorithms implemented with an Object-Oriented Programming (OOP) design[cite: 3].
* **Contents:**
  * Vanilla / Batch Gradient Descent (BGD)[cite: 3]
  * Stochastic Gradient Descent (SGD)[cite: 3]
  * Mini-Batch Gradient Descent (MBGD)[cite: 3]
  * Evaluated and compared on the synthetic dataset (`Synthetic.csv`)[cite: 3].

### 2. K-Means++ Clustering (`K_MEANS++.ipynb`)
* **Topic:** Unsupervised clustering algorithm[cite: 3].
* **Contents:**
  * Implementation of centroid initialization using the $D^2$ weighting strategy (K-Means++) to accelerate convergence and avoid poor local minima.
  * Iterative assignment and centroid updating steps.

### 3. Logistic Regression (`Logistic_Regression_From_Scratch_Assignment.ipynb`)
* **Topic:** Supervised binary classification[cite: 3].
* **Contents:**
  * Sigmoid activation function and cross-entropy loss formulation.
  * Gradient computation and parameter updates without high-level ML libraries[cite: 2, 3].
  * Model evaluation and decision boundary visualization.

### 4. PageRank Algorithm (`PageRank_Algorithm.ipynb`)
* **Topic:** Link analysis and graph ranking[cite: 1, 2, 3].
* **Contents:**
  * Directed graph representation and column-stochastic transition matrix construction[cite: 2].
  * Random walk model with damping factor ($d = 0.85$) and teleportation handling[cite: 1, 2].
  * Step-by-step verification alongside power iteration until convergence[cite: 1, 2].

---

## Datasets

* **`Synthetic.csv`:** Synthetic feature dataset used for testing and comparing the gradient descent optimization algorithms[cite: 3].

---

\
pip install numpy pandas matplotlib jupyter
