
# 🌫️ Predicting Air Quality Index (AQI)

This project focuses on predicting the Air Quality Index (AQI) based on various atmospheric pollutants and environmental conditions. It utilizes regression techniques to forecast AQI levels and help in understanding the impact of pollutants on air quality.

## 📁 Repository Structure

```
Predicting-Air-Quality-Index/
├── aqi_prediction.ipynb      
├── air_quality_data.csv      # Dataset used (if available)
├── README.md                 # Project documentation
```

## 📌 Problem Statement

Rising air pollution levels pose a serious threat to health and the environment. Predicting the Air Quality Index in advance can help inform policy decisions, health advisories, and public awareness campaigns. The objective of this project is to build a machine learning model to predict AQI based on historical data.

## 🔧 Tools & Libraries Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn (data visualization)
- Scikit-learn (for regression modeling)
- XGBoost / Random Forest Regressor (optional)
- Jupyter Notebook

## 📊 Workflow

1. **Data Collection & Cleaning**
   - Loading CSV data
   - Handling missing/null values
   - Removing irrelevant features

2. **Exploratory Data Analysis (EDA)**
   - Trend analysis of pollutants like PM2.5, PM10, NO2, SO2, CO, O3
   - Correlation analysis with AQI

3. **Feature Engineering**
   - Encoding categorical variables (if any)
   - Normalization or standardization

4. **Model Building & Evaluation**
   - Linear Regression
   - Random Forest Regressor
   - XGBoost Regressor
   - Evaluation using MAE, MSE, RMSE, R²

   ```

## 💡 Insights

- PM2.5 and PM10 are usually the strongest predictors of AQI.
- Models like Random Forest and XGBoost typically outperform linear models.

