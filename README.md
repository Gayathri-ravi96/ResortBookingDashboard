# 🏖️ Resort Booking Insights Dashboard

This project is an end-to-end data science solution built to analyze and predict booking trends in the resort industry. It includes:

- **Peak season prediction** using Random Forest
- **Booking cancellation prediction** using XGBoost
- **Occupancy forecasting** using Prophet
- **Visual insights** into trends, seasonality, and holiday patterns

The dashboard is built with **Streamlit** and integrates machine learning pipelines for seamless predictions. It’s designed to help resort managers make informed decisions about promotions, staffing, and operational planning.

---

## Features

🔹 Predict whether a given period is a **peak season**  
🔹 Predict **booking cancellation** based on guest details and reservation patterns  
🔹 Forecast **monthly and daily occupancy** to identify:
- High and low booking periods
- Holiday trends
- Opportunities for promotions during off-peak times

🔹 Custom visualizations using **Matplotlib**

---
## 📦Libraries Used
- `streamlit` – dashboard framework
- `pandas` – data manipulation
- `numpy` – data manipulation
- `scikit-learn` – machine learning models (Random Forest, pipelines)
- `xgboost` – gradient boosting model for cancellation prediction
- `matplotlib` – custom visualizations and charts
- `joblib` – saving and loading trained models
- `prophet` – time series forecasting and holiday trend detection
- `python-dateutil` – used for handling date offsets like `relativedelta`


## 📁 Project Files

- `ResortBooking.ipynb` — EDA, feature engineering, model building, and pipeline creation  
- `deployresort.py` — Streamlit app to interact with the dashboard  
- `country_freq_map.pkl` — Country frequency mapping used in visualizations *(optional)*  
- `rf_pipeline.pkl`, `xgb_pipeline.pkl`, `model_prophet.pkl` — Trained ML models *(not included)*  

---

## ⚠️ Note on Model Files

To keep the repository lightweight, trained model files (`rf_pipeline.pkl`, `xgb_pipeline.pkl`, etc.) are **not included**.  
Please run the notebook (`ResortBooking.ipynb`) to retrain the models before using the Streamlit app.

---

## 📦 Requirements

Install dependencies using:

pip install streamlit pandas scikit-learn xgboost matplotlib prophet joblib


