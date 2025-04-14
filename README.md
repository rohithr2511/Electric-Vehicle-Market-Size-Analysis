# ⚡ Python Electric Vehicle (EV) Data Analysis Project

This project presents an end-to-end data analysis of electric vehicles (EVs) using Python. The goal was to assist consumers in selecting EVs based on budget, range, battery capacity, and other key performance metrics.

## 📊 Dataset Overview

- Source: EV specifications (FEV.xlsx)
- Total EVs analyzed: **53**
- Key features: Price, range, battery capacity, energy consumption, performance specs

## 🔍 Project Objectives

- Filter EVs by budget and minimum range
- Identify manufacturers offering optimal EVs
- Detect energy consumption outliers
- Visualize battery capacity vs. range
- Recommend top EVs using custom logic
- Perform hypothesis testing on engine power

---

## 🧠 Key Insights

### 🔹 1. Budget and Range Filtering
- **12 EVs** satisfied the criteria: ≤ 350,000 PLN price and ≥ 400 km range.
- Eligible brands: **Audi, BMW, Hyundai, Kia, Mercedes-Benz, Tesla, Volkswagen**

### 🔹 2. Manufacturer Breakdown
- **Tesla and Volkswagen** had the most qualifying models (3 each).
- **Average Battery Capacity by Brand:**
  - Audi: 95.0 kWh  
  - Tesla: 68.0 kWh  
  - Volkswagen: 70.7 kWh  
  - Kia/Hyundai: 64.0 kWh  
  - BMW: 80.0 kWh  
  - Mercedes-Benz: 80.0 kWh  

### 🔹 3. Outlier Analysis
- No outliers detected in **Mean Energy Consumption [kWh/100 km]** — indicating energy usage consistency across models.

### 🔹 4. EV Recommendation System
- Based on budget, minimum range, and battery capacity:
  - 🥇 **Tesla Model 3 Long Range** — *580 km range*
  - 🥈 **Tesla Model 3 Performance** — *567 km range*
  - 🥉 **Volkswagen ID.3 Pro S** — *549 km range*

### 🔹 5. Hypothesis Testing
- Conducted a t-test comparing **Tesla vs. Audi** engine power.
  - **p-value = 0.116** → No statistically significant difference in engine power.

### 🔹 6. Data Visualization
- **Battery Capacity vs. Range** scatter plot showed:
  - A positive correlation between battery size and range.
  - Tesla and Volkswagen models performed strongly in balancing battery efficiency with driving range.

---

## ✅ Conclusions

- **Tesla** leads the pack in delivering high-range EVs within a moderate budget.
- **Audi** provides robust battery capacity, though at a higher cost.
- The **EV Recommendation System** offers practical, data-driven purchase advice tailored to consumer priorities.
