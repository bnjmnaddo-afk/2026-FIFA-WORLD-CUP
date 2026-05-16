# 🚲 Citi Bike Usage Analysis — July 2025  
### A Data‑Driven Look at Urban Mobility, Rider Behavior & World Cup Readiness

This repository contains a full exploratory data analysis (EDA) of Citi Bike trip data for July 2025. Using nearly **5 million rides**, the project uncovers demand patterns, rider segmentation, and station‑level operational risks — with a focus on preparing New York City for the **2026 FIFA World Cup**.

---

## 📌 Objectives
- Understand daily and hourly demand patterns  
- Compare member vs casual rider behavior  
- Identify high‑pressure stations (outflow/inflow imbalance)  
- Highlight operational risks for large‑scale events  
- Provide insights for transportation planning and mobility management  

---

## 🧹 Data Engineering
- Merged 5 CSV files using `glob`  
- Dropped rows missing station or coordinate data  
- Converted timestamps to datetime  
- Created trip duration and removed unrealistic trips  
- Engineered features:  
  `hour`, `day_of_week`, `month`, `year`, `is_weekend`  
- Removed duplicates and validated dataset integrity  

---

## 📈 Key Findings

### **Demand Trends**
- Commute peaks at **7–9 AM** and **4–7 PM**  
- Weekend demand spikes due to tourism  
- Mid‑month dips likely tied to weekday patterns or weather  

### **Rider Behavior**
- **Members**: short, consistent, commuter‑driven trips  
- **Casual riders**: longer, leisure‑oriented trips  
- Casual usage surges on weekends and afternoons  

### **Station Pressure**
- High outflow stations risk running out of bikes  
- High inflow stations risk dock saturation  
- Midtown, Central Park, Chelsea Piers, and Union Square are critical zones  

---

## 🏆 World Cup Readiness
This analysis identifies:
- Stations requiring temporary capacity increases  
- Areas needing more rebalancing trucks  
- Time windows with highest operational pressure  
- Expected surges in casual rider volume  

---

## 🛠️ Tech Stack
Python • Pandas • NumPy • Matplotlib • Seaborn • Google Colab

👤 Author
**Benjamin Addo**  
Data Analyst (in training) • HSE Professional • Urban Mobility Enthusiast

## 📂 Repository Structure
