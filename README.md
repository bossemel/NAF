# NAF Python 3
This repository contains a modification of the [NAF Repository]([here](https://github.com/CW-Huang/NAF). ) for experiments for the [Neural Autoregressive Flows](https://arxiv.org/abs/1804.00779) paper by Huang et al. The code was adjusted for Python 3 and a bug was fixed concerning the dimensionality of the DDSF.

To download datasets, please modify L21-24 of `download_datasets.py`. 

## To install:

```
python3 -m venv .env
source .env/bin/activate
pip install -r requirements.txt
python download_datasets.py
```

## To run experiments: 
```
python maf_experiments.py
```
