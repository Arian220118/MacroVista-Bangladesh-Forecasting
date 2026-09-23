# MacroVista: Bangladesh Macro-Financial Forecasting

This repository contains the supplementary dataset, source code, and reproducibility materials for the study:

**“MacroVista: A Hybrid Trend-Aware Explainable AI Framework for Forecasting the Future of Business in Bangladesh Using Two Decades of Macroeconomic and Financial Indicators.”**

## Overview

MacroVista is a trend-aware and explainable forecasting framework developed for one-month-ahead prediction of the BDT/USD exchange rate using monthly macroeconomic and financial indicators from Bangladesh.

The framework integrates temporal exchange-rate dynamics, macro-financial predictors, leakage-safe feature selection, Ridge regularization, explainable AI, and robustness analysis.

## Repository Contents

- `Final dataset.csv` — processed monthly macro-financial dataset used in the study
- `MacroVista_Forecasting.ipynb` — complete forecasting, evaluation, explainability, robustness, and ex-ante forecasting notebook
- `requirements.txt` — Python dependencies required to reproduce the analysis

## Dataset

The dataset contains monthly macro-financial indicators covering real-sector, external-sector, and monetary-financial conditions in Bangladesh.

The main variables include inflation, industrial/manufacturing activity, BDT/USD exchange rate, international reserves, exports, imports, trade balance, remittances, broad money, policy rate, stock-market indicators, and private-sector credit.

The underlying indicators were compiled from publicly accessible institutional data sources, primarily the Asian Development Bank’s Asia Regional Integration Center (ADB-ARIC), and subsequently cleaned, harmonized, and transformed for forecasting analysis.

## Forecasting Models

The study evaluates six main forecasting models:

1. SARIMA
2. Random Forest
3. XGBoost
4. LightGBM
5. Support Vector Regression
6. MacroVista

Persistence, Drift, and ETS are additionally used as diagnostic baselines.

## Reproducibility

Install the required Python packages using:

```bash
pip install -r requirements.txt
