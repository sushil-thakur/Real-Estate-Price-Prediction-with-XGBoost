Real Estate Price Prediction with XGBoost
Overview
This project predicts real estate prices using XGBoost based on building features like height, floors, area, age, and location. It processes multiple datasets, encodes locations, scales features, trains the model, and forecasts prices for the next 10 years with visualization.

Features
Data cleaning and merging from 3 datasets

Location target encoding

Feature scaling with StandardScaler

XGBoost regression with hyperparameter tuning

10-year price forecasting with growth rate

Price output in words and bar chart visualization

Saving model, scaler, and location encoding for reuse

Usage
Run training script to prepare data, train model, and save artifacts:

xgboost_real_estate_model.pkl

scaler.pkl

location_encoding.pkl

Load saved files for prediction on new data:

Encode location using saved encoding

Scale features with saved scaler

Predict with saved model
