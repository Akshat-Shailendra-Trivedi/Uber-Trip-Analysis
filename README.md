# 🚖 Uber Trip Analysis 

## 📌 1. Purpose
An interactive Power BI dashboard built to analyze Uber trip data, uncover booking trends, revenue performance, location hotspots, and time-based ride demand.  
This project enables stakeholders to make data-driven operational and strategic decisions.

---

## 🛠 2. Tech Stack

The dashboard was developed using:

- **Power BI Desktop** – Interactive reporting and visualization  
- **Power Query** – Data cleaning, shaping & transformation  
- **DAX (Data Analysis Expressions)** – KPIs, dynamic measures, disconnected tables  
- **Data Modeling** – Star schema, active/inactive relationships  
- **File Formats** – `.pbix` for development, `.csv` / `.xlsx` for exports  

---

## 📂 3. Data Source

This project uses a **CSV dataset uploaded directly in this repository** under the `/
Uber Trip Details.xlsx` folder.  
All data used for the analysis is available in the repository for transparency and reproducibility.

### **Dataset Contents**
The primary dataset includes trip-level details such as:
- Pickup & drop-off timestamps  
- Trip distance & trip duration  
- Fare amount & total booking value  
- Payment method (Cash, Card, Wallet, etc.)  
- Vehicle type  
- Pickup & drop-off location IDs  

---

## ⭐ 4. Features & Highlights

### 🔹 A. Business Problem
Uber needs insights into trip demand, revenue trends, time-based activity, and geographic hotspots to improve pricing, operations, and customer satisfaction.

### 🔹 B. Dashboard Goals
- Identify booking & revenue trends  
- Analyze trip efficiency  
- Detect peak demand times  
- Understand location-based patterns  
- Optimize operational decision-making  

---

### 🟦 **Dashboard 1: Overview Analysis**

**Key KPIs**
- Total Bookings  
- Total Booking Value  
- Average Booking Value  
- Total Trip Distance  
- Average Trip Distance  
- Average Trip Duration  

**Visuals & Features**
- Dynamic Measure Selector (Bookings / Revenue / Distance)  
- Filters: Payment Type, Trip Type (Day/Night), City, Date  
- Vehicle Type Analysis Grid (with conditional formatting)  
- Bookings by Day  
- Location Insights:
  - Most Frequent Pickup Point  
  - Most Frequent Drop-off Point  
  - Longest Trip (Distance)  
  - Top 5 Pickup Locations  
  - Most Preferred Vehicle by Location  

**Additional Enhancements**
- Data Details Bookmark  
- Clear Slicers Button  
- Export Raw Data Button  

---

### 🟧 **Dashboard 2: Time Analysis**

**Global Dynamic Measure**  
Applied across all visuals (Bookings / Revenue / Distance)

**Visuals**
- 10-Minute Interval Area Chart  
- Day-Name Trend Line Chart  
- Hour × Day Heatmap (Peak demand patterns)  

---

### 🟫 **Dashboard 3: Details Tab**

- Full trip-level data grid  
- Drill-through from all dashboards  
- Bookmark to switch between filtered data & full dataset  

---

## 📈 5. Business Impact

✔ Identify peak/low demand hours  
✔ Improve driver allocation and reduce idle time  
✔ Optimize pricing & surge strategy  
✔ Understand customer behavior and vehicle preferences  
✔ Better planning and decision-making  

---
## 🖼 6. Snapshorts Of The Dashboard

### Dashboard Overview
![Dashboard Screenshot 1](https://github.com/Akshat-Shailendra-Trivedi/Uber-Trip-Analysis/blob/main/Snapshort%20of%20dashboard.png)

### Time & Details View
![Dashboard Screenshot 2](https://github.com/Akshat-Shailendra-Trivedi/Uber-Trip-Analysis/blob/main/Snapshort%20of%20dashboard%202.png)


