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

### 🔸 Dimension Tables
- **DimAirline** – Airline name, car
