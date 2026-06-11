# 🌍AtmosAI Air Quality Index (AQI) Prediction Using Machine Learning

## Overview

This project predicts the Air Quality Index (AQI) using machine learning techniques based on pollutant concentrations such as PM2.5, PM10, NO2, SO2, CO, and O3.

The objective is to build an accurate AQI prediction system that can assist environmental monitoring and support pollution-control decision making.

## Features

* Data preprocessing and cleaning
* Feature engineering and analysis
* Multiple ML model comparison
* AQI prediction using pollutant concentrations
* Performance evaluation using RMSE, MAE, MAPE, and R² Score
* Feature importance and SHAP analysis
* Model visualization and interpretation

## Tech Stack

* Python
* Pandas
* NumPy
* Scikit-Learn
* XGBoost
* CatBoost
* Matplotlib
* Seaborn
* SHAP
* Google Colab / Jupyter Notebook

## Machine Learning Models

* Linear Regression
* Support Vector Machine (SVM)
* Random Forest
* AdaBoost
* CatBoost
* XGBoost

## Dataset

Dataset Source:
https://www.kaggle.com/datasets/sathvikisikella/cleaned-air-quality-india

Features Used:

* PM2.5
* PM10
* NO
* NO2
* NOx
* NH3
* CO
* SO2
* O3

Target Variable:

* AQI (Air Quality Index)

## Results

| Model             | R² Score | RMSE  |
| ----------------- | -------- | ----- |
| XGBoost           | 0.9775   | 16.55 |
| CatBoost          | 0.9745   | 17.60 |
| SVM               | 0.7785   | 51.95 |
| Linear Regression | 0.7279   | 57.58 |

### Best Model

XGBoost achieved the highest prediction accuracy with:

* R² Score = 0.9775
* RMSE = 16.55

## Project Workflow

Data Collection
↓
Data Preprocessing
↓
Feature Engineering
↓
Train-Test Split
↓
Model Training
↓
Performance Evaluation
↓
Feature Importance Analysis
↓
AQI Prediction

## Installation

```bash
git clone https://github.com/yourusername/aqi-prediction.git
cd aqi-prediction
pip install -r requirements.txt
```

## Run

```bash
jupyter notebook
```

Open:

```bash
Atomos_AI_AQI.ipynb
```

## Future Improvements

* Real-time AQI prediction
* IoT sensor integration
* Weather data integration
* LSTM and Deep Learning models
* Streamlit dashboard deployment

## Author

Bhoomi Gaur
B.Tech CSE (AI & ML)
Bennett University
