# ⚡ APC Intelligence Dashboard

### AI-Based Auxiliary Power Consumption Optimization  
**Hindalco Industries Ltd. — Renusagar Power Division (RPD)**

---

## 📌 Overview

APC Intelligence Dashboard is an AI-driven system designed to optimize Auxiliary Power Consumption (APC) in a 716 MW captive thermal power plant.

It integrates:
- 📊 Interactive Dashboard (Chart.js)
- 🤖 AI Models (LSTM, GRU, XGBoost)
- ⚙️ Equipment Analytics
- 💡 Optimization Engine
- 📈 Forecasting & Decision Support

---

## 🎯 Objectives

- Reduce APC from 8.11% → 6.92%  
- Identify high energy-consuming equipment  
- Enable data-driven operational decisions  
- Achieve ₹50+ Crore annual savings  
- Improve overall plant efficiency  

---

## 🚀 Features

### 📊 Dashboard
- APC Trend (Actual vs Forecast vs Target)
- KPI Monitoring (APC %, Savings, Equipment Share)
- Alerts for abnormal performance

### ⚙️ Equipment Analytics
- BFP, CW Pump, ID/FD/PA Fans, Mills analysis
- Equipment-wise APC contribution
- Monthly trend tracking

### 🏭 Unit Performance
- 10-unit comparison
- APC vs PLF benchmarking
- Identification of inefficient units

---

## 🤖 AI Models

| Model | R² Score |
|------|---------|
| ARIMA | 0.76 |
| LSTM | 0.92 |
| GRU | 0.91 |
| Hybrid (LSTM + XGBoost) | **0.94** |

---

## 💡 Optimization Results

| Lever | APC Reduction | Savings |
|------|-------------|--------|
| Coal Moisture Reduction | 0.28% | ₹12.4 Cr |
| BFP Optimization | 0.16% | ₹7.1 Cr |
| CW Pump Optimization | 0.13% | ₹5.8 Cr |
| Load Balancing | 0.21% | ₹9.3 Cr |
| **Combined AI Scenario** | **1.19%** | **₹52.6 Cr** |

---

## 📋 AI Recommendations

- Reduce coal moisture during monsoon  
- Optimize BFP RPM  
- Use CW pump duty/standby strategy  
- Balance unit loading  
- Optimize ID fan damper settings  

---

## 🏗️ Architecture
Data Sources (MIS / SCADA)
↓
Data Processing (Python)
↓
Feature Engineering
↓
ML Models (LSTM / GRU / XGBoost)
↓
Forecast & Optimization
↓
Dashboard (HTML + Chart.js)


---

## 📂 Project Structure
APC-Dashboard/
│
├── index.html
├── css/
├── js/
├── data/
├── models/
├── README.md


---

## 🛠️ Tech Stack

- HTML, CSS, JavaScript  
- Chart.js  
- Python (Pandas, NumPy)  
- TensorFlow / Keras  
- Scikit-learn  
- Statsmodels  

---

## 📈 Data Details

- Period: Jan 2023 – Dec 2025  
- Frequency: Monthly  
- Inputs:
  - Generation Data  
  - Coal Quality (GCV, Moisture, Ash)  
  - Equipment Consumption  
  - Operational Parameters  

---

## 💰 Business Impact

- APC Reduction: **8.11% → 6.92%**  
- Annual Savings: **₹52.6 Crore**  
- Improved plant efficiency  
- AI-driven operations  

---

## ⚙️ Usage
git clone [https://github.com/your-username/APC-Dashboard.git](https://mohitsaxena1210.github.io/APC-Optimization/)

Open: index.html


---

## 🔮 Future Enhancements

- Real-time SCADA integration  
- Transformer-based forecasting models  
- Digital twin for plant optimization  
- Automated control recommendations  

---

## 👨‍💻 Author

**Mohit Saxena**  
Tech Services HIL RPD 
EMBA, IIMR
---

## 📜 License

For research and industrial use.

---

## ⭐ Final Note

This project demonstrates how AI combined with power plant domain expertise can deliver real, measurable financial impact through intelligent optimization.
