# Air-Line-Performance-Dashboard
This  analysis is for different airports from which the airlines depart and arrive. The average  delay time of an airline over a period of time and more.
# 🛫 Flight Analysis and Reporting – Power BI Project

This Power BI project is part of the Brain4ce Power BI Internship program. It analyzes airline flight data to provide actionable insights on delays, cancellations, traffic trends, and peak travel times across different airports and airlines.

---

## 📊 Objective

To transform raw flight data into a powerful, interactive dashboard that helps stakeholders:

- Understand delay trends and causes
- Analyze air traffic patterns
- Identify the best time to travel
- Make data-backed decisions for operational improvements

---

## 🧠 Data Modeling

The Power BI data model follows a **star schema** approach to enable scalable, performant reporting.

### 🔹 Fact Table
- **FlightFact**  
  Contains detailed records for each flight, including:  
  - Flight ID  
  - Airline  
  - Departure & Arrival Airports  
  - Flight Date & Time  
  - Flight Status (On-time / Delayed / Cancelled)  
  - Delay Duration (in minutes)

✅ **Excel** was used as the data source. Relationships were built in Power BI to enable cross-filtering, visual interactions, and DAX-based aggregations.



---

## 📈 Key Insights & Dashboard Features

- **Flight Status Analysis**
  - Month-wise and Airline-wise summary of On-time, Delayed, and Cancelled flights
  - Average delay time per airline and month
- **Air Traffic Analysis**
  - Peak hours for departures/arrivals
  - Best time slots to book flights
  - Region-wise airport traffic heatmaps
- **Interactive Filters**
  - Slicers for Airline, Status, Month, and Airport
- **KPIs**
  - Total flights, delayed % share, average delay in minutes

---

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Data modeling, DAX, visuals
- **Power Query Editor** – Data cleaning & transformation
- **DAX (Data Analysis Expressions)** – Measures & KPIs
- **Excel** – Raw data source for flight information

---

## 🔗 Files

- `Final project_Flight analysis report.pbix` – Main Power BI report file  
- Excel dataset – Loaded into `.pbix` (not shared publicly due to training license)

---

## 🌐 Deployment

- Published to Power BI Service
- Tiles pinned to dashboard for sharing with colleagues
- Ready for embedding, sharing, and collaboration

---
