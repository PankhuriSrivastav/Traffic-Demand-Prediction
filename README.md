# HyperDrive - Traffic Demand Prediction

## Overview

Traffic demand forecasting solution developed for **Flipkart Gridlock Hackathon 2.0**. This project predicts normalized traffic demand across geospatial locations using advanced feature engineering, geospatial analysis, and ensemble machine learning models.

## Highlights

* Custom geohash decoding for spatial feature extraction
* Temporal feature engineering using cyclic time encodings
* K-Means clustering for traffic hotspot detection
* Leakage-free target encoding for time-series data
* Optuna-based hyperparameter optimization
* CatBoost + LightGBM ensemble model

## Model Performance

| Model                                  | Validation R² |
| -------------------------------------- | ------------- |
| LightGBM                               | 0.7762        |
| CatBoost                               | 0.7921        |
| Ensemble (60% CatBoost + 40% LightGBM) | 0.8042        |

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-Learn
* CatBoost
* LightGBM
* Optuna
* SHAP

## Project Structure

```text
├── Traffic Demand Prediction(Hyper Drive).ipynb
├── dataset/
├── results/
│   └── submission.csv
├── Flipkart_Gridlock_Methodology.pdf
├── README.md
└── requirements.txt
```

## Methodology

The solution incorporates:

* Spatial-temporal feature engineering
* Geohash-based location analytics
* Traffic hotspot identification using clustering
* Time-series aware validation
* Gradient boosting ensemble learning

A detailed explanation is available in **Flipkart_Gridlock_Methodology.pdf**.

## Team

**HyperDrive**

* Pankhuri Srivastava
* Swarda Kishor Sawale
