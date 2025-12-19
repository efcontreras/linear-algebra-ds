# Linear Algebra and Spectral Methods for Data Science
![Python](https://img.shields.io/badge/Python-Data%20Science-blue?logo=python)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243?logo=numpy)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML%20Applications-F7931E?logo=scikitlearn)

![Linear%20Algebra](https://img.shields.io/badge/Linear%20Algebra-SVD%20%7C%20PCA%20%7C%20Spectral-4B5563)
![Website](https://img.shields.io/badge/Docs-Quarto%20Website-blue?logo=quarto)

![License](https://img.shields.io/badge/License-Open%20Source-green)

This repository presents a **rigorous yet applied treatment of Linear Algebra
and Spectral Methods**, with a clear focus on **Data Science applications**.

The project is designed as a **mathematical narrative**:
from vector spaces and linear maps to spectral theory, SVD, regularization,
PCA, and spectral clustering.

Rather than treating algorithms as black boxes, the emphasis is on
**geometry, structure, and interpretation**.

---

## Philosophy

Modern Data Science relies heavily on linear algebra, but the underlying
mathematical ideas are often hidden behind APIs and implementations.

This project takes the opposite approach:

> **Understand first, compute second.**

Key principles:
- linear algebra is fundamentally geometric,
- spectral decompositions reveal structure,
- low-rank approximations are optimal, not heuristic,
- regularization is spectral control,
- many nonlinear problems become linear after the right embedding.

---

## Structure of the Repository

The material is organized as a **Quarto website**, composed of self-contained
chapters written in Markdown with LaTeX mathematics and Python examples.

### Foundations
- Vector spaces and subspaces  
- Linear maps and matrices  
- Inner products, orthogonality, projections  
- Computational cost and complexity (addendum)

### Solving Linear Systems
- LU and PA = LU decompositions  
- Cholesky decomposition  
- Numerical stability and conditioning  

### Spectral Theory
- Eigenvalues and eigenvectors  
- Spectral Theorem for symmetric operators  
- Rayleigh quotients and quadratic forms  

### Singular Value Decomposition
- SVD as a generalization of spectral theory  
- Geometry of singular vectors  
- Optimal low-rank approximation (Eckart–Young)  

### Applications
- Principal Component Analysis (PCA)  
- Truncated SVD and ridge regularization  
- Bias–variance trade-offs  
- Spectral clustering and graph Laplacians  

---

## Mathematical Level

The exposition is **mathematically rigorous** but accessible to readers with:

- basic linear algebra,
- familiarity with matrices and vector spaces,
- interest in Data Science or applied mathematics.

Where appropriate:
- definitions, theorems, and proofs are provided,
- proofs may be collapsible to preserve readability,
- computational examples illustrate abstract ideas.

---

## Computational Tools

All computational examples use:

- **Python**
- `numpy`
- `scipy`
- `matplotlib`
- `scikit-learn` (for selected applications)

The focus is on **clarity and interpretation**, not on performance engineering.

---

## How to Use This Repository

You can use this project in multiple ways:

- 📘 as a **self-study resource** on spectral methods,
- 🧠 as a **conceptual reference** for Data Science practice,
- 🎓 as **lecture notes** for a course or seminar,
- 🔬 as a bridge between **theory and applied modeling**.

Suggested reading paths:
- *Theory-first*: Foundations → Spectral Theory → SVD  
- *Application-first*: PCA → Regularization → Spectral Clustering  
- *Full journey*: read chapters in order  

---

## Website

The content is rendered as a static website using **Quarto**.

## Intended Audience

This repository is intended for:
- Data Scientists who want deeper mathematical understanding,
- Mathematicians interested in applied spectral methods,
- Graduate students in Data Science, Statistics, or Applied Mathematics,
- Practitioners who want to reason about models.

---

## Author

This project is developed by **Erik Contreras López**,  
Mathematician (PhD) and Data Scientist.

The material reflects both:
- academic training in mathematics,
- practical experience in data-driven modeling.

---

## License

This repository is released under an open-source license.
See the `LICENSE` file for details.

---

## Final Note

This repository is an invitation to think about Data Science
through the lens of linear algebra and geometry.
