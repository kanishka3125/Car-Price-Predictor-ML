# Car Price Predictor – Machine Learning

This project was completed as part of a **Machine Learning Internship (Week 2)**.  
The goal was to build an end-to-end regression pipeline to predict used car prices using structured tabular data.

## Objective
Build a regression-based machine learning model to predict used car prices based on:
- Car name
- Company
- Year of manufacture
- Kilometers driven
- Fuel type

## Dataset
**Source:** Quikr used car listings
The raw dataset required extensive cleaning due to:
- Missing values
- Text-based numeric fields (e.g., `"Ask For Price"`, `"45,000 kms"`)
- Inconsistent naming conventions
- Outliers in price values

## 🧹 Data Preprocessing
- Removed invalid and missing values
- Converted text-based numerical columns to integers
- Standardized car names to reduce categorical noise
- Filtered extreme outliers in price

---

## 🧠 Approach
- Exploratory Data Analysis (EDA)
- Feature engineering and selection
- One-Hot Encoding for categorical variables
- Linear Regression using **scikit-learn**
- Pipeline-based model training
- Model evaluation using **R² score**
- Model serialization using **pickle**

## 📈 Model Performance
- **Best R² Score:** ~0.89 on test data

---

## 🔍 Sample Prediction
**Input:**
```python
['Maruti Suzuki Swift', 'Maruti', 2019, 100, 'Petrol']

Predicted Price: ₹456,670
```

## Files in Repository

1. Car_Price_Predictor.ipynb – Complete Project notebook

2. Cleaned_Car_data.csv – Cleaned dataset

3. quikr_car.csv – Raw dataset

4. CarPricePredictor_Model.pkl – Trained machine learning model

## Status: Week 2 Internship Task Completed
