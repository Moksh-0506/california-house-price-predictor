# California House Price Predictor

## Overview

This project is an end-to-end Machine Learning application that predicts California housing prices using the California Housing Dataset.

The project includes data preprocessing, feature transformation, model training, model persistence, and prediction on new housing data.

## Features

* Data preprocessing using Scikit-Learn Pipelines
* Missing value handling with SimpleImputer
* Feature scaling using StandardScaler
* Categorical feature encoding using OneHotEncoder
* Stratified sampling for balanced training data
* Random Forest Regression model
* Model and pipeline persistence using Joblib
* Prediction on new unseen datasets

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-Learn
* Joblib

## Project Workflow

1. Load California Housing Dataset
2. Perform stratified sampling based on income categories
3. Preprocess numerical and categorical features
4. Train a Random Forest Regressor
5. Save trained model and preprocessing pipeline
6. Load saved model for inference
7. Generate house price predictions for new data

## Files

## Files

- `housing.csv` - Training dataset
- `input.csv` - Input dataset used for prediction
- `output.csv` - Generated predictions
- `model.pkl` - Trained Random Forest model
- `pipeline.pkl` - Saved preprocessing pipeline
- `main.py` - Main application script

## Model Files

The trained model files are not included in this repository because of GitHub file size limits.

Run the project once to automatically train and generate:

- model.pkl
- pipeline.pkl

## How to Run

Install dependencies:

```bash
pip install pandas numpy scikit-learn joblib
```

Run:

```bash
python main.py
```

## Author

Moksh
