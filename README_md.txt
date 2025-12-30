# Hybrid CNN–BiLSTM–Bayesian Ensemble for Sea Surface Temperature Forecasting
### Author: Khadijah Rao

## 🌍 Overview
This project develops a **Hybrid Deep Learning Framework** that integrates **Convolutional Neural Networks (CNN)**, **Bidirectional LSTMs (BiLSTM)**, and **Bayesian Dropout** to forecast **Global Sea Surface Temperature (SST)** with predictive uncertainty estimation.

## 🧠 Core Objectives
- Forecast future SST variations using hybrid spatial-temporal modeling.
- Quantify predictive uncertainty using **Monte Carlo Dropout**.
- Perform **trend analysis** using the **Mann–Kendall test** for statistical significance.
- Enhance interpretability through uncertainty visualization.

## 📊 Key Features
- Hybrid CNN–BiLSTM architecture for deep temporal-spatial learning.
- Bayesian inference layer for uncertainty quantification.
- Statistical validation (Mann–Kendall + Sen’s Slope).
- Visualization of prediction intervals for reliability assessment.

## 🧩 Technologies Used
- Python, TensorFlow / Keras
- NumPy, Pandas, Scikit-Learn
- Matplotlib, Seaborn
- PyMannKendall for trend analysis

## 📈 Results
- Achieved stable training (val_loss ≈ 0.003).
- Detected **significant decreasing SST trend (p ≈ 0.0003)**.
- Successfully visualized uncertainty bands in global SST forecasts.

## 💾 Files Included
- `sst_global.csv` — Sea Surface Temperature dataset (2000–2015)
- `Hybrid_SST_Model.h5` — Trained deep learning model
- `SST_Forecast_Uncertainty.png` — Visualization of predicted SST with uncertainty
- `Hybrid_SST_Predictive_Uncertainty_Khadijah.ipynb` — Main notebook file
- `README.txt` — Project documentation

## ✨ Author
**Khadijah Rao**  
AI & Data Science Researcher | Climate Deep Learning | Geospatial Intelligence
