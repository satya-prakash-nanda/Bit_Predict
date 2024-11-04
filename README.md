# BitPredict 💰📈

Welcome to **BitPredict**, a project focused on using deep learning for time series forecasting to predict the price of Bitcoin. 📊🚀

This project is part of a series on TensorFlow and deep learning, aiming to provide hands-on experience in working with time series data and various neural network architectures. Please note: ⚠️ **This is not financial advice; predicting stock market prices is inherently uncertain.**

---

## 📋 Project Overview

Time series forecasting is about predicting future values based on previously observed data over time. Here, we use the historical prices of Bitcoin (from 2013 to 2021) to experiment with several deep learning models for forecasting.

### Key Features

- **Data Collection & Preprocessing**: Loads Bitcoin price data, formats it for time series analysis, and applies transformations for model readiness.
- **Modeling Approaches**:
  - **Dense Neural Networks**: Fully-connected networks for straightforward time series predictions.
  - **LSTM & CNN**: Sequence models like LSTM and 1D CNN for capturing sequential dependencies.
  - **Ensembling**: Combining multiple models to improve performance.
  - **N-BEATS Replication**: Implements N-BEATS, a deep learning model specifically designed for time series.

- **Evaluation & Prediction**:
  - Model evaluation, forecasting, and creating prediction intervals.
  - Discussion on **data uncertainty** and **model uncertainty**.

---

## 🛠️ Setup and Installation

To get started, clone this repository and ensure you have the required dependencies.

```bash
git clone https://github.com/yourusername/BitPredict.git
cd BitPredict
pip install -r requirements.txt
