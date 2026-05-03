# 🚀 UPI Growth vs Internet Penetration — India

An end-to-end data science project analyzing whether India's explosive UPI growth is driven by internet penetration or by deeper behavioral, policy, and ecosystem factors.

---

## 📌 Project Overview

| Item | Detail |
|---|---|
| **Period** | 2016–17 to 2022–23 |
| **Datasets** | NPCI, TRAI, UPI Monthly Data |
| **Models** | Linear Regression, Random Forest |
| **Dashboard** | Panel + Plotly |
| **Language** | Python |

### 🎯 Research Question
> Is internet penetration the primary driver of UPI growth, or are other factors more influential?

---

## 📊 Dashboard Preview

### 🏠 Overview
![Overview](screenshots/dashboard_overview.png)

### 📈 Growth Analysis
![Growth](screenshots/dashboard_growth.png)

### 🔍 Comparison & Correlation
![Comparison](screenshots/dashboard_comparison.png)

### 🤖 Machine Learning
![ML](screenshots/dashboard_ml.png)

### 💡 Conclusion
![Conclusion](screenshots/dashboard_conclusion.png)

---

## 🔄 Workflow

1. Data Collection  
2. Data Cleaning  
3. Data Integration  
4. Feature Engineering  
5. Exploratory Data Analysis (EDA)  
6. Machine Learning  
7. Dashboard Development  

---

## ⚙️ Feature Engineering

| Feature | Purpose |
|---|---|
| `Volume_Growth_Pct` | Capture UPI growth trends |
| `Value_Per_Txn` | Understand transaction efficiency |
| `Log_Volume` | Handle exponential growth |
| `Subscribers_Sq` | Capture non-linear effects |
| `Rural_Urban_Ratio` | Digital divide proxy |

---

## 📊 Exploratory Data Analysis

- Descriptive statistics  
- Correlation matrix  
- Growth comparison  
- Scatter plots & heatmaps  

### 🔥 Key Observation
UPI growth is **exponential**, while internet penetration remains relatively **stable**

---

## 🤖 Machine Learning

### Models Used
- Linear Regression (baseline)
- Random Forest (non-linear model)

### Evaluation
- R² Score  
- Residual Analysis  
- Cross-validation (LOO)

### 🔑 Insight
Random Forest performs better due to **non-linear relationship in data**

---

## 📊 Key Findings

- UPI grew ~4689× over the period  
- Internet penetration increased marginally  
- Correlation between UPI and internet ≈ **weak (-0.143)**  

### 💡 Final Insight
UPI growth is **not solely dependent on internet penetration**

It is driven by:
- Behavioral adoption  
- Government initiatives  
- Merchant ecosystem  
- Digital payment infrastructure  

---

## 📈 Dashboard Highlights

- KPI-based overview  
- Growth trend comparison  
- Correlation heatmap  
- ML model comparison  
- Feature importance analysis  

---

## 🛠️ Tech Stack

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Panel, Plotly  

---

## ▶️ How to Run

```bash
pip install pandas numpy matplotlib seaborn scikit-learn panel plotly
