# 📊 Data Analysis & Visualization Project

A comprehensive data analysis and visualization project showcasing end-to-end data cleaning, transformation, and storytelling using **Python (Jupyter Notebook)** and **Power BI**.

---

## 🧩 Project Overview

This project demonstrates how to explore, clean, merge, and visualize multi-source data to uncover meaningful insights about **user behavior, campaign performance, and engagement trends**.

It combines:
- 🐍 **Jupyter Notebook** for data preprocessing and analysis
- 📈 **Power BI Dashboard** for interactive visual storytelling

---

## 📁 Folder Structure

Data_Analysis_Project/

│

├── data/

│ ├── users.csv

│ ├── campaigns.csv

│ └── usage_metrics.csv

│


├── analysis/

│ └── data_cleaning_and_merging.ipynb

│

├── visuals/

│ └── PowerBI_Dashboard.pbix

│

├── reports/

│ ├── Code for analysis

│ └── Mini presentation

│

└── README.md

---

## ⚙️ Tools & Technologies

| Tool / Library | Purpose |
|----------------|----------|
| **Python (Pandas, NumPy)** | Data cleaning & preprocessing |
| **Matplotlib / Seaborn** | Basic exploratory visualizations |
| **Power BI** | Interactive dashboards & KPIs |
| **Excel / CSV** | Dataset storage and merging |
| **Jupyter Notebook** | Code execution & documentation |

---

## 🔍 Project Workflow

### **Step 1 – Data Understanding**
- Loaded 3 CSV datasets: `users.csv`, `campaigns.csv`, and `usage_metrics.csv`
- Inspected dataset structure, datatypes, and missing values

### **Step 2 – Data Cleaning & Transformation**
- Handled missing values (`NaN`, blanks)
- Converted date fields into standard datetime format
- Standardized categorical data (country, device, status)
- Merged datasets using `user_id` and `campaign_id` keys

### **Step 3 – Analysis & Exploration**
- Explored user engagement by device and country
- Identified most active and least active campaigns
- Analyzed trends in session duration and engagement scores

### **Step 4 – Visualization & Dashboard**
- Built Power BI dashboards to visualize:
  - 📅 Weekly user activity trends  
  - 💬 Engagement by device & country  
  - 🎯 Campaign performance & status breakdown  
  - 🕒 Average session time analysis  
  - 🌍 Global engagement overview  

### **Step 5 – Insights & Recommendations**
- Highlighted key findings from data
- Suggested actionable improvements for user engagement and campaign optimization

---

## 💡 Key Insights

- 📈 **User Engagement Growth:** Consistent increase in user activity over time, with peaks during specific campaign launches  
- 🌐 **Top Performing Regions:** Engagement highest in Tier-1 countries with mobile-first users  
- 🧠 **Behavioral Trends:** Referral users show longer session durations  
- 🚀 **Experience Impact:** Certain experience types drive significantly higher engagement rates  
- 🕵️ **Inactive Segments:** Users with low engagement can be re-targeted through credit-based incentives  

---

## 🧭 Future Improvements

- Add predictive modeling for user churn  
- Integrate SQL queries for advanced data extraction  
- Automate Power BI refresh using Python scripts  
- Extend dashboard to include cohort analysis  

---

## 👤 Author

**Name:** Lakshman  
**Role:** Data Enthusiast | Analyst | Power BI Developer  
**Contact:** [LinkedIn](https://www.linkedin.com) • [Email](mailto:example@email.com)

---

⭐ *If you find this project useful, give it a star on GitHub!*
