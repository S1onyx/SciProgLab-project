# 🧮 Numerical Integration in Python

An interactive Jupyter notebook for numerical integration — developed as part of the *Scientific Programming Lab* course at DHBW.

## 📚 Project Overview

This project explores various techniques for numerical integration, including classical methods like Riemann sums and the trapezoidal rule, as well as probabilistic approaches like Monte Carlo simulation. The goal is to explain these methods mathematically, implement them programmatically, visualize their behavior, and evaluate them using representative test functions.

## 🔍 Notebook Contents

The notebook is structured into several parts:

1. **Introduction to Numerical Integration**
   - Mathematical foundations
   - Definitions and derivations
2. **Part 1 – Classical Methods**
   - Upper sums, lower sums, trapezoidal rule
   - Flexible implementation with parameter options
3. **Part 2 – Monte Carlo Integration**
   - Randomized integration with manual or adaptive bounds
   - Comparison to classical methods
4. **Part 3 – Visualization**
   - Graphical illustrations of integration methods
   - Comparative result analysis
5. **Part 4 – Testing & Evaluation**
   - Tested with functions like `sin(x)`, `x² - 4x + 2`, and `e^x`
   - Convergence analysis as resolution increases
   - Comparison with analytical integrals
6. **Part 5 – Limits of Numerical Integration**
   - Example: `sin((x + 1) * 16π)` over [0, 1]
   - Error analysis based on number of intervals
   - Criteria for reliable integration
7. **(Optional) Special Case: Gaussian Error Function**
   - Numerically integrable but non-elementary functions

## ✅ Features

- Supports upper/lower sum and trapezoidal rule
- Monte Carlo integration with fixed or adaptive bounds
- Mathematical documentation using LaTeX
- Visualizations with `matplotlib`
- Robust error handling and parameter validation
- Includes extensive testing

## 🧪 Requirements

- **Python 3.8+**
- No external modules required — runs in standard Jupyter environment

## 🚀 Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/USERNAME/numerical-integration.git
   cd numerical-integration
   ```

2. Launch Jupyter:
   ```bash
   jupyter notebook
   ```

3. Open and run `numerical_integration.ipynb`

## 👨‍👩‍👧‍👦 Team

Developed by a group of four students as part of the *Scientific Programming Lab* at DHBW:

- Simon
- Colin
- Laurin
- Damian

## 🗓️ Submission

- **Due Date**: Wednesday, July 16, 2025 – 23:59 (via Moodle)
- **Presentation**: Thursday, July 17, 2025, during class

## 📄 License

This project is intended for educational purposes only and is not released under a specific license.
