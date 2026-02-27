# Confidence vs Correctness: Machine Learning Reliability Study

## Overview
This project investigates machine learning model reliability beyond traditional accuracy metrics.  
It analyzes how prediction confidence relates to correctness under corruption and distribution shift scenarios.

## Objectives
- Analyze confidence vs correctness distribution
- Evaluate model calibration
- Study reliability under feature noise
- Study reliability under label corruption
- Evaluate robustness under missing data
- Analyze performance under distribution shift
- Compare Logistic Regression and Random Forest models

## Dataset
Adult Income Dataset

## Experiments Conducted
1. Baseline model evaluation
2. Confidence distribution analysis
3. Calibration curve assessment
4. Reliability vs training data size
5. Feature noise corruption
6. Label corruption experiment
7. Missing data robustness test
8. Distribution shift simulation
9. Model comparison analysis

## Key Findings
- Models can remain highly confident even when incorrect.
- Calibration degrades significantly under corruption.
- Distribution shift impacts both accuracy and confidence reliability.

## Repository Structure
- `confidence_reliability.ipynb` → Main implementation
- `data/` → Dataset
- `figures/` → Experiment plots
- `report/` → Final PDF report
- `project timeline.md` → Development timeline

## Tools Used
- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib

Author: Hariharan D
