# JS-Kaggle

Create a venv, then activate venv and install requirements with
```bash
python3 -m pip install -r requirements.txt
```

Need to have `train.parquet` (around 7Gb) and `valid.parquet` in root directory

## Training MLP:
`jx-train-nn.ipynb`

## Training XGB baseline
`jx-train-xgb-baseline.ipynb`

## Training  multiple XGB on random feature subsets
`rand-xgb-forest.ipynb`

## Inference with MLP (cannot run yet)
`jx-inference-nn.ipynb`


https://github.com/evgeniavolkova/kagglejanestreet

https://www.kaggle.com/code/eivolkova/public-lb-6th?scriptVersionId=217330222

https://www.kaggle.com/competitions/jane-street-real-time-market-data-forecasting/writeups/evgeniia-grigoreva-private-lb-8th-solution

https://www.kaggle.com/competitions/jane-street-real-time-market-data-forecasting/writeups/private-58th-tabm-autoencodermlp-with-online-train