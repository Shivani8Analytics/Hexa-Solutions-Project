# Hexa-Solutions-Project
# 🚗 Uber Supply-Demand Gap Analysis (EDA Project)

## 📌 Project Overview
This project performs an end-to-end **Exploratory Data Analysis (EDA)** on Uber's trip request dataset to identify the core operational bottlenecks causing the severe **Supply-Demand Gap**. By analyzing ride statuses across various pickup locations and peak time slots, this project uncovers why passengers face high cab unavailability and ride cancellations, and provides actionable business solutions to optimize ride fulfillment and maximize revenue.

---

## 🎯 Key Business Objectives
1. **Cancellation Root Cause Analysis:** Identify key reasons and time windows for high ride cancellations by drivers.
2. **Dynamic Pricing & Transparency:** Suggest strategies to increase fare transparency and driver incentives.
3. **Customer Retention & Satisfaction:** Formulate solutions to minimize passenger wait times and churn.
4. **Competitive Advantage:** Recommend operational enhancements to drive higher app engagement over competitors.
5. **Night-time Safety & Reliability:** Propose safety measures and verification protocols, specifically for late-night rides.

---

## 🔍 Major Findings & Insights
* **The Airport Supply Bottleneck (Evening Peak | 17:00 – 22:00):** 
  * Over **1,700 trip requests** faced a **"No Cars Available"** issue at the Airport pickup point.
  * *Root Cause:* High volume of evening incoming flights coincides with low city-to-airport traffic, leaving drivers reluctant to drive to the airport without a guaranteed return trip.
* **The City Cancellation Bottleneck (Morning Peak | 05:00 – 10:00):**
  * Highest cancellations (**1,066 rides**) occur for **City pickup points** during early morning hours.
  * *Root Cause:* Drivers cancel airport-bound rides due to anticipated long idle waiting times at the airport before securing a return ride back to the city.
* **Overall Ride Status Distribution:**
  * **Completed Trips:** ~2,831 (42%)
  * **No Cars Available:** ~2,650 (39%)
  * **Cancelled Trips:** ~1,264 (19%)

---

## 🛠️ Strategic Business Solutions
* **Destination & Shift Incentives:** Implement guaranteed return-dispatch priority and bonus payouts for drivers accepting early morning airport trips from the city.
* **Flight Schedule Integration & Surge Pricing:** Sync surge alerts with real-time airport landing schedules during evening peak hours (17:00–22:00) to attract off-duty drivers to airport buffer zones.
* **Pre-scheduled Advance Bookings:** Allow passengers to pre-book airport-bound rides with locked fare assurances to curb last-minute cancellations.
* **Enhanced Fare Transparency:** Display clear upfront fare breakdowns (base, distance, peak surge) on the rider app and transparent earning estimates on the driver app.
* **Night Safety Protocol:** Mandate live GPS tracking, in-app emergency SOS buttons, and facial verification for late-night airport pickups.

---

## 🧰 Tech Stack & Libraries
* **Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`, `plotly`, `missingno`
* **Environment:** Jupyter Notebook

---


