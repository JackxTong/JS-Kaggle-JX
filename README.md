# JS-Kaggle

Create a venv, then activate venv and install requirements with
```bash
python3 -m pip install -r requirements.txt`
```

Need to have `train.parquet` (around 7Gb) and `valid.parquet` in root directory

## Training MLP:
`jx-train-nn.ipynb`

Will save weights as `result.pkl` into root directory

## Training XGB baseline
`jx-train-xgb-baseline.ipynb`

## Training  multiple XGB on random feature subsets
`rand-xgb-forest.ipynb`

## Inference with MLP (cannot run yet)
`jx-inference-nn.ipynb`