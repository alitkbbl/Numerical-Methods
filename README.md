# Numerical Methods Project

<p align="center">
      <img src="banner.png" alt="Project Banner" width="100%">
</p>

A collection of numerical methods implemented in Python, covering interpolation,
data visualization, and numerical integration. Each topic is explored through a
dedicated Jupyter notebook with supporting figures, results, and detailed reports.

## 📄 Project Documentation

For a comprehensive overview of the project, please refer to the full reports:

* [English Report](report/English_report.pdf)
* [Persian Report](report/project_report.pdf)

---

## 📂 Directory Structure

```
numerical-methods/
│
├── README.md
├── data/
│   └── algorithm_times.xlsx          # Raw timing/measurement data
│
├── notebooks/
│   ├── 01_interpolation.ipynb         # Interpolation methods
│   ├── 02_data_visualization.ipynb    # Data analysis & plotting
│   └── 03_numerical_integration.ipynb # Numerical integration
│
├── outputs/
│   ├── figures/                       # Generated plots and charts
│   └── results/                       # Computed numerical results
│
└── report/
    ├── project_report.pdf             # Persian report
    └── English_report.pdf             # English report

```
---

## 📌 Project Overview

### Question 1 — Interpolation
Implements and compares interpolation techniques to approximate a function from
a set of discrete data points. The notebook evaluates accuracy across methods
and visualizes how each interpolant fits the underlying data.

📓 [`notebooks/01_interpolation.ipynb`](notebooks/01_interpolation.ipynb)

### Question 2 — Data Visualization
Analyzes algorithm timing data from `algorithm_times.xlsx` using multiple chart
types (line charts, bar charts, and box plots) to reveal performance trends,
distributions, and outliers across different algorithms.

📓 [`notebooks/02_data_visualization.ipynb`](notebooks/02_data_visualization.ipynb)

### Question 3 — Numerical Integration
Applies numerical integration methods to approximate definite integrals and
compares the results against analytical values to assess accuracy and
convergence behavior.

📓 [`notebooks/03_numerical_integration.ipynb`](notebooks/03_numerical_integration.ipynb)

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/alitkbbl/Numerical-Methods.git
cd Numerical-Methods

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```



## 📝 Summary

This project demonstrates core numerical methods (interpolation, numerical 
integration, and data visualization) through practical, well-documented examples. 
Each notebook is self-contained and produces figures and results saved under 
the `outputs/` directory. 

For complete analysis, derivations, and discussion of results, refer to the 
comprehensive reports in the `report/` folder.

