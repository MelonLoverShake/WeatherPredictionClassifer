# 🌦️ Weather Prediction Machine Learning Model

A comprehensive machine learning solution for predicting weather conditions using historical meteorological data. This project trains a Random Forest classifier to forecast weather summaries based on various atmospheric parameters.

## 📊 Features

- **Multi-feature Weather Analysis**: Uses temperature, humidity, wind speed, pressure, visibility, and cloud cover data
- **Automated Data Preprocessing**: Handles missing values, rare classes, and feature scaling
- **Random Forest Classification**: Robust ensemble learning approach for accurate predictions
- **Comprehensive Evaluation**: Includes accuracy metrics, confusion matrices, and feature importance analysis
- **Model Persistence**: Save and load trained models for production use
- **Google Colab Compatible**: Ready-to-use notebook for cloud-based training

## 🎯 What It Predicts

The model predicts weather conditions (e.g., "Partly Cloudy throughout the day", "Rain", etc.) based on:
- Temperature (actual and apparent)
- Precipitation type and amount
- Humidity levels
- Wind speed and bearing
- Atmospheric pressure
- Visibility and cloud cover

## 🚀 Quick Start

1. Upload your weather dataset CSV to Google Colab
2. Run all cells in the notebook
3. Get instant predictions with trained model

## 📈 Model Performance

- Automatic train-test split (80/20)
- Stratified sampling for balanced class distribution
- Feature importance visualization
- Detailed classification reports

## 🛠️ Tech Stack

- **Python 3.x**
- **scikit-learn** - Machine learning algorithms
- **pandas** - Data manipulation
- **matplotlib & seaborn** - Visualizations
- **NumPy** - Numerical computing

## 📦 Output

- Trained model (`weather_model.pkl`)
- Feature scaler (`scaler.pkl`)
- Label encoder (`label_encoder.pkl`)
- Comprehensive training metrics and visualizations

---

**Perfect for**: Weather forecasting projects, meteorological research, data science portfolios, or learning ML classification techniques.
