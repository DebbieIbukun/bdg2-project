# 🔋 BDG2 Energy Consumption Prediction

This project uses the **BDG2 dataset** to model and predict energy consumption across multiple building types. It applies machine learning techniques to forecast usage based on historical data, weather variables, and building characteristics — with the goal of improving energy efficiency and load planning.

---

## 📦 Dataset

- **Source**: BDG2 
- **Contents**:
  - Hourly energy consumption data
  - Weather variables (temperature, humidity, solar radiation)
  - Building metadata (type, area, occupancy, HVAC systems)

---

## 🎯 Objectives

- Predict future energy consumption for different building types
- Identify key drivers of energy usage
- Improve forecasting accuracy using regression models
- Visualize consumption trends for operational insights

---

## 🧠 Methodology

### 🔍 Data Preprocessing
- Handled missing values and outliers
- Normalized continuous variables
- Encoded categorical features

### 📊 Feature Engineering
- Created lag features and rolling averages
- Derived interaction terms (e.g., temp × occupancy)
- Integrated time-based features (hour, day, season)

### 🤖 Modeling
- Trained multiple regression models:
  - LSTM Model
  - Random Forest Regressor
  - XGBoost
- Evaluated using MAE, and RMSE scores
- Selected best model based on cross-validation performance

### 📈 Visualization
- Plotted actual vs predicted consumption
- Heatmaps of usage by time and building type
- Feature importance charts

---

## 🧪 Results

- Best model: **LSTM Model**
- Forecasting error reduced to **RMSE: 4.5 kWh**
- Top predictors: outdoor temperature, occupancy, building area
- Insights used to recommend energy-saving strategies for high-consumption zones

---

## 🛠 Tools & Technologies

- Python (Pandas, NumPy, Scikit-learn)
- Jupyter Notebook
- Matplotlib & Seaborn
- Plotly (for dashboarding)
- Git & GitHub (version control)

---

