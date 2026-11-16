# DSC8307 Assignment 2 - Data Mining, Modeling and Analytics

This repository contains two reproducible Jupyter notebooks:

1. `Project_1_Wholesale_Customer_Segmentation.ipynb`
2. `Project_2_Credit_Card_Fraud_Detection.ipynb`

## Data files
Place the supplied files in the repository root:
- `wholesale-customers.csv`
- `creditcard.csv`

## Setup

python -m venv .venv
# Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter lab


## Analytical design
- Project 1 compares K-means, Ward hierarchical clustering and DBSCAN after log transformation and robust scaling. It assesses cluster tendency, internal validity, stability, interpretability and business actionability.
- Project 2 withholds `Class` from model fitting, compares a statistical baseline, normalized cluster distance and Isolation Forest, and evaluates the resulting rankings using PR-AUC, ROC-AUC, Precision@K, Recall@K and Lift@K.

## Reproducibility
Random seeds are fixed. Data preparation is shown explicitly in the notebooks.
