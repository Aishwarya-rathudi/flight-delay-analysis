# ✈️ Flight Delay Analysis Dashboard

An interactive **Tableau** dashboard analyzing U.S. domestic flight delays and cancellations, highlighting trends, patterns, and contributing factors. This project combines data visualization with actionable insights to help stakeholders in the aviation industry understand delay dynamics and optimize operations.

🔗 **Live Dashboard**: [View on Tableau Public](https://public.tableau.com/app/profile/aishwarya.rathudi/viz/FlightDelaysDashboard_17539983690800/Dashboard)  

---
## 📌 Overview
Flight delays are a significant operational and financial challenge for airlines, airports, and passengers.  
This dashboard provides:
- A geographical breakdown of cancellations
- Delay trends by month, state, and airline
- Factors contributing to delays
- Seasonal and operational patterns

The dashboard is interactive, allowing users to drill down by **state, airline, and month** to gain deeper insights.

---

## 🎯 Objective
- **Identify** states, airlines, and months with the highest cancellations
- **Understand** main delay causes and their seasonal patterns
- **Highlight** operational bottlenecks for airlines and airports
- **Provide** a visual tool for quick decision-making and analysis

---

## 🛠 Tools & Technologies
- **Tableau Public** – Dashboard creation and visualization  
- **Data Source** – U.S. DOT Bureau of Transportation Statistics  
- **Chart Types Used** – Heatmaps, bar charts, area charts, line charts  

---

## 📊 Key Insights

### 1️⃣ Heatmap of Cancelled Flights  
🔗 [View Visualization](https://public.tableau.com/app/profile/aishwarya.rathudi/viz/HeatMap_17547815996910/Heatmap?publish=yes)  
- **Finding:** Texas recorded the highest cancellations, followed by Illinois and New York.  
- **Low Cancellation States:** West Virginia had fewer than 200 cancellations.  
- **Design Choices:**  
  - Heatmap with red gradient for severity  
  - Tooltips for exact numbers  
  - State highlight filter for focused exploration  

---

### 2️⃣ Cancelled Flights by State (Bar Chart)  
🔗 [View Visualization](https://public.tableau.com/app/profile/aishwarya.rathudi/viz/CancelledbyState_17547817539510/CancelledbyState?publish=yes)  
- **Finding:** Texas leads with **640k+ cancellations**, followed by Illinois and New York.  
- **Design Choices:**  
  - Horizontal bar chart for clear ranking  
  - Color scheme aligned with heatmap for consistency  
  - Tooltips and state filters for interactivity  

---

### 3️⃣ Factors Contributing to Flight Delays (Bar Chart)  
🔗 [View Visualization](https://public.tableau.com/app/profile/aishwarya.rathudi/viz/FactorsContributingtotheFlightDelay/DelayFactors?publish=yes)  
- **Finding:**  
  - Late Aircraft Delay (~23 min) is the largest contributor  
  - Followed by Air System Delay (~13 min) and Departure Delay (~10 min)  
- **Design Choices:**  
  - Bright orange bars for emphasis  
  - Tooltips with exact delay durations  

---

### 4️⃣ Causes for Delay Over the Months (Line & Area Chart)  
🔗 [View Visualization](https://public.tableau.com/app/profile/aishwarya.rathudi/viz/CausesforDelayOvertheMonths/Causesfordelay?publish=yes)  
- **Finding:**  
  - Late Aircraft Delays peak in **June–August**  
  - Other delay types remain moderately consistent  
- **Design Choices:**  
  - Distinct colors for each delay cause  
  - Combination of line chart & area overlay for clarity  
  - Monthly breakdowns via tooltips  

---

### 5️⃣ Cancelled Flights by Month (Area Chart)  
🔗 [View Visualization](https://public.tableau.com/app/profile/aishwarya.rathudi/viz/CancelledbyMonth_17547792176740/CancelledbyMonth?publish=yes)  
- **Finding:**  
  - Highest cancellations in **February (20,517)** and **January (11,982)** — likely due to winter weather and operational factors.  
- **Design Choices:**  
  - Single gradient for focus  
  - Tooltips for exact counts  
  - Month-level granularity for seasonal analysis  

---

### 6️⃣ Cancellations by Airline (Bar Chart)  
🔗 [View Visualization](https://public.tableau.com/app/profile/aishwarya.rathudi/viz/CancellationsbyAirline_17547791111430/CancellationsbyAirline?publish=yes)  
- **Finding:**  
  - Southwest Airlines (WN) tops with **15,721 cancellations**, significantly higher than others  
  - Suggests operational, route density, or hub-specific challenges  
- **Design Choices:**  
  - Distinct airline colors for comparison  
  - Sorted descending for quick interpretation  
  - Tooltips with airline name & exact figures  

---

## 📂 Data Source
- **Provider:** [U.S. DOT Bureau of Transportation Statistics](https://www.transtats.bts.gov/)  
- **Data Includes:**  
  - Flight dates & times  
  - Origin & destination airports  
  - Delay durations & causes  
  - Airline codes    
- **Data Cleaning:** Removed missing values, standardized date formats, aggregated metrics  

---

## 📸 Dashboard Preview
![Flight Delay Dashboard](flight%20delay%20Dashboard.png)  
![Cancellations by Airline](Cancellations%20by%20Airline.png)  
![Cancelled by Month](Cancelled%20by%20Month.png)  

---

## 📜 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

---

**Author:** Aishwarya Rathudi  
**GitHub:** [@yourusername](https://github.com/aishwarya.rathudi)  
**Tableau Public:** [Aishwarya's Profile](https://public.tableau.com/app/profile/aishwarya.rathudi)
