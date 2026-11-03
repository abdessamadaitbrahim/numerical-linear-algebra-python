# Numerical Linear Algebra for Data Analysis

[![Overview](https://img.shields.io/badge/Overview-2563EB?style=flat-square)](#overview)
[![Contents](https://img.shields.io/badge/Contents-2563EB?style=flat-square)](#contents)
[![Usage](https://img.shields.io/badge/Usage-7C3AED?style=flat-square)](#usage)
[![Structure](https://img.shields.io/badge/Structure-7C3AED?style=flat-square)](#repository-structure)
[![Author](https://img.shields.io/badge/Author-F59E0B?style=flat-square)](#author)

## Overview

An individual project on numerical linear algebra in Python (**NumPy** and **SciPy**): solving linear systems, matrix decompositions (LU, Cholesky, QR, SVD) and their applications in data analysis.

- **Notebook:** [notebooks/numerical_linear_algebra.ipynb](notebooks/numerical_linear_algebra.ipynb)
- **Notebook export (PDF):** [docs/notebook_export.pdf](docs/notebook_export.pdf)
- **Theory report (PDF):** [docs/theory_report.pdf](docs/theory_report.pdf)
- **Instructor:** Dr. Abdel Louly
- **Program:** Big Data and Artificial Intelligence, ENSA Tetouan, 2024-2025

## Contents

| Exercise | Topics |
|---|---|
| **1. Linear systems** | LU decomposition, Cholesky, Jacobi and Gauss-Seidel iterations, accuracy and execution time comparison |
| **2. Decompositions** | SVD (reconstruction, rank-2 approximation), QR (orthogonality check) |
| **3. Data analysis** | Principal component analysis (PCA) via SVD, image compression with different ranks (k = 10, 50, 100) |

The theory report compares direct and iterative methods for solving Ax = b and discusses the impact of SVD-based dimensionality reduction (compression, denoising, visualization, limits).

## Usage

```bash
git clone git@github.com:abdessamadaitbrahim/numerical-linear-algebra-python.git
cd numerical-linear-algebra-python
pip install -r requirements.txt
jupyter notebook notebooks/numerical_linear_algebra.ipynb
```

Matrices and vectors are generated randomly, so numerical results change at each run.

## Repository structure

```
numerical-linear-algebra-python/
├── notebooks/
│   └── numerical_linear_algebra.ipynb
├── docs/
│   ├── notebook_export.pdf
│   └── theory_report.pdf
├── requirements.txt
└── README.md
```

## Author

Abdessamad Ait Brahim, [@abdessamadaitbrahim](https://github.com/abdessamadaitbrahim)