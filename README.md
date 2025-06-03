# Customer Churn Prediction in a Fuel Station Chain Using Machine Learning Methods

**Author:** Kostin Kirill
**Supervisor:** Beklaryan Armen
**Institution:** Master of Data Science, Faculty of Computer Science, National Research University Higher School of Economics, Moscow, 2025

## Project Overview

This repository contains the code, experimental notebooks, and supplementary materials for the master's thesis focused on developing a machine learning system to proactively predict customer churn within a major fuel station chain's loyalty program. The primary goal is to identify customers at high risk of inactivity in the next 30 days, enabling timely retention interventions.

## Repository Structure

- `/data_preparation`: Contains scripts related to data ingestion from Parquet files, schema unification, data cleaning, and feature engineering using Polars.
- `/modeling`: Includes Jupyter notebooks and/or Python scripts detailing the training, hyperparameter optimization (using Optuna and Genetic Algorithms), and evaluation of various churn prediction models (e.g., XGBoost, BiGRU).

## Technologies Used

- Python 3.12
- Polars
- scikit-learn
- XGBoost
- PyTorch (for BiGRU models)
- Optuna
- DEAP (for Genetic Algorithms)
- SHAP
- Pandas, NumPy, Matplotlib, Seaborn
- Jupyter Notebooks

## Getting Started / Reproducibility

(Optional: Include instructions if you want to guide the reviewer on how to run specific parts)

1.  The main experimental notebooks can be found in the `/modeling` directory. For example, `XGBoost_Optimization.ipynb` details the XGBoost model experiments.
2.  Data source: The project uses proprietary transaction data (approx. 150 GB) which is not included in this repository due to confidentiality.
