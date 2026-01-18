# Linear Algebra Cheatsheet

A comprehensive cheatsheet for Linear Algebra covering key concepts and topics.


## Main Sections

1. Vectors
2. Matrices
3. Linear Equations
4. Four Fundamental Subspaces
  - Vector Spaces
  - Bases and Dimension
  - Computing the Three Fundamental Subspaces
  - All Solutions of $A\mathbf{x}=\mathbf{b}$
5. Orthogonality and Projections
  - Definition
  - Projections
6. Applications of Orthogonality and Projections
  - Least Squares Approximation
  - The Set of All Solutions to a System of Linear Equations
  - Orthogonal Bases and Gram Schmidt
  - Pseudoinverse
7. The Determinant
  - 2x2 Case
  - General Case
8. Eigenvalues and Eigenvectors
  - Complex Numbers
  - Introduction to Eigenvectors and Eigenvalues
  - Properties of Eigenvalues and Eigenvectors
9. Diagonalization, Singular Value Decomposition
  - Diagonalization
  - Symmetric Matrices, Spectral Theorem
  - Singular Value Decomposition
10. Strategies
   - Systems of Equations
   - Fundamental Spaces
   - Orthogonality, Projections & Least Squares
   - Eigenvalues & Decomposition
   - Quick Sanity Checks
   - Proof Toolkit (Standard Strategies)
   - Advanced Calculation Strategies
   - Spectral Theory & Properties
   - Matrix Algebra Hacks
11. Typical Exercises
  - Projections onto Column Spaces
    - Find projection $\mathbf{p} \in C(Q)$ that minimizes $\|\mathbf{b} - \mathbf{p}\|$
  - Proofs with Skew-Symmetric Matrices
    - Prove $\mathbf{x}^\top S \mathbf{x} = 0$ for all $\mathbf{x}$ where $S^\top = -S$
  - Least Squares Fitting
    - Minimize $\sum_{k=1}^n (f(x_k) - y_k)^2$ for $f(x) = ax^2 + b$
  - Matrix Equations from Eigenvector Conditions
    - Constructing $A$ from orthonormal input--output pairs
  - Cauchy-Schwarz and Inequality Proofs
    - Prove $\sum_{i=1}^n \frac{a_i^2}{b_i} \ge \frac{(a_1 + \cdots + a_n)^2}{b_1 + \cdots + b_n}$ for $b_i > 0$
  - Singular Values and Decompositions
    - Find a non-zero singular value of a given matrix
12. Requirements Checklist
  - When can I use this method?
  - Diagonalization ($A=V\Lambda V^{-1}$)
  - Orthogonal Diagonalization ($A=Q\Lambda Q^\top$)
  - Cholesky Decomposition ($A=LL^\top$)
  - SVD ($A=U\Sigma V^\top$)
  - Least Squares ($A^\top A \hat{x} = A^\top b$)
13. Quick Facts & Properties
  - Symmetric Matrices ($A=A^\top$)
  - Orthogonal Matrices ($Q^\top Q = I$)
  - Skew-Symmetric Matrices ($A^\top = -A$)
  - Projection Matrices ($P^2 = P$)
  - Positive (Semi-)Definite Matrices
14. Rapid Operations
  - Inverse of $2\times 2$
  - Rank Properties
  - Determinant Shifts
  - Trace Tricks
  - Block Matrices
  - Cross Product (in $\mathbb{R}^3$)
  - Quick Eigenvalue Checks
  - Nilpotent & Idempotent
  - Linear Systems & Solutions

## Files

- `main.tex` - Main LaTeX cheatsheet document
- `notes_part_I.txt` - Part 1 of the script from LinAlg HS25
- `notes_part_II.txt` - Part 2 of the script from LinAlg HS25
## Usage

Compile the LaTeX document with:
```bash
pdflatex main.tex
```

---

*A reference guide for students studying Linear Algebra.*
