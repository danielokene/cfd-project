# CFD Fundamentals in Python: 12 Steps to Navier–Stokes

> A hands-on implementation of the numerical methods behind Computational Fluid Dynamics (CFD), progressing from one-dimensional convection equations to solving the incompressible Navier–Stokes equations.

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![NumPy](https://img.shields.io/badge/NumPy-Numerical_Computing-orange)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-green)
![Status](https://img.shields.io/badge/Progress-In_Progress-yellow)

---

## Overview

This repository documents my journey of learning **Computational Fluid Dynamics (CFD)** by implementing numerical solvers entirely from scratch in Python.

Rather than relying on commercial CFD software, each exercise develops the governing equations, discretizes them using finite difference methods, and implements the solution using NumPy and Matplotlib.

The exercises begin with simple one-dimensional transport equations and gradually build toward solving the incompressible **Navier–Stokes equations**.

---

## Motivation

As an budding researcher in **Computational Fluid Dynamics, Thermo-Fluids, and Scientific Machine Learning**, I believe understanding the underlying numerical methods is just as important as using existing CFD software.

This repository serves as both:

* a structured learning journal,

* a portfolio of CFD implementations,

---

## Learning Roadmap

### 1D Problems

* [X] Step 1 — Linear Convection
* [X] Step 2 — Nonlinear Convection
* [X] CFL Condition
* [X] Step 3 — Diffusion
* [X] Step 4 — Burgers' Equation

### 2D Problems

* [X] Step 5 — Linear Convection
* [X] Step 6 — Nonlinear Convection
* [X] Step 7 — Diffusion
* [ ] Step 8 — Burgers' Equation

### Elliptic PDEs

* [ ] Step 9 — Laplace Equation
* [ ] Step 10 — Poisson Equation

### Navier–Stokes

* [ ] Step 11 — Lid-Driven Cavity Flow
* [ ] Step 12 — Channel Flow

---

## Numerical Methods Covered

| Step | Problem              | Dimension | Concepts                     |
| ---- | -------------------- | --------- | ---------------------------- |
| 1    | Linear Convection    | 1D        | Upwind Scheme                |
| 2    | Nonlinear Convection | 1D        | Nonlinear PDEs               |
| 3    | Diffusion            | 1D        | FTCS Scheme                  |
| 4    | Burgers' Equation    | 1D        | Convection + Diffusion       |
| 5    | Linear Convection    | 2D        | Finite Difference            |
| 6    | Nonlinear Convection | 2D        | Coupled PDEs                 |
| 7    | Diffusion            | 2D        | Explicit Time Marching       |
| 8    | Burgers' Equation    | 2D        | Nonlinear Transport          |
| 9    | Laplace Equation     | 2D        | Iterative Solvers            |
| 10   | Poisson Equation     | 2D        | Source Terms                 |
| 11   | Lid-Driven Cavity    | 2D        | Incompressible Navier–Stokes |
| 12   | Channel Flow         | 2D        | Pressure-Driven Flow         |

---

## Repository Structure

```text
cfd-fundamentals-python/
│
├── README.md
├── LICENSE
├── requirements.txt
├── .gitignore
│
├── notebooks/
│   ├── Step01_Linear_Convection.ipynb
│   ├── Step02_Nonlinear_Convection.ipynb
│   ├── ...
│   └── Step12_Channel_Flow.ipynb
│
├── src/
│   ├── step01_linear_convection.py
│   ├── step02_nonlinear_convection.py
│   ├── ...
│   └── step12_channel_flow.py
│
├── images/
│   ├── step01.png
│   ├── cavity.png
│   └── burgers2d.gif
│
└── reports/
```

---

## Example Results

Results from each step will be added here as I progress through the project.

| Step    | Visualization   |
| ------- | --------------- |
| Step 1  | *(Coming Soon)* |
| Step 4  | *(Coming Soon)* |
| Step 8  | *(Coming Soon)* |
| Step 11 | *(Coming Soon)* |
| Step 12 | *(Coming Soon)* |

---

## Installation

Clone the repository

```bash
git clone https://github.com/danielokene/cfd-fundamentals-python.git
```

Move into the project

```bash
cd cfd-fundamentals-python
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Running a Solver

Example:

```bash
python src/step01_linear_convection.py
```

or open the corresponding Jupyter notebook inside the `notebooks/` folder.

---

## What I'm Learning

Throughout this project I aim to develop a solid understanding of:

* Partial Differential Equations
* Finite Difference Methods
* Explicit Time Integration
* Numerical Stability
* CFL Condition
* Boundary Conditions
* Pressure Poisson Equation
* Incompressible Navier–Stokes Equations
* Scientific Programming with NumPy

---

## Future Work

After completing these twelve steps, I plan to explore:

* Finite Volume Method (FVM)
* Lattice Boltzmann Method (LBM)
* OpenFOAM
* Turbulence Modeling (RANS & LES)
* GPU-Accelerated CFD
* High-Performance Computing (MPI/OpenMP)

---

## Acknowledgements

This repository is inspired by the excellent educational project **CFD Python: The 12 Steps to Navier–Stokes** developed by Prof. Lorena A. Barba and Gilbert F. Forsyth. While this repository contains my own implementations, notes, and learning progress, the learning pathway and pedagogical approach are based on their open educational materials. Please consider citing their work if you use or build upon the original lessons.

---

## Citation

If you use the original educational material, please cite:

> Barba, L. A., & Forsyth, G. F. (2018). *CFD Python: the 12 steps to Navier–Stokes equations*. Journal of Open Source Education, **1**(9), 21. https://doi.org/10.21105/jose.00021

---

## References

1. Barba, L. A., & Forsyth, G. F. (2018). *CFD Python: The 12 Steps to Navier–Stokes*. Journal of Open Source Education.
2. Anderson, J. D. *Computational Fluid Dynamics: The Basics with Applications.*
3. Ferziger, J. H., & Perić, M. *Computational Methods for Fluid Dynamics.*
4. Versteeg, H. K., & Malalasekera, W. *An Introduction to Computational Fluid Dynamics: The Finite Volume Method.*

---

**⭐ If you find this repository useful, feel free to star it!**