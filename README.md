# Car Price Prediction Project

# Overview
This assignment applies the CRISP-DM methodology to analyze and predict used car prices using the `vehicles.csv` dataset. 
The project focuses on transforming raw data into meaningful insights and building predictive models for price estimation.

# Objective
To develop a machine learning framework that predicts used car prices based on key attributes such as age, mileage, condition, and fuel type.

# Methodology
1. Data Cleaning:
  - Removed unnecessary columns
  - Handled missing values
2. Feature Engineering:
  - `car_age`
  - `mileage_per_year`
  - `condition_encoded`
  - `log_price`
3. Exploratory Data Analysis (EDA):
  - Identified trends using Matplotlib and Seaborn
  - Observed strong influence of age, mileage, condition, and fuel type on price
  4. Model Development:
  - Linear Regression
  - Random Forest Regression
  - Implemented using Scikit-learn pipelines (preprocessing, encoding, scaling)

# Results
1. Linear Regression:
  - R² ≈ 0.69
  - Stable performance across cross-validation
2. Random Forest:
  - Lower performance compared to Linear Regression
  - Limited improvement after GridSearchCV tuning

# Key Insights
- Depreciation-related features (car age and mileage) are the most significant predictors
- Vehicle condition and fuel type also contribute meaningfully to price variation

# Tools Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Conclusion
The project successfully demonstrates a data-driven predictive framework for used car pricing while providing actionable insights into the key factors influencing vehicle value.
