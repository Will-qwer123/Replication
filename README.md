## Code statement
## Mandate
The mandate code was based on the original code provided by Matt Ryan.
This code is the original code provided by Matt Ryan. I used this code directly.
## Feature Importance Analysis
For the feature importance figures, AI assistance was used only for colour selection, spacing and font size adjustment.

## Plots
In Plots file, mask_wearing_feature_importance_top10.png and general_protective_behaviours_feature_importance_top10.png are the final version plots.

# COVID-19 Protective Behaviour Replication

This repository contains the code and analysis for replicating the study:

Ryan et al. (2025), *Face mask mandates alter major determinants of adherence to protective health behaviours in Australia*.

## Project Overview

The project investigates factors associated with:

- Face mask wearing behaviour
- General protective behaviours

before and after mask mandates in Australia during the COVID-19 pandemic.

The replication includes:

- Data cleaning and preprocessing
- Mask mandate period definition
- Feature engineering
- Machine learning modelling
- Cross-validation and test set evaluation
- Feature importance analysis

## Datasets

The project uses two main datasets:

1. Imperial College London YouGov COVID-19 Behaviour Tracker
2. Oxford COVID-19 Government Response Tracker (OxCGRT)

## Models

The following models were implemented:

- Logistic Regression
- Classification Tree
- Random Forest
- XGBoost

## Evaluation Metrics

Models were evaluated using:

- ROC AUC
- Precision
- Recall
- Accuracy
- F1-score

## Feature Importance

Feature importance analysis was conducted using XGBoost models with repeated bootstrap resampling.

## Repository Structure

```text
data/       # Raw and processed datasets
notebooks/  # Jupyter notebooks
results/    # Figures and model outputs
scripts/    # Python scripts
