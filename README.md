# 📊 CRIS Metro Booking & Sales Analysis Dashboard

A Power BI dashboard developed using real metro sales and booking data from the Centre for Railway Information Systems (CRIS). This project visualizes transaction behaviors, zone-wise token distributions, and terminal-wise cash trends to enable data-driven operational insights.

---

## 📁 Project Overview

This interactive report covers:
- Booking trends and forecasting
- Token sale peaks across June
- Terminal performance (cash influx, security deposits)
- Shift-wise transaction summaries
- Zone-wise token distribution

---

## ⚙️ Tools & Technologies
- **Power BI Desktop**
- **Oracle SQL Server** (Data Source)
- **Microsoft Excel** (Pre-processing)
- **DAX** (for measures & calculated columns)

---

## 🧠 Problem Statement

Analyze CRIS metro sales and booking data to:
- Identify high-performing zones and terminals
- Forecast future booking behavior
- Understand inflow and deposit distributions
- Monitor operational shifts and total net influx

---

## 📊 Dashboard Highlights

### 📄 **Page 1: Booking and Token Overview**

![image](https://github.com/user-attachments/assets/ba88605f-0426-4b7c-95f3-f67b48696e07)

- **KPI Cards**:  
  - `Net Booking Sales`: ₹2.38L  
  - `Net Token Sales`: ₹91.51K  

- **Area Charts**:  
  Embedded within KPI cards for mini-trends

- **Shift-Wise Transaction Matrix**:  
  Location-wise sales across three shift slots

- **Forecast Line Chart**:  
  - Title: *Booking Trend with Future Analysis*  
  - Highlights booking momentum and prediction over time

---

### 📄 **Page 2: Terminal & Zone Analytics**

![image](https://github.com/user-attachments/assets/d6118b10-c78e-4100-a32d-70e1d593b8fb)

- **Bar Chart** – *Dates with Highest Token Sales*  
  Helps spot booking surges and date-specific peaks.

- **Stacked Column Chart** – *Zone-Wise Sales*  
  Compares ZONE1–ZONE6 over daily intervals.

- **Pie Charts** – *Terminal-Wise Insights*  
  - **Cash Influx**:  
    - KBEL02 (₹2.46M - 43.37%)  
    - KBEL03 (₹2.29M - 40.39%)  
    - KBEL81 (₹0.92M - 16.2%)  
  - **Security Deposit**:  
    - KBEL99 (₹4.14K - 57.66%)  
    - KBEL02 (₹1.72K - 23.96%)  
    - KBEL03 (₹1.32K - 18.38%)

---

## 📈 Key Takeaways
- **KBEL02** contributed the highest to cash influx, with **43.37% share**
- **KBEL99** led in security deposits at **57.66%**
- **ZONE3** had the highest ticketing activity overall
- Forecast model indicates an **upward trend in bookings**

### 📁 Files

📄 [View Full Power BI Report (PDF)](CRIS%20report.pdf): Contains the full Power BI report with visuals and data summary

> 💡 Tools Used: Power BI, Oracle SQL Server, Excel


---
