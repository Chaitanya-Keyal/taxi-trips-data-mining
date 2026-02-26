# Data Mining

Course project repository for **CS F415 Data Mining**.

## Project Context

This project analyzes smart-city taxi/rideshare trip data to find actionable ways to reduce traffic congestion and improve public transportation planning.

## Repository Structure

- `data/`: raw and processed datasets
- `notebooks/`: Jupyter notebooks for EDA, preprocessing, modeling, and evaluation
- `figures/`: generated plots and visual outputs
- `reports/`: proposal and final report files

## Typical Workflow

1. Explore and profile data in `notebooks/`.
2. Clean data and engineer features (time-based fields, zone patterns, etc.).
3. Train and evaluate models for selected data mining tasks.
4. Save key charts to `figures/`.
5. Summarize findings and business recommendations in `reports/`.

## Dataset

- Source: <https://www.kaggle.com/competitions/nyc-taxi-trip-duration/data?select=train.zip>

## Suggested Setup

```bash
python -m venv .venv
source .venv/bin/activate
pip install -U pip jupyter pandas numpy scikit-learn matplotlib seaborn
jupyter notebook
```
