
# Numerical Methods in Python

A Python-based collection of numerical methods designed to solve mathematical and computational problems. This project focuses on implementing numerical algorithms, visualizing their behavior, and comparing their computational performance.

The project is being developed incrementally, starting with root-finding methods and expanding towards other areas of numerical analysis.

## Current Implementation

### 1. Root-Finding Methods

The following methods are currently implemented:

- **Bisection Method**
- **Fixed Point Iteration Method**
- **False Position Method (Regula Falsi)**
- **Newton-Raphson Method**

### 2. Features

- Individual implementation of each numerical method.
- Graphical visualization of mathematical functions.
- Comparison of numerical results across different methods.
- Execution time measurement.
- Iteration count and convergence analysis.
- Automated testing of implemented methods.

## Project Structure

```text
Numerical-Methods/
│
├── README.md
├── requirements.txt
├── pyproject.toml
│
├── src/
│   └── root_finding/
│       ├── __init__.py
│       ├── bisection.py
│       ├── fixed_point.py
│       ├── false_position.py
│       ├── newton_raphson.py
│       ├── compare.py
│       └── visualization.py
│
├── examples/
│   └── run_all.py
│
├── tests/
│   └── test_root_methods.py
│
└── results/
```

## Installation

### 1. Clone the Repository

```bash
git clone https://github.com/donish0/numerical-methods-python.git
cd numerical-methods-python
```

## Usage

### Run the Implemented Methods

Execute the following command to run the implemented numerical methods and generate comparisons and visualizations:

```bash
python examples/run_all.py
```

### Run the Test Suite

Run the automated tests using pytest:

```bash
python -m pytest
```

## Results and Visualization

The project generates graphical representations and comparative results to help analyze the behavior and performance of different numerical methods.

Generated plots and output files are saved in the `results/` directory.

Execution time may vary depending on the system and computational environment.

## Future Development

This project will be expanded progressively to cover additional topics in Numerical Methods, including:

- Numerical Differentiation and Integration
- Linear Algebraic Equations
- Interpolation and Curve Fitting
- Eigenvalue and Eigenvector Computation
- Numerical Solutions of Differential Equations

Additional algorithms, visualizations, and performance comparisons will be incorporated as the project develops.

## Technologies Used

- **Python** — Programming language
- **NumPy** — Numerical computation
- **Matplotlib** — Data visualization
- **SymPy** — Symbolic mathematics
- **Pytest** — Automated testing

## Project Objective

The primary objective is to develop a structured and extensible collection of numerical algorithms while exploring their mathematical foundations, computational implementations, accuracy, convergence, and performance.

---

**Status:** Ongoing Development

**Scope:** Numerical Analysis and Scientific Computing
