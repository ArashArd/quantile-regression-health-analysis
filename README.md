# Quantile Regression for Population Health Analysis (R)

This repository demonstrates a clean, reproducible workflow for analysing health-related outcomes using **quantile regression** in R.

## What this project shows
- Data preparation and sensible feature selection
- Exploratory analysis with clear visualisation
- Quantile regression (effects across the outcome distribution)
- Interpretation in plain language
- Basic modelling extension (logistic regression example)

## Data
The dataset used here is an **anonymised subset (n = 1000)** derived from a larger adolescent health study.
Only a limited set of anthropometric, demographic, and family-level variables were retained, and identifiers were removed.
The data is shared solely for demonstrating analytical workflows.

## Tools
R, tidyverse, ggplot2, quantreg, broom

## Files
- `quantile_regression_health_analysis.Rmd` – main analysis
- `data/health_sample_data_1000.csv` – anonymised sample used in the notebook

- ## Results snapshot

The analysis shows that associations between body fat and BMI
tend to be stronger at higher quantiles of the BMI distribution,
highlighting heterogeneity that is not captured by mean regression.
Parental obesity indicators also show stronger effects among
higher-BMI individuals.
