## Phishing URL Detection 
 
## Reproducibility Package 
 
This repository contains the complete reproducibility package for the
leakage-controlled phishing URL detection framework, including experimental
code, dataset information, evaluation artifacts, explainability outputs,
and submission-ready results.


## Files 
 
 
### Datasets
 
datasets/
 
Contains dataset descriptions, metadata, and required information for
reproducing the experiments.
 
Includes:

- dataset descriptions
- dataset sources
- feature availability information

 
### Notebook
 
notebooks/
 
cyber-phishing-code.ipynb 
 
Complete experimental workflow including:

- data preprocessing
- leakage screening
- feature analysis
- model development
- XGBoost optimization
- sealed-test evaluation
- cross-dataset transfer evaluation
- explainability analysis
- sensitivity analysis

 
### Q1_Artifacts/
 
 
data_manifest/
 
Dataset descriptions and metadata.
 
 
features/
 
Feature dictionary and feature representation information.
 
 
predictions/
 
Per-sample sealed test predictions.
 
 
splits/
 
Train/validation/test split identifiers for leakage-controlled evaluation.
 
 
statistics/
 
Evaluation statistics, uncertainty estimation, and confidence intervals.
 
 
shap/
 
Explainability outputs and SHAP feature attribution results.
 
 
optuna/
 
Hyperparameter optimization records.
 
 
requirements.txt
 
Python package versions required for reproducing the experiments.
 
 
### OUTPUT_SUBMISSION_PACKAGE/
 
Contains all manuscript-related output files.
 
 
figures/
 
Publication-ready figures including:

- workflow diagram
- model comparison
- SHAP analysis
- calibration curve
- sensitivity analysis
- external transfer comparison
 
 
tables/
 
Publication-ready result tables including:

- dataset summary
- leakage screening results
- model screening results
- sealed-test performance
- cross-dataset transfer performance
- calibration results
- sensitivity analysis results
 
 
 
## Environment Setup 
 
 
Install required packages:
 
```bash
pip install -r Q1_Artifacts/requirements.txt