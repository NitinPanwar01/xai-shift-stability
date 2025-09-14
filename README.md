# XAI Shift Stability (STeP-X)
A zero-cost, reproducible protocol to measure and improve LIME/SHAP explanation stability under distribution shift on tabular data.

## Structure
- `data/` – raw/processed datasets (not tracked)
- `src/` – dataset loaders, models, explainers, metrics, defenses
- `experiments/results/` – CSV metrics
- `experiments/figs/` – plots
- `notebooks/` – Colab/analysis notebooks

## Quickstart (Google Colab)
1. Open the starter notebook in `notebooks/`.
2. Run cells to mount Drive, install deps, and reproduce baseline results.

## Goals
- Standardized stability metrics: Kendall τ, top-k overlap, local cosine, flip-rate
- Shifts: covariate, prior, label-noise
- Free defenses: binning, calibration, regularization, (optional) monotonic constraints
