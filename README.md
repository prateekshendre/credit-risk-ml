# Credit Risk Model

Classify borrower default risk using tabular data with SQL feature prep and a Python ML pipeline.

## Problem
Lenders need early signals of default risk to price credit and manage exposure.

## Solution
End to end workflow
* SQL for feature engineering and joins
* Python pipeline with train test split, scaling, and models
* Clear metrics and charts for model quality

## Data
* Placeholder  replace with your chosen dataset name and link
* Typical fields  demographics, income, credit history, delinquency flags, utilization

## Methods
* Baseline  logistic regression
* Tree based model  random forest or gradient boosted trees
* Evaluation  AUC, PR curve, confusion matrix, KS, recall at fixed precision

## Repo layout
* data  small sample for demo
* sql  feature creation queries
* notebooks  model build and evaluation
* visuals  ROC, PR, feature importance
* requirements.txt

## Results to report
* AUC and PR at a glance
* Cost aware threshold choice
* Top features and business takeaways

## Next steps
* Add explainability with SHAP
* Calibrate probabilities with isotonic or Platt scaling
* Time based split for more realistic validation
# credit-risk-ml
Machine learning project analyzing credit risk using Python, SQL, and scikit-learn.
