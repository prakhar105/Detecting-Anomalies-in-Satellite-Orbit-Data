# 🌍 Fengyun-2F Eccentricity Analysis

This repository presents a time series analysis and anomaly detection study of the **eccentricity** of the **Fengyun-2F satellite**. The focus is on forecasting this orbital parameter using statistical modeling and identifying deviations that may indicate satellite maneuvers or orbital anomalies.

---

## 📊 Overview

The orbital eccentricity of geostationary satellites like Fengyun-2F is typically near zero. Deviations in this parameter may signal potential satellite maneuvers or data irregularities. In this project, we:

- Load and process satellite TLE (Two-Line Element) data  
- Analyze the eccentricity time series  
- Forecast using ARIMA modeling  
- Identify anomalies using residuals and statistical thresholds  

---

## 🧠 Methods

The analysis involves:

- **ARIMA (AutoRegressive Integrated Moving Average)** for time series forecasting  
- Residual-based **anomaly detection**  
- Visualization using **Matplotlib** and **Seaborn**  
- Time series diagnostics (ACF, PACF, residual plots)  

---

## 📁 Project Structure

```plaintext
Fengyun2FEccentricity/
├── Fengyun2FEccentricity.ipynb   # Jupyter notebook with the full analysis
├── data/                         # Directory for input TLE or derived orbital data
├── models/                       # (Optional) Trained model storage
├── plots/                        # (Optional) Figures and output plots
└── README.md                     # Project documentation
```

---

## ⚙️ Installation

Install the required Python packages:

```bash
pip install numpy pandas matplotlib seaborn statsmodels
```

---

## 📈 Outputs

The notebook generates:

- Time series plot of actual vs predicted eccentricity  
- Residual diagnostics for ARIMA performance  
- Highlighted anomalies based on model deviations  

---

## 🚀 Future Work

Potential extensions of this project include:

- Implementing **SARIMA** or **LSTM** models for improved accuracy  
- Analyzing additional orbital parameters (e.g., inclination, RAAN)  
- Automating anomaly validation using historical maneuver records  

---

## 📡 Data Source

- TLE (Two-Line Element) datasets for Fengyun-2F satellite
- Derived eccentricity values calculated from TLE data

---

## 📬 Contact

If you have questions, suggestions, or collaboration requests:

- Open an issue on [GitHub](https://github.com/yourusername/yourrepo/issues)
- Or contact the maintainer via email

---

> _"Even a perfectly circular orbit holds secrets — it just takes the right lens to see them."_ ✨
