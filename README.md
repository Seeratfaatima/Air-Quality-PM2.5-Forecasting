# Air Quality $PM_{2.5}$ Multi-Step Forecasting & Dataset Connectivity

A professional machine learning project focused on predictive atmospheric modeling for public health and urban planning.

---

## 📌 Project Overview
Predicting atmospheric $PM_{2.5}$ concentration is a critical task for public health and urban planning. This project implements a **Stacked Bidirectional Long Short-Term Memory (BiLSTM)** network to perform a **24-hour multi-step forecast** using the Beijing Multi-Site Air-Quality Dataset.

## 🎯 Technical Objectives
* **Sequential Learning:** Capture complex temporal dependencies using bidirectional recurrent layers.
* **Multivariate Integration:** Combine pollutant data ($PM_{2.5}$, $SO_2$, $CO$) with meteorological variables (Temperature, Pressure, Wind Speed).
* **Pipeline Architecture:** Implement a robust **Scikit-Learn Pipeline** to automate scaling and 3D windowing, ensuring zero data leakage.
* **Model Interpretability:** Utilize feature importance analysis to understand which environmental drivers most influence the forecast.

---

## 📊 Dataset & Architecture
* **Dataset:** Beijing Multi-Site Air-Quality Dataset (integrated directly via Kaggle).
* **Core Stack:** Python, TensorFlow/Keras, Scikit-Learn, Pandas, NumPy.
* **Model Architecture:** Stacked Bidirectional LSTM optimized for multivariate time-series forecasting.

## 🛠️ How to Run the Notebook
1. Clone this repository:
```bash
   git clone [https://github.com/Seeratfaatima/Air-Quality-PM2.5-Forecasting.git](https://github.com/Seeratfaatima/Air-Quality-PM2.5-Forecasting.git)
