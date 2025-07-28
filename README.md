# 🌦️ Weather AUS – Rain Prediction Using Machine Learning

This project focuses on predicting whether it will rain tomorrow in Australia based on historical weather data. The dataset includes observations from various weather stations across the country, with features like temperature, humidity, wind, and rainfall.

## 📁 Dataset
- **Source:** [Kaggle - Rain in Australia](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package)
- **Features:** 23 columns including `RainToday`, `RainTomorrow`, `Humidity`, `Pressure`, `WindGustDir`, etc.
- **Target:** `RainTomorrow` (Yes/No)

## 📌 Project Highlights
- 📊 **Exploratory Data Analysis**: Understanding patterns and correlations in the weather features.
- 🧼 **Data Preprocessing**:
  - Handling missing values
  - Encoding categorical features
  - Feature scaling
- 🤖 **Modeling**:
  - Logistic Regression
  - Random Forest Classifier
  - XGBoost Classifier
- 📈 **Evaluation Metrics**:
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC-AUC Score

## 🚀 Results
- Best model: **XGBoost**
- Accuracy: **~87%**
- ROC-AUC: **0.91**

## 🛠️ Tech Stack
- Python
- Jupyter Notebook
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- XGBoost

## 📁 Folder Structure (Suggested)
