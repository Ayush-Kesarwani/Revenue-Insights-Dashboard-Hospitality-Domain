# 📊 Revenue Insights in the Hospitality Domain

## 📌 Project Overview

This project focuses on analyzing **hotel bookings and revenue performance** in the hospitality industry. The goal was to build an interactive **Power BI dashboard** that provides actionable insights into **occupancy, revenue realization, cancellations, room-class performance, and property-wise contribution**.

The dataset consists of multiple **fact and dimension tables**, modeled in a **star schema**, to enable smooth drill-down from overall KPIs to **city-level, property-level, and room-level insights**.

---

## 🔧 Data Model

* **Fact Tables:**

  * `fact_bookings` → booking-level details (status, revenue, cancellations, guests).
  * `fact_aggregated_bookings` → daily bookings vs capacity by room type.
* **Dimension Tables:**

  * `dim_hotels` → hotel properties, city, and category.
  * `dim_rooms` → room types and room class.
  * `dim_date` → calendar, month, weekday/weekend indicators.

---

## 📈 Key Insights from the Dashboard

* Total Revenue: **₹1.69B** with **70.1% realization**, exposing \~**30% revenue leakage** due to cancellations/refunds.
* Average Occupancy: **57.8%**, with weekends showing a **+7% uplift** compared to weekdays.
* Cancellation Rate: **24.8%** of total bookings.
* Room-Class Contribution: **Elite and Presidential rooms contributed 60%+ of revenue** despite fewer bookings.
* City Contribution: Top 3 cities (Bangalore, Hyderabad, Delhi) generated **\~75% of total revenue**.
* Property-Wise: Top 5 properties individually contributed **100M+ each**, with Atiq Exotica leading at \~117M (\~22% of revenue).

---

## 🚀 Outcomes

* Helped identify **key revenue leakage drivers** (cancellations, platform-specific performance).
* Showed opportunities to **optimize pricing and upsell premium rooms**.
* Highlighted **market concentration risks** and **growth opportunities** across cities.
* Delivered a **centralized decision-making tool** for management to monitor performance across dimensions.

---

## 🛠️ Tools & Technologies

* **Power BI** – Dashboarding & Visual Analytics
* **DAX** – Custom measures (Occupancy %, ADR, RevPAR, Cancellation %, Revenue % contribution)
* **MS SQL Server** – Data extraction & transformation
* **Data Modeling** – Star schema with fact/dimension tables

---

## ✨ Learning Outcomes

* Gained hands-on experience in **Power BI data modeling**, **DAX measures**, and **dashboard design**.
* Learned how to connect and manage **multiple fact and dimension tables** for business reporting.
* Applied **business analytics mindset** to derive actionable recommendations in the hospitality sector.
