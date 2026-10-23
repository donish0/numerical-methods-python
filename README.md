# Numerical Methods in Python

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)
![Project Status](https://img.shields.io/badge/Status-Ongoing-2EA44F?style=flat-square)

Some mathematical problems are difficult to solve directly, and in some cases, finding an exact solution isn't possible. I started this repository out of curiosity to understand how computers can help solve these kinds of problems.

Here, I'm implementing different numerical methods in Jupyter Notebooks using Python and its scientific computing libraries. Along the way, I'm exploring how each method works, how it approaches an approximate solution step by step, and how accuracy and numerical errors affect the results.

## Project Structure

```text
numerical-methods-python/
├── root-finding-method/
├── interpolation/
├── numerical-integration/
├── linear-systems/
├── eigenvalues-eigenvectors/
└── differential-equations/
```

| Directory | What's Inside |
|-----------|---------------|
| `root-finding-method` | • Bisection Method<br>• Newton-Raphson Method<br>• Fixed Point Iteration Method<br>• False Position (Regula Falsi) Method |
| `interpolation` | • Newton's Forward Difference<br>• Newton's Backward Difference<br>• Newton's Divided Difference<br>• Lagrange Interpolation<br>• Cubic Spline Interpolation<br> |
| `numerical-integration` | • Trapezoidal Rule<br>• Simpson's 1/3 Rule<br>• Simpson's 3/8 Rule<br>• Romberg Method<br>• Gauss-Legendre Quadrature (2-point)<br>• Gauss-Legendre Quadrature (3-point) |
| `linear-systems` | • Gauss Elimination<br>• Gauss-Jordan Elimination<br>• Matrix Inversion<br>• LU Decomposition<br>• Jacobi Method<br>• Gauss-Seidel Method<br> |
| `eigenvalues-eigenvectors` | • Power Method<br>• Jacobi Method<br>• Givens Method<br> |
| `differential-equations` | • Euler's Method<br>• Runge-Kutta 2nd Order (RK2)<br>• Runge-Kutta 4th Order (RK4)<br>• Adams-Bashforth-Moulton Method |

## Libraries Used

I'm mainly using these Python libraries:

- **NumPy** for numerical calculations and matrix operations
- **SciPy** to compare my results with built-in numerical methods
- **SymPy** for symbolic calculations and derivatives
- **Pandas** to display iteration steps and results in tables
- **Matplotlib** to plot graphs and visualize results
- **Jupyter Notebook** to run the code and see the output step by step

## Getting Started

You'll need Python 3 and pip installed on your computer.

First, install the required libraries:

```bash
python -m pip install numpy scipy sympy pandas matplotlib notebook
```

Clone the repository:

```bash
git clone https://github.com/donish0/numerical-methods-python.git
cd numerical-methods-python
```

Start Jupyter Notebook from the project folder:

```bash
jupyter notebook
```

If the `jupyter` command is not found, use this instead:

```bash
python -m notebook
```

Your browser will open the Jupyter file explorer. Go to the folder containing the method you want to try and open the `.ipynb` notebook.

For example, open `root-finding-method/bisection.ipynb` and run the cells one by one (`Shift + Enter`), or use **Run All** from the menu.

You can also open the notebooks in VS Code (with the Jupyter extension installed) or in Google Colab (open them from the GitHub tab or upload the file).

You can explore the other folders in the same way.

## What I'm Learning

- How different numerical methods work and the math behind them
- Implementing the algorithms myself instead of just relying on built-in functions
- How iterative methods get closer to a solution step by step
- How accuracy, convergence, and numerical errors affect the results
- Visualizing results with graphs to understand how each method behaves
- Improving my Python and problem-solving skills with each method

## License

This project is open source under the [MIT License](LICENSE).
