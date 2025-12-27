# Car Price Predictor – Machine Learning

This project was completed as part of a Machine Learning Internship (Week 2).

## Objective
Build a regression-based machine learning model to predict used car prices based on:
- Car name
- Company
- Year of manufacture
- Kilometers driven
- Fuel type

## Dataset
- Source: Quikr used car listings
- Raw data cleaned to handle:
  - Missing values
  - Text-based numeric fields
  - Inconsistent naming
  - Outliers

## Approach
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- One-Hot Encoding for categorical variables
- Linear Regression using sklearn
- Model evaluation using R² score
- Pipeline creation and model serialization using pickle

## Model Performance
- Best R² Score: ~0.89 on test data

## Sample Prediction
```python
['Maruti Suzuki Swift', 'Maruti', 2019, 100, 'Petrol']

Predicted Price: ₹456,670
```

## Files in Repository

1. Car_Price_Predictor.ipynb – Full notebook

2. Cleaned_Car_data.csv – Cleaned dataset

3. quikr_car.csv – Raw dataset

4. CarPricePredictor_Model.pkl – Trained model

## Status: Week 2 Internship Task Completed
