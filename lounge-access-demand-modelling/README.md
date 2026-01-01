# Lounge Access Demand Modelling

## 📌 Project Overview
This project focuses on estimating airport lounge demand by modelling passenger eligibility across different lounge tiers. The objective is to support capacity planning by forecasting how many passengers may be eligible for lounge access based on high-level flight characteristics.

The model is designed to be **scalable and future-proof**, relying on broad categories rather than individual flights or aircraft types.

---

## 🎯 Business Objective
- Estimate potential demand for different lounge tiers:
  - Tier 1: Concorde Room (hypothetical at Terminal 3)
  - Tier 2: First Lounge
  - Tier 3: Club Lounge
- Enable forward-looking lounge capacity planning
- Provide a reusable framework applicable to future flight schedules

---

## 🧠 Methodology

### 1. Flight Grouping
Flights were grouped using scalable dimensions:
- **Haul Type**: Short-haul vs Long-haul
- **Time of Day**: Morning, Afternoon, Lunchtime, Evening

These groupings reflect meaningful differences in passenger profiles and travel behaviour.

---

### 2. Eligibility Assumptions
A lookup table was created to estimate the percentage of passengers eligible for each lounge tier per group.

Assumptions were based on:
- Higher premium demand on long-haul routes
- Increased business and loyalty travellers during peak business hours
- Lower premium penetration on short-haul flights

> Note: Tier 1 eligibility is included hypothetically to assess future lounge needs.

---

### 3. Application to Flight Schedule
- A representative sample of flights was selected
- Flights were matched to the eligibility lookup
- Estimated eligible passengers were calculated using:
  

## 🛠 Tools Used
- Python
- Pandas
- Excel
- Jupyter Notebook

## 📊 Key Output
- Reusable eligibility lookup table
- Estimated lounge demand by tier
- Framework applicable to future and changing schedules

## ✅ Key Takeaway
This project demonstrates how high-level assumptions and structured grouping can be used to model lounge demand in the absence of detailed future data, supporting strategic planning decisions.