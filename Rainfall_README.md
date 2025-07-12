# Rainfall Prediction Report

## 1. Objective
Summarize the goal: predict precipitation using weather features (temperature, humidity, wind speed, etc.).

## 2. Dataset Description
- Name: Austin Weather Dataset
- Features: Temperature, Humidity, Wind Speed, Visibility, Dew Point, Precipitation
- Target: PrecipitationSumInches

## 3. Data Preprocessing
- Removed irrelevant columns (mention which ones)
- Replaced "T" (trace amounts) and "-" (missing) with 0 or NaN
- Handled missing values using appropriate strategies

## 4. Model Implementation
- Applied Linear Regression using `sklearn`
- Split dataset into train and test sets
- Evaluated model performance using R² and MAE

## 5. Visualizations
- Precipitation over time
- Correlation heatmap
- Scatter plots: Temperature vs Precipitation, Humidity vs Precipitation, etc.

## 6. Conclusion
- Summarize findings
- Comment on model accuracy and observed trends

## 7. Future Scope
- Try advanced models (e.g., Random Forest, XGBoost)
- Add more features (e.g., pressure, seasonality)
