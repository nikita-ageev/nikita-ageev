# Credit models: from ranking to decisions

## The question

Does a higher AUC necessarily imply a better lending decision? How do calibration and distribution changes affect a threshold policy?

## Public experiments

1. [From AUC to Money — Cutoff Economics](https://www.kaggle.com/code/truenikita/home-credit-from-auc-to-money-cutoff-economics) compares predictive scores with decision economics under stated assumptions.
2. [PD Calibration — AUC Is Not Enough](https://www.kaggle.com/code/truenikita/home-credit-pd-calibration-auc-is-not-enough) studies the distinction between ranking and probability quality.
3. [PSI, Drift and Re-setting the Cutoff](https://www.kaggle.com/code/truenikita/home-credit-psi-drift-and-re-setting-the-cutoff) examines monitoring signals and decision thresholds under constructed distribution changes.

## How to assess the work

Read the data split, model and calibration procedure, economic assumptions, sensitivity analysis and limitations before interpreting the charts. Reproduce the notebooks in the declared environment and compare outputs with the published version. They are CPU notebooks on the public Home Credit competition data; access to that data remains subject to its rules.

## Limits

These are educational experiments with public data. Economic parameters are illustrative. Constructed drift scenarios are not a dated panel of a real lender's portfolio. No employer figures, customer records or claims of realised bank profit are included. A useful result is a reproducible decision experiment, including cases where a prediction improvement does not translate into a material business gain.
