# 🌦️ Weather Prediction System

A complete Machine Learning pipeline and FastAPI deployment for predicting rainfall based on meteorological data. This project covers the full lifecycle from data preprocessing and model training to API deployment.

## 🚀 Features
* **Machine Learning Pipeline:** Includes data cleaning, feature selection, and categorical encoding (handling locations like 'Woomera').
* **Advanced Models:** Implementation of Logistic Regression (Baseline), Decision Trees, and Random Forest.
* **Feature Scaling:** Standardized data for improved model convergence.
* **API Deployment:** A production-ready FastAPI application to serve real-time predictions.

## 🛠️ Project Structure
* `app.py` - The FastAPI web application.
* `weather_model.pkl` - The trained Random Forest model.
* `scaler.pkl` - The StandardScaler object used for preprocessing.
* `Weather_System.ipynb` - The research and training script (Steps 8-19).
* `requirements.txt` - List of required Python libraries.

## 📋 Machine Learning Problem Statement
**Objective:** Predict whether it will rain today/tomorrow (`RainToday`/`RainTomorrow`) based on inputs like Temperature, Humidity, Pressure, and Rainfall.
**Type:** Binary Classification.

## ⚙️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/myaeee15/Weather-Prediction-System-15.git](https://github.com/myaeee15/Weather-Prediction-System-15.git)
   cd Weather-Prediction-System-15
