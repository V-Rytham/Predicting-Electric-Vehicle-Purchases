# Predicting Electric Vehicle Purchases

Kaggle Playground Series S6E9 | Binary classification | ROC-AUC

Baseline comparison of Logistic Regression and CatBoost for EV purchase intent.

## Validation results

| Model | ROC-AUC |
| --- | ---: |
| Logistic Regression | 0.937958 |
| CatBoost | 0.941471 |

Scores are from the saved Colab notebook on an 80/20 stratified holdout with seed 42. CatBoost uses this holdout for early stopping.

The notebook includes EDA, baseline models, feature importance, and submission generation. Use the [competition data](https://www.kaggle.com/competitions/playground-series-s6e9) to run it; the output `submission.csv` contains probabilities for `Will_Buy_EV = Yes`.

This is a baseline, not a tuned or cross-validated result. Feature importance measures predictive contribution, not causality.
