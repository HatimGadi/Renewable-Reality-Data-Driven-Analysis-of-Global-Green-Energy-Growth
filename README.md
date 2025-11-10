# 🌍 Renewable Reality: Global Renewable Energy Growth Analysis (SDG 7)

A data-driven analysis and visualization project exploring how renewable energy adoption has evolved globally over time — with a detailed focus on India's growth and future prediction using Linear Regression.

---

## 📘 Overview

This project analyzes the share of renewable energy in global and regional power consumption from 1990 to 2024, aligning with the **UN Sustainable Development Goal 7 (Affordable & Clean Energy)**.

Using **Python for analysis** and **Power BI for visualization**, the project identifies renewable energy trends, top-performing countries, and forecasts India’s renewable growth through 2035.

---

## 🎯 Objectives

- Analyze historical renewable energy trends globally.  
- Identify top and bottom-performing countries.  
- Study India’s renewable energy progress in detail.  
- Predict India’s future renewable energy share using Linear Regression.  
- Build an interactive Power BI dashboard for storytelling and insights.

---

## 🧠 Key Insights

- Global renewable energy share has shown steady growth since 2000.  
- Northern European countries (Iceland, Norway, Sweden) lead adoption with >80% renewable share.  
- Developing countries show accelerating adoption rates post-2015.  
- India’s renewable share is projected to **grow consistently through 2035**, based on regression analysis.  

---

## 🧩 Tech Stack

| Component | Tools Used |
|------------|-------------|
| **Data Analysis** | Python, Pandas, NumPy |
| **Visualization** | Power BI, Matplotlib |
| **Machine Learning** | Scikit-learn (Linear Regression) |
| **Data Cleaning** | Pandas, Excel |
| **Dataset Format** | CSV (`01_renewable-share-energy.csv`) |

---

## 📊 Project Workflow

1. **Data Collection & Cleaning**  
   - Source: [Kaggle / Our World in Data - Renewable Energy Dataset](https://www.kaggle.com/datasets)  
   - Removed null values and standardized country names.

2. **Exploratory Data Analysis (EDA)**  
   - Global renewable share trends by year.  
   - Top 10 and bottom 10 countries analysis.  
   - Regional trend comparisons.  

3. **Predictive Modeling (India)**  
   - Linear Regression model trained on India’s renewable share data.  
   - Forecast from 2025–2035 using scikit-learn.

4. **Visualization (Power BI)**  
   - Global renewable share dashboard.  
   - Country-level comparison.  
   - Predictive line for India’s future growth.  

---

## 📈 Machine Learning Component

**Model:** Linear Regression  
**Goal:** Predict India’s Renewable Energy Share (2025–2035)

```python
from sklearn.linear_model import LinearRegression
model = LinearRegression()
model.fit(X, y)
future_pred = model.predict(future_years)
