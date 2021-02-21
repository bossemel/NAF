# NAF Python 3
Modification of the experiments for the [Neural Autoregressive Flows](https://arxiv.org/abs/1804.00779) paper by Huang et al. for Python 3. Find the original repository [here](https://github.com/CW-Huang/NAF). 

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
