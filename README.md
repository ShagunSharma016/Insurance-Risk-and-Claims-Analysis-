# 🏦 Insurance Risk and Claims Analysis  

> **An interactive Power BI dashboard designed to analyze insurance policies, claims, and risk exposure across multiple customer and policy dimensions.**

![Insurance Risk and Claims Dashboard](https://raw.githubusercontent.com/ShagunSharma016/Insurance-Risk-and-Claims-Analysis-/main/Insurance.png)  
*Insurance Risk and Claims Analysis Dashboard*

---

### 🎯 Project Overview  
This project explores **insurance risk and claim behavior** using real-world analytical insights.  
The goal was to understand how different factors, such as **policy type, car make, coverage zone, age group, and education**, impact the total claim amount and claim frequency.  

Through this dashboard, I simulated how insurance analysts monitor key metrics like policy growth, claim distribution, and risk concentration.  
It became an excellent exercise in combining **data analytics, visualization, and business domain understanding**, bringing data to life through insights.  

---

### 💼 Objective  
To develop an **interactive Power BI dashboard** that helps insurance stakeholders track policy performance, claim trends, and overall financial exposure.  
The main aim was to turn raw policy and claims data into **actionable insights** that support better decision-making and risk management.  

---

### ⚙️ Tools & Skills Used  
- **Power BI:** Data modeling, DAX calculations, and dashboard design  
- **Excel:** Data cleaning and transformation  
- **DAX:** KPIs such as Claim Frequency, Total Policies, and Total Claim Amount  
- **Analytical Thinking:** Risk segmentation, claim analysis, and customer profiling  

---

### 📈 Key Features  
✅ **Dynamic Parameter Selector:** Switch between *Total Policies*, *Total Claim Amount*, and *Claim Frequency*  
📊 **Demographic Insights:** Breakdown by gender, education, and age group  
🚗 **Policy Behavior:** Trends by car type, make, and manufacturing year  
🌍 **Coverage Zone Distribution:** Comparison across rural, urban, and highly urban zones  
📅 **Yearly Policy Trends:** Analysis of growth and claims over time  
🎨 **Professional Design:** Clean, dark theme optimized for clarity and focus  

---

### 💬 Insights & Findings  

- **Overall Performance:**  
  - **Total Policies:** 37,542  
  - **Total Claim Amount:** **$187.8M**  
  - **Average Claim Amount:** **$5,003**  
  - **Claim Frequency:** **51.03%**
    
### **For Current Parameter: Total Policies**

- **Customer Demographics:**  
  - Gender distribution was balanced — **18,736 male** vs **18,806 female** policyholders.  
  - **Bachelors (49.8%)** represented the largest education segment.  
  - Majority of policyholders fell within the **26–55 age range**, highlighting a mature customer base.  

- **Policy Insights:**  
  - **Private Use Vehicles (80%)** dominated compared to **Commercial (20%)**.  
  - **Ford** and **Chevrolet** were the most frequently insured car brands.  
  - **Urban and Highly Urban Zones (40%)** accounted for the majority of total policies.  

- **Claim Trends:**  
  - Policy growth was steady between **1990 and 2015**, with a small dip post-2018.  
  - A **claim frequency of 51%** suggests high repeat or multiple claim behavior in certain segments.  

---

### 🧭 Dynamic Measure Feature  
This dashboard includes a **Measure Selector Parameter** that enables users to toggle between major KPIs —  
providing a flexible and interactive experience for deeper analysis:  

- **Total Policies**  
- **Total Claim Amount**  
- **Claim Frequency**  

```DAX
Selected Measure =
SWITCH(
    TRUE(),
    'Measure Selector'[Measure] = "Total Policies", [Total Policies],
    'Measure Selector'[Measure] = "Total Claim Amount", [Total Claim Amount],
    'Measure Selector'[Measure] = "Claim Freq", [Claim Freq]
)
```    
### 💡 What I Learned  
- Analytics isn’t just about numbers, it’s about **understanding the story behind data**.  
- I learned how insurance data can reveal customer behavior, risk trends, and claim patterns.  
- Building this project helped me improve my **DAX logic, visualization clarity, and business thinking**.  
- I realized that every dataset has its own rhythm, this one taught me how **data connects to real financial impact and risk insight**.  

---

### 🚀 Outcome  
A complete **Insurance Risk and Claims Analysis Dashboard** that shows:  
- Real-world problem-solving through analytics  
- Strong DAX understanding and parameter logic  
- Ability to combine data visualization with business context  
- Confidence to analyze financial, operational, and demographic data

---
  
**👤 Author:** Shagun Sharma  
**💼 Role:** Data Analyst
