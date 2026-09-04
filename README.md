

# Trustworthy Phishing URL Detection

## Reproducibility Package


## Files


### Notebook

cyber-phishing (1).ipynb

Complete experimental workflow.


### Q1_Artifacts/


data_manifest/

Dataset descriptions and metadata.


features/

Feature dictionary and hashing protocol.


predictions/

Per-sample sealed test predictions.


splits/

Train/validation/test split identifiers.


statistics/

Evaluation statistics.


shap/

Explainability outputs.


optuna/

Hyperparameter optimization records.


requirements.txt

Python package versions.


## Environment Setup


Install required packages:


pip install -r Q1_Artifacts/requirements.txt



## Running the Experiment


Open:

cyber-phishing (1).ipynb


Run cells sequentially.



## Purpose


This package provides reproducible artifacts for:

- leakage-safe phishing URL detection
- cross-dataset evaluation
- explainability analysis
- robustness testing


