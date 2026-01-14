# 🛒 Customer Segmentation & Lifetime Value Prediction  
*A complete end-to-end Data Science project using the Online Retail II dataset.*

---

## 📌 Project Overview
This project performs customer analytics for an e-commerce business using:

- **RFM Analysis (Recency, Frequency, Monetary)**
- **K-Means Customer Segmentation**
- **Cohort Analysis**
- **Lifetime Value (LTV) Prediction using LightGBM**
- **Interactive Streamlit Dashboard**

The goal is to understand customer behavior, classify customer groups, and predict future revenue.

---

## 📁 Dataset
The dataset used is **Online Retail II** (UCI / Kaggle).

It contains:

- 541,000+ transactions  
- 2010–2011 timeframe  
- Customer ID, product codes, quantity, price, invoice date, and country  

Dataset link:  
https://www.kaggle.com/datasets/mashlyn/online-retail-ii-uci

---

## 🧪 Features of This Project
### ✔ RFM Analysis
Calculates:
- **Recency** – days since last purchase  
- **Frequency** – number of invoices  
- **Monetary** – total spending  

### ✔ Customer Segmentation
Uses **K-Means** to classify customers into behavioral clusters.

### ✔ Cohort Analysis
Identifies retention patterns using:
- Cohort month  
- Cohort index  
- Retention heatmaps  

### ✔ Lifetime Value Prediction (LTV)
Uses LightGBM to estimate how much a customer will spend in the future.

### ✔ Streamlit Dashboard
An interactive dashboard that includes:
- RFM distribution plots  
- Cluster insights  
- LTV prediction tool  
- Feature importance visualization  

---

## 🗂 Project Structure
```
customer-segmentation-ltv/
│
├── notebooks/
│ └── customer_segmentation_ltv.ipynb
│
├── app.py # Streamlit dashboard
├── rfm_clusters.csv # RFM table with cluster labels
├── ltv_model.pkl # Trained LightGBM model
├── scaler.pkl # StandardScaler for model
│
└── README.md
```

---

## 🚀 How to Run the Dashboard

### 1. Install dependencies
```bash
pip install -r requirements.txt
```
2. Run Streamlit app
streamlit run app.py

3. Open in browser
Streamlit will open automatically or you can visit:
http://localhost:8501/

🔮 Future Improvements

Add customer churn prediction

Implement advanced time-series LTV models

Build automated pipelines using Airflow

Deploy the dashboard using Streamlit Cloud or Docker 

Author
Ege Bakalım
Data Scientist
