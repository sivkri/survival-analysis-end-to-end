# Survival Analysis End-to-End

This project demonstrates end-to-end survival analysis using classical and deep learning models on clinical data (e.g., lung cancer dataset). It includes data preprocessing, model building (Cox PH, RSF, DeepSurv), evaluation, and interpretation.


## Models Used
- Cox Proportional Hazards (lifelines)
- Random Survival Forest (scikit-survival)
- GBM model

## Evaluation Metrics
- Concordance Index
- Log-Rank Tests
- Kaplan-Meier Curves


## Data Handling & Preprocessing
Cleaned column names and handled missing values appropriately.

Encoded categorical variables consistently.

Label encoding logic is sound for small category values.

## Main libraries:

`lifelines`, `scikit-survival`, `matplotlib`, `seaborn`

## Features

End-to-end analysis from data cleaning to evaluation

Rich markdown annotations for learning

Classical + modern survival models

Explainability (e.g., hazard ratios, feature importance)