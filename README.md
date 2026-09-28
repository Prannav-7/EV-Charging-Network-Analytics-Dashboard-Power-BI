# EV-Charging-Network-Analytics-Dashboard-Power-BI

# **EV Charging Network Analytics Dashboard | Power BI**

## **📌 Project Overview**

The **EV Charging Network Analytics Dashboard** is an interactive Power BI project developed to analyze EV charging network performance using **100K+ charging session records**.

The dashboard transforms raw charging data into meaningful business insights across **revenue, charging sessions, energy consumption, station performance, utilization, waiting time, vehicle types, cities, and location types**.

---

## **🎯 Objectives**

- Analyze overall EV charging network performance
- Track charging sessions and revenue trends
- Monitor energy consumption across vehicle types
- Identify top-performing charging stations
- Analyze charger utilization by hour
- Compare charging demand across cities
- Analyze revenue by location type
- Monitor charging duration and waiting time
- Provide interactive filtering for detailed analysis

---

## **📊 Dashboard Features**

### **Executive KPIs**
- Total Charging Sessions
- Total Revenue
- Total Energy Consumption
- Average Charging Duration
- Average Waiting Time
- Average Charger Utilization

### **Revenue Analysis**
- Monthly Revenue Trend
- Revenue by Location Type
- Top 10 Stations by Revenue

### **Charging & Energy Analysis**
- Charging Sessions by City
- Energy Consumption by Vehicle Type
- Utilization Rate by Hour
- Charging demand patterns across different time periods

### **Interactive Filters**
- Date
- City
- Charger Type
- Vehicle Type
- Vehicle Brand
- Customer Type
- Weather

---

## **🛠️ Tools & Technologies**

**Power BI | DAX | Power Query | Data Modeling | Data Visualization | Excel/CSV**

---

## **📂 Dataset**

The project uses a structured EV charging session dataset containing **100K+ records**.

The dataset includes:

- Session details
- Date and time
- Charging station information
- City and state
- Location type
- Charger type
- Charging power
- Vehicle model and brand
- Vehicle type
- Customer type
- Membership
- Payment method
- Energy consumption
- Revenue
- Charging duration
- Waiting time
- Utilization rate
- Weather
- Traffic conditions
- Local events

Each row represents an individual **EV charging session**.

---

## **📈 Key DAX Measures**

```DAX
Total Sessions =
DISTINCTCOUNT(EV_Charging_Analytics_100K[SessionID])
