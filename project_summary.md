# Project Summary: Financial Sales Dashboard

## 1. Objective
The goal of this project was to design an **interactive Power BI dashboard** that provides
business stakeholders with insights into call activity, customer engagement, and sales conversion.  
The dashboard enables management to monitor **agent performance, customer conversion behavior, and call efficiency**.

---

## 2. Tools Used
- **Power BI** → Dashboard design, DAX measures, visualization.  
- **Excel** → Data cleaning and preparation.  

---

## 3. Dataset Overview
- **Dataset:** Sales of Financial Products Clean Data  
- **Rows:** 9,939  
- **Key Fields:**  
  - AgentID, CallID, CustomerID  
  - PickedUp (Yes/No)  
  - Duration (seconds)  
  - ProductSold (Yes/No)  
  - Agent_Name  

---

## 4. Data Preparation
- Cleaned `PickedUp` & `ProductSold` columns → standardized to **Yes/No**.  
- Set correct data types:  
  - IDs → Text  
  - Duration → Numeric (seconds)  
- Added calculated fields:  
  - **Duration Bucket** (<2 min, 2–5 min, 5–10 min, 10+ min)  
  - **Key DAX Measures**:  
    - Total Calls  
    - PickedUp Calls & PickedUp Rate  
    - Total Sales & Conversion Rate  
    - Average Duration (minutes)  
    - Unique Customers, Converted Customers, Customer Conversion Rate  

---

## 5. Dashboard KPIs
- 📞 **Total Calls:** 9,939  
- ☎️ **PickedUp Rate:** 69.62%  
- 💰 **Total Sales:** 2,089  
- 🎯 **Conversion Rate:** 30.19%  
- ⏱ **Average Duration:** 2.09 minutes  
- 👥 **Unique Customers:** 1,001  
- ✅ **Converted Customers:** 886  
- 🎯 **Customer Conversion Rate:** 88.5%  

---

## 6. Business Insights

### Funnel Analysis
- Journey: **Calls → PickedUp → Sales**  
- Drop-off: **10K calls → 7K picked → 2K sales**  
- Insight: Major loss occurs **after calls are picked up** (only ~30% convert).

### Agent Performance
- **Top Agents by Calls:** Michele Williams, Gloria Singh, Agent X  
- **Highest Sales:** Gloria Singh (209), Michele Williams (198)  
- Conversion efficiency across agents: ~20–23%  
- Performance table shows: Calls, PickedUp, Sales, Conversion %, Avg Duration.

### Customer Insights
- **Unique Customers:** 1,001  
- **Converted Customers:** 886  
- **Customer Conversion Rate:** 88.5%  
- Insight: Once engaged, customers are highly likely to purchase.

### Duration Analysis
- **Best conversions for 2–5 minute calls (845 conversions)**.  
- Very short (<2 min) or very long (>10 min) calls convert poorly.  
- Insight: **Optimal call length = 2–5 minutes** → useful for training.

---

## 7. Business Value
- Enables **real-time monitoring** of call center performance.  
- Identifies **top and low-performing agents**.  
- Provides insights into **customer engagement patterns**.  
- Establishes benchmarks for **ideal call duration** to maximize conversions.  

