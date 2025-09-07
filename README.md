# Chicken Republic Sales & Forecasting  

## Project Overview  
This project analyzes **Chicken Republic’s sales data** using:  
- **Power BI** → Interactive dashboards for sales and profit insights  
- **Python (SARIMA)** → Time series forecasting for sales prediction  
<img width="516" height="296" alt="Dashboard" src="https://github.com/user-attachments/assets/ee98d38c-4ce3-436e-ae2f-15c540773521" />

The dataset was sourced from **Kaggle** and preprocessed in Python.  

---

## Objectives  
- Analyze sales performance across locations and product categories  
- Identify profitability trends and key revenue drivers  
- Forecast sales using **SARIMA** for better business planning  
- Provide **actionable business recommendations**  

---

## Data Preparation  
- Cleaned raw dataset (handled missing values, standardized dates, removed inconsistencies)  
- Engineered features: sales aggregated by time, product category, and location  
- **Challenge**: Preparing the date column for SARIMA and parameter tuning  

---

## Dashboard Insights (Power BI)  

### Sales & Profit by Location  
- **Victoria Island & Ikeja** = Strongest performers (contributing >60% profit)  
- **Ajah & Yaba** = Underperforming branches that need improvement  

### Sales by Product Category  
- Balanced contributions across **Desserts, Meals, Snacks, and Drinks** (23–26% each)  
- Opportunity: Promote **higher-margin items** through upselling  

### Overall Performance  
- **Total Sales**: ₦3.79M  
- **Total Profit**: ₦656.93K  
- **Quantity Sold**: 2,581  

---

## Time Series Forecasting (SARIMA)  
- Built SARIMA model for **sales prediction**  
- Forecast vs. Real sales show model captures **seasonality and trend**  
- Supports **demand planning, inventory management, and scheduling**  

---

## Business Recommendations  
1. **Location Strategy**  
   - Boost strong outlets (Victoria Island, Ikeja) with promotions  
   - Investigate inefficiencies in Ajah & Yaba  

2. **Product Mix Optimization**  
   - Upsell **high-margin items** (e.g., desserts, snacks)  
   - Offer **bundles (meals + drinks)** to increase spend per customer  

3. **Forecast Utilization**  
   - Apply SARIMA forecasts for inventory & staff planning  
   - Align promotions with predicted high-demand months  

4. **Data-Driven Marketing**  
   - Run **location-specific campaigns**  
   - Launch loyalty programs in low-performing areas  

---

## Way Forward  
- Enhance forecasting with **Facebook Prophet** or **LSTM deep learning**  
- Connect **Power BI dashboards** to live sales data  
- Expand forecasting to include **profit prediction**  
- Incorporate **customer demographics** for deeper insights  

---

## Sample Dashboards & Forecast  
*(Replace links below with your screenshots)*  
<img width="189" height="314" alt="model prediction" src="https://github.com/user-attachments/assets/bd7fbc15-a0ff-49f6-8868-97aa9b1874a7" />
<img width="527" height="297" alt="Prediction" src="https://github.com/user-attachments/assets/0d53d8d1-bd7c-4cf3-a1c4-b9d7ecfb4e19" />


---

## Tech Stack  
- **Python** → Pandas, Statsmodels, Matplotlib  
- **Power BI** → Interactive dashboards  
- **SARIMA** → Time series forecasting  
- **Dataset** → Kaggle  
