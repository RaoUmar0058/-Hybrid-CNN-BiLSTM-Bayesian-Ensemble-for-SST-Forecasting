# Hybrid CNN–BiLSTM–Bayesian Ensemble for Sea Surface Temperature Forecasting

### Author: Khadija Rao

## Overview

This project develops a **Hybrid Deep Learning Framework** that integrates **Convolutional Neural Networks (CNN)**, **Bidirectional LSTMs (BiLSTM)**, and **Bayesian Dropout** to forecast **Global Sea Surface Temperature (SST)** with predictive uncertainty estimation.

## Objectives

* Forecast future SST variations using hybrid spatial-temporal modeling.
* Quantify predictive uncertainty using **Monte Carlo Dropout**.
* Perform **trend analysis** using the **Mann–Kendall test**.
* Visualize prediction reliability and uncertainty.

## Key Features

* Hybrid CNN–BiLSTM architecture for deep spatial-temporal learning.
* Bayesian inference layer for uncertainty quantification.
* Statistical validation (Mann–Kendall + Sen’s Slope).
* Visualization of prediction intervals for reliability assessment.

## Technologies Used

* Python, TensorFlow / Keras
* NumPy, Pandas, Scikit-Learn
* Matplotlib, Seaborn
* PyMannKendall for trend analysis

## Results

* Stable training (val_loss ≈ 0.003).
* Significant decreasing SST trend detected (p ≈ 0.0003).
* Visualized uncertainty bands in SST forecasts.

## Files Included

* `sst_global.csv` — SST dataset (2000–2015)
* `Hybrid_SST_Model.h5` — Trained deep learning model
* `SST_Forecast_Uncertainty.png` — Visualization of predicted SST with uncertainty
* `Hybrid_SST_Predictive_Uncertainty_Khadijah.ipynb` — Notebook file
* `README.txt` — Project documentation

## Author

**Khadija Rao**
AI & Data Science Researcher | Climate Deep Learning | Geospatial Intelligence
