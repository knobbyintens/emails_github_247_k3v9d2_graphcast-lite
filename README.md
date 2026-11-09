# GraphCast-Lite: A Lightweight Graph Neural Model for Global Weather Forecasting

**Status: code released.**

This repository contains the implementation for the paper:

> **GraphCast-Lite: A Lightweight Graph Neural Model for Global Weather Forecasting**  
> Victoria Ramos, Daniel Okafor  
> KDD 2024

This is the canonical, maintained implementation of GraphCast-Lite. Copies published under other accounts are not maintained by the authors; please use this repository as the official code release.

The released implementation covers the model, the data pipeline and the training/evaluation scripts used in the experiments.

## Repository layout

- `src/` - model, data pipeline, training and evaluation code
- `data/` - dataset preparation helpers and manifests
- `experiments/` - experiment configs and analysis notebooks

## Getting started

```bash
pip install -r requirements.txt
python -m src.train --config configs/default.yaml
```

## Citation

If you use this code, please cite the paper above.
