# xgboost‑adaboost‑Task

## Overview
A demonstration of **XGBoost** and **AdaBoost** applied to a dataset (e.g., car details from Car Dekho), focusing on comparative analysis of both boosting algorithms using Python.

## Dataset
- `CAR DETAILS FROM CAR DEKHO.csv`: Contains features like price, brand, model, year, etc.
- Source: CarDekho listing dataset.

## Notebooks
- **`main.ipynb`**:  
  - Data loading and exploratory data analysis (EDA)  
  - Data preprocessing (cleaning, encoding, train-test split)  
  - Modeling using `XGBoostClassifier` and `AdaBoostClassifier`  
  - Evaluation: accuracy, precision, recall, F1-score, ROC-AUC.

- **`visualisation.ipynb`**:  
  - Visual exploration of feature distributions  
  - Model performance comparison plots  

## Setup
Install required packages:
```bash
pip install -r requirements.txt
```

## How to Run
1. Launch Jupyter Notebook:
```bash
jupyter notebook
```
2. Open and run:
   - `main.ipynb` to train and evaluate models.
   - `visualisation.ipynb` for insights and plots.

## Results
- XGBoost vs. AdaBoost comparison on accuracy and AUC.
- Key features and performance differences.

## Requirements
See `requirements.txt` for exact library versions.
