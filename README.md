## 📊 Short-Term Load Forecasting using Machine Learning

This project implements a multi-step (24-hour ahead) electrical load forecasting model using historical demand and weather data.

### 🔹 Problem Statement
Accurate short-term load forecasting is essential for power system operation, planning, and reliability.

### 🔹 Methodology
- Hourly data preprocessing and resampling
- Feature engineering using cyclic time features
- Time-based train–test split to avoid data leakage
- Baseline models:
  - Naive seasonal persistence
- Deep learning model:
  - Stacked LSTM with early stopping and learning-rate scheduling

### 🔹 Tools & Libraries
Python, TensorFlow, Scikit-learn, Pandas, NumPy, Matplotlib
