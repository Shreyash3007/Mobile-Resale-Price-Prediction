# Smartphone Price Prediction

A small machine-learning project that estimates phone prices from specifications using a Random Forest regressor.

## What is included

- `Predictor`: the Python training and evaluation script; the filename has no extension.
- `cleaned_final.csv`: the input dataset.
- `regression line .jpeg`: a saved plot.

The script uses an 80/20 train/test split with `random_state=42`, trains 100 trees, and prints R², RMSE, and feature importance. Inputs include specification score, battery, RAM, storage, camera specifications, and encoded brand/processor fields.

## Run locally

```bash
python -m pip install pandas numpy scikit-learn matplotlib seaborn
python Predictor
```

Run from the repository root so the script can locate the CSV. The plot opens in a local window.

## Limits

This is a learning experiment, not a validated resale valuation service. The code targets the dataset’s `price` column; the repository does not establish that this represents real resale transactions. Earlier approximate headline scores are omitted because no fresh reproducible run is recorded here. Dependency versions are not pinned.

Built by [Shreyash Sakhare](https://github.com/Shreyash3007).
