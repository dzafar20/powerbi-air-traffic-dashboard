# ✈️ Air Traffic Status Dashboard

A Power BI dashboard analyzing **2 million+ flights**, breaking down total volume, delays, and cancellations across major airports — including a deep dive into why flights get cancelled.

![Dashboard Preview](dashboard-preview.png)

## 🎯 Key Insights

- 🛫 **Volume:** 2M total flights analyzed, with **Atlanta** as the busiest hub (350K)
- ⏱️ **Delays:** 790K delayed flights — Atlanta (130K) and Chicago (121K) lead the list
- ❌ **Cancellations:** 29K canceled flights, with a clear weekly pattern
- 🌧️ **Weather is the #1 cancellation cause:** 57.3% of cancellations are weather-related, far ahead of airline/carrier issues (28.3%) and air traffic system delays (14.4%)
- 📊 **Performance summary:** 58% on-time, 41% delayed, 1% cancelled

## 🛠️ Tools & Skills Used

- Power BI Desktop
- DAX (measures, calculated columns)
- Data modeling (4 related tables)
- KPI design with sparkline trends
- Dark-theme dashboard design

## 📁 Files

- `Air Traffic Report.pbix` — main Power BI report
- `flights.csv` — flight records dataset
- `airports.csv` — airport reference data
- `airlines.csv` — airline reference data
- `cancellation_codes.csv` — cancellation reason codes
- `dashboard-preview.png` — dashboard screenshot

## 📊 Visualizations Included

1. **KPI cards with sparklines** — Total flights, delays, and cancellations with trends
2. **Horizontal bar charts** — Top 10 airports by flight volume and by delays
3. **Donut chart** — Cancellation reason breakdown
4. **Column chart** — Cancellations by day of the week
5. **Status summary cards** — On-Time / Delayed / Cancelled percentages
6. **Stacked bar** — Status distribution overview

## 💡 Business Value

This dashboard helps airline operations teams:
- Identify which airports need more delay-mitigation resources
- Plan staffing around predictable cancellation patterns
- Quantify the impact of weather vs. operational issues on cancellations
- Communicate performance to stakeholders with clean, scannable visuals

## 🚀 How to Open

1. Download the `.pbix` file
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/en-us/desktop/) (free)
3. Interact with the visualizations and explore the data!
