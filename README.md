# Titanic-Classification

## Project Overview
Predicting Titanic passenger survival using Logistic Regression, 
Bagging, and Boosting — implemented from scratch (NumPy) and 
with scikit-learn.

## Structure
- A_minimal_prep_and_split.ipynb — Data preprocessing & split
- B_from_scratch_models.ipynb — NumPy implementations
- C_library_models.ipynb — Sklearn implementations  
- D_report.pdf — Technical analysis report

## Setup & Execution
Run notebooks in order: A → B → C → D

## Package Versions
- Python 3.12
- numpy 1.26
- pandas 2.0
- scikit-learn 1.6
- matplotlib 3.7

## Global Seed
All notebooks use seed=42 for reproducibility.

## Dataset
Titanic — loaded directly from:
https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv

## Results
Best model: Random Forest — 81.01% accuracy | 0.8464 AUC
