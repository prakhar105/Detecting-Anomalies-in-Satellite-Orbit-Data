# 🌍 Fengyun-2F Eccentricity Analysis

This repository presents a time series analysis and anomaly detection study of the **eccentricity** of the **Fengyun-2F satellite**. The focus is on forecasting this orbital parameter using statistical modeling and identifying deviations that may indicate satellite maneuvers or orbital anomalies.

---

## 📊 Overview

The orbital eccentricity of geostationary satellites like Fengyun-2F is typically near zero. Deviations in this parameter may signal potential satellite maneuvers or data irregularities. In this project, we:

- Load and process satellite TLE (Two-Line Element) data  
- Analyze the eccentricity time series  
- Forecast using multiple time series models  
- Identify anomalies using residuals and statistical thresholds  

---

## 🧠 Methods Implemented

The following methods have been implemented in this project:

- **ARIMA** (AutoRegressive Integrated Moving Average)
- **Auto-ARIMA** for automated parameter selection
- **Rolling ARIMA** for adaptive short-window forecasting
- **Rolling SARIMAX** for seasonal modeling with exogenous variables
- **LSTM (Long Short-Term Memory)** for deep learning-based time series prediction
- Residual-based **anomaly detection**
- Visualization using **Matplotlib** and **Seaborn**
- Diagnostic plots (ACF, PACF, residual analysis)

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
pip install numpy pandas matplotlib seaborn statsmodels pmdarima tensorflow
```

---

## 📈 Outputs

The notebook generates:

- Time series plots comparing actual and predicted eccentricity  
- Residual diagnostics for model validation  
- Detected anomalies based on statistical deviation  

---

## 🚀 Future Work

Potential future directions for this project include:

- Integrating **Large Language Models (LLMs)** for pattern reasoning or natural language anomaly descriptions  
- Using **TimeGPT** or transformer-based models for enhanced forecasting  
- Expanding anomaly detection to multi-variate telemetry datasets  
- Incorporating real maneuver logs for validation

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

> _"Even a perfectly circular orbit holds secrets, it just takes the right lens to see them."_ ✨
