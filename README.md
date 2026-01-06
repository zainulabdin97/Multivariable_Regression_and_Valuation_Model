# Multivariable Regression & Housing Valuation Model (Boston Housing)

A data science project that builds a multivariable regression model to estimate housing prices and demonstrates a simple valuation workflow for predicting a property’s value from its features.

---

## Project Overview

This notebook explores the Boston Housing dataset, performs exploratory data analysis (EDA), trains a multivariable **Linear Regression** model, and evaluates performance using standard regression metrics.  
To improve stability and reduce skew in the target variable, the project also trains a model using a **log-transformed price target**, then converts predictions back to the original price scale for valuation.

---

## Key Highlights

- Clean EDA with focused visualizations (e.g., **RM vs PRICE**, **LSTAT vs PRICE**)
- Baseline multivariable Linear Regression model
- Log-target regression to improve residual behavior
- Coefficient interpretation to understand key price drivers
- Practical valuation examples:
  - Average property estimate
  - Custom property estimate (user-defined inputs)

---

## Dataset

This project uses the Boston Housing dataset. Many sources name the target as `MEDV` (median value).  
If needed, the notebook renames:

- `MEDV` → `PRICE`

Example CSV source:
- https://raw.githubusercontent.com/selva86/datasets/master/BostonHousing.csv

> Note: Column names may vary slightly across sources. The notebook expects a `PRICE` column.

---

## Tech Stack

- Python
- Jupyter Notebook
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

---

## How to Run

### 1) Clone the repository
```bash
git clone <YOUR_REPO_URL>
cd <YOUR_REPO_NAME>
