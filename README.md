# ✈️ Airline Performance & Cancellation Analysis | Power BI

An interactive **Power BI dashboard** designed to analyze airline operations, flight volume, cancellations, delays, routes, airport activity, and on-time performance from **2019–2023**.

The project transforms airline flight data into actionable insights through interactive dashboards, KPIs, drill-through analysis, geographical visualization, trend analysis, and flight-volume forecasting.

---

## 📊 Project Overview

This dashboard provides a comprehensive view of airline operational performance and helps answer key business questions such as:

* How many flights were operated?
* What percentage of flights were cancelled?
* Which airlines have the highest flight volume?
* Which airlines experience the highest departure delays?
* What are the major reasons for flight cancellations?
* How has on-time performance changed from 2019 to 2023?
* Which airports have the highest destination flight volume?
* How does cancellation rate vary across airlines and years?
* What are the monthly flight-volume trends?
* What does the future flight-volume forecast look like?

---

## 🖥️ Dashboard Pages

### 1. Airline Performance & Cancellation Overview

Provides an executive-level summary of airline operations.

**Key KPIs:**

* Total Flights: **3M**
* Total Cancelled Flights: **79K**
* Cancellation Rate: **2.64%**
* On-Time Rate: **82.32%**

**Visualizations include:**

* Flight Cancellation by Cause
* Airline Comparison
* Flight Outcome Distribution
* Airline Performance Overview
* Overall On-Time Rate vs 80% Target

---

### 2. Airline Performance & Delay Analysis

Focuses on delays and cancellation performance across airlines.

**Key Metrics:**

* Average Departure Delay: **10.10 minutes**
* Average Arrival Delay: **4.26 minutes**
* Cancellation Rate: **2.64%**
* On-Time Rate: **82.32%**

**Analysis includes:**

* Top 10 Airlines by Average Departure Delay
* Top 10 Airlines by Cancellation Count
* Airline Cancellation Rate Heatmap by Year
* Departure & Arrival Delay Analysis

---

### 3. Airline Trends & Flight Volume Forecast

Analyzes monthly and yearly flight trends from 2019–2023 and provides a future flight-volume forecast.

**Visualizations include:**

* Monthly Average Departure Delay by Year
* Monthly Flight Volume by Year
* Total Monthly Flight Volume Trend
* 6-Month Flight Volume Forecast

This page helps identify seasonality, operational changes, and future flight-volume patterns.

---

### 4. Airline Route & Airport Analysis

Provides geographical and airport-level analysis.

**Analysis includes:**

* Total Flights by Airline
* US Departure Airport Flight Volume
* Average Airport Delay
* US State Cancellation Rate
* Geographic Distribution of Flight Operations

Interactive maps are used to visualize flight activity and cancellation patterns across locations.

---

### 5. Airline Drill-Through Analysis

Provides detailed analysis for a selected airline.

Users can select an airline and investigate:

* Total Flights
* Total Cancelled Flights
* Cancellation %
* Monthly Cancellation Trends
* Cancellation Causes
* On-Time Rate by Year
* Detailed Flight-Level Records

This enables users to move from high-level KPIs to detailed operational data.

---

### 6. Route & Airport / Tooltip Analysis

Additional interactive views provide contextual information about destinations, airports, and airline performance.

The dashboard includes:

* Top 5 Destination Airports
* Airport Flight Volume
* Airline/Route details
* Interactive tooltip analysis
* Dynamic filtering

---

## 🎯 Key Insights

Some important insights identified from the dashboard include:

### ✈️ Overall Performance

The dataset contains approximately **3 million flights**, with around **79K cancellations**, resulting in an overall cancellation rate of **2.64%**.

### ⏱️ On-Time Performance

The overall on-time rate is approximately **82.32%**, which is above the dashboard's **80% target**.

### ❌ Cancellation Causes

The major cancellation causes include:

* Weather
* Security
* National Air System
* Airline/Carrier-related causes

Weather represents the largest cancellation category in the dashboard.

### 🏆 Flight Volume

**Southwest Airlines (WN)** has the highest flight volume among the airlines analyzed, with approximately **576K flights**.

### 🛫 Destination Airports

The top destination airports by flight volume include:

1. **ATL — 154K**
2. **DFW — 130K**
3. **ORD — 123K**
4. **DEN — 120K**
5. **CLT — 95K**

### ⏰ Departure Delays

The dashboard identifies airlines with higher average departure delays, helping highlight areas requiring operational improvement.

---

## 🛠️ Tools & Technologies

* **Power BI**
* **Power Query**
* **DAX**
* **Data Modeling**
* **Microsoft Bing/Azure Maps**
* **Time Intelligence**
* **Forecasting**
* **Interactive Slicers**
* **Drill-Through**
* **Data Visualization**

---

## 📐 Key Power BI Concepts Used

This project demonstrates practical use of:

* DAX Measures
* Calculated Columns
* CALCULATE
* DIVIDE
* AVERAGE
* COUNTROWS
* Filter Context
* Time Intelligence
* Date Tables
* Relationships
* KPI Cards
* Conditional Formatting
* Drill-Through Pages
* Slicers
* Tooltips
* Forecasting
* Geographic Mapping

---

## 🎛️ Interactive Filters

The dashboard contains interactive filters for:

* **Airline Code**
* **Delay Status**
* **Flight Year**

These filters dynamically update the dashboard visuals and allow users to perform focused analysis.

---

## 📸 Dashboard Preview

### Airline Performance Overview

![Airline Overview](AIRLINE%20OVERVIEW.png)

### Airline Performance & Delay Analysis

![Airline Performance](AIRLINE%20PERFORMANCE.png)

### Airline Trends & Forecast

![Airline Trends & Forecast](AIRLINE%20TRENDS%20%26%20FORECAST.png)

### Route & Airport Analysis

![Route & Airport Analysis](ROUTE%20%26%20AIRPOT%20MAP.png)

### Airline Drill-Through

![Airline Drill Through](AIRLINE%20DRILL%20THROUGH.png)

### Tooltip Analysis

![Airline Tooltip](AIRLINE%20TOOLTIP.png)

---

## 📁 Project Structure

```text
Airline-Performance-PowerBI/
│
├── README.md
│
├── Dataset/
│   └── airline_data.csv
│
├── PowerBI/
│   └── Airline_Performance.pbix
│
└── Screenshots/
    ├── AIRLINE OVERVIEW.png
    ├── AIRLINE PERFORMANCE.png
    ├── AIRLINE TRENDS & FORECAST.png
    ├── ROUTE & AIRPOT MAP.png
    ├── AIRLINE DRILL THROUGH.png
    └── AIRLINE TOOLTIP.png
```

---

## 🚀 Business Value

This dashboard can help airline management and operations teams:

* Monitor flight performance
* Identify cancellation patterns
* Track airline-level operational efficiency
* Analyze airport performance
* Understand delay trends
* Compare yearly performance
* Identify high-volume routes and airports
* Monitor on-time performance against targets
* Support operational decision-making
* Forecast future flight demand

---

## 📌 Conclusion

The **Airline Performance & Cancellation Analysis Dashboard** converts millions of flight records into an interactive business intelligence solution.

By combining **Power BI, DAX, Power Query, interactive visualization, geographic analysis, drill-through functionality, and forecasting**, the dashboard provides a complete view of airline operational performance from **2019 to 2023**.

---

## 👨‍💻 Author

**Kanish Singh**

**Skills:** Power BI | DAX | Power Query | SQL | Excel | Data Analytics | Data Visualization

---

⭐ **If you find this project useful, consider giving this repository a star!**
