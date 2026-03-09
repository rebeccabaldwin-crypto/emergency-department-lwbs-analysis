# emergency-department-lwbs-analysis
Data analytics capstone project analyzing operational drivers of emergency department patients leaving without being seen (LWBS).

# Emergency Department Throughput Optimization

## Overview
This project analyzes operational drivers of patients leaving the emergency department without being seen (LWBS).

Using a dataset of 5,000 emergency department visits, the analysis explores how intake delays, staffing ratios, and patient acuity influence patient abandonment.

## Key Insights
- Long registration and triage waits significantly increase LWBS risk
- Low-acuity patients are more likely to leave during delays
- Higher nurse-to-patient ratios contribute to operational strain

## Predictive Modeling
A logistic regression model was built to predict LWBS risk using intake variables.

Model performance:
**ROC-AUC: 0.87**

## Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Scikit-learn

## Project File
See the full analysis in the Jupyter Notebook:
ER_LWBS.ipynb
