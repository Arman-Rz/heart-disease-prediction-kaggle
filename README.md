# Heart Disease Prediction

**Author:** Arman Rashidizadeh  
**Date:** January 2026  
**Project:** Kaggle Playground Competition

## Project Overview

This project explores machine learning models for predictiong heart disease risk using a structured clinical dataset.  

## Models used:
- CatBoost
- LightGBM
- XGBoost

## Training Strategy:
- K-Fold cross validation
- Hyperparameter tuning
- Multi-seed training
- Model ensembling

The final prediction is an ensemble of the three models.  

## Tools:
Python, Scikit-learn, Optuna, CatBoost, LightGBM, XGBoost

## Repository Structure

```
heart-disease-prediction-kaggle
│
├── data/
├── notebooks/
│   ├── 01_catboost.ipynb
│   ├── 02_lightgbm.ipynb
│   ├── 03_xgboost.ipynb
│   └── 04_ensemble.ipynb
│
|── requirements.txt
└── README.md
```

## Installation & Setup

1. Clone the repository:

``` bash
    git clone https://github.com/Arman-Rz/heart-disease-prediction-kaggle.git
    cd heart-disease-prediction-kaggle
```

2. Install dependencies

``` bash
    pip install -r requirements.txt
```

3. (Optional) If using Kaggle API to fetch the dataset:

``` bash
    kaggle competitions download -c playground-series-s6e2
    unzip playground-series-s6e2.zip -d data/
```

## License

This project is released for academic and educational purposes only.
All dataset rights belong to the original Kaggle authors.