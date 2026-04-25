# Ola-Analysis
# 🚖 Ola Ride Analysis: Bengaluru Booking Insights Dashboard

A dynamic, interactive data visualization tool built to explore Ola ride-booking data for Bengaluru — focusing on booking performance, revenue trends, cancellation patterns, vehicle type comparisons, and customer/driver ratings.

---

## 📋 Short Description / Purpose

The Ola Ride Analysis Dashboard is a visually engaging and analytical Power BI report designed to help users explore and compare ride-booking outcomes across Bengaluru for the month of July 2024. The dashboard focuses on highlighting key operational metrics such as booking success rates, revenue by payment method, cancellation reasons (by both customers and drivers), and rating trends across vehicle categories. This tool is intended for use by operations analysts, business strategy teams, ride-hailing platform managers, and data enthusiasts who seek to understand the performance, demand patterns, and service quality of Ola's Bengaluru operations.

---

## 🛠️ Tech Stack

The dashboard was built using the following tools and technologies:

- 📊 **Power BI Desktop** – Main data visualization platform used for report creation and layout design.
- 📂 **Power Query** – Data transformation and cleaning layer for reshaping and preparing the booking dataset.
- 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures such as cancellation rate, total bookings value, and ride distance aggregations.
- 📝 **Data Modeling** – Relationships established between the `Bengaluru_Ola_Booking_Data` and `July` tables to enable cross-filtering and accurate aggregations.
- 📁 **File Format** – `.pbix` for development and `.png` for dashboard previews.

---

## 🗃️ Data Source

**Source:** Bengaluru Ola Booking Records — July 2024

Data covering ride bookings in Bengaluru across the full month of July 2024, including details on booking status, vehicle type, fare value, ride distance, payment method, cancellation reasons, and customer/driver ratings. The dataset is structured across two related tables:

- `Bengaluru_Ola_Booking_Data` — Primary bookings table with booking IDs, dates, statuses, and fare values.
- `July` — Extended table with granular metrics including ratings, cancellation breakdowns, ride distance, and payment methods.

---

## ✨ Features / Highlights

### 🔴 Business Problem

The ride-hailing industry is highly competitive and operationally complex. Platform managers and analysts often lack a centralized, intuitive way to monitor booking health, identify cancellation drivers, and evaluate performance across vehicle segments.

Key questions such as:
- What percentage of bookings are being cancelled — and who is initiating them?
- Which vehicle categories generate the most revenue?
- How are customer and driver ratings distributed across ride types?
- What are the most common reasons for ride cancellations?

…are difficult to answer quickly from raw data alone.

---

### 🎯 Goal of the Dashboard

To deliver an interactive visual tool that:
- Enables operations teams to monitor booking success, cancellations, and revenue in one place.
- Supports decisions around driver management, customer retention, and vehicle category investment.
- Uncovers trends in ride performance, cancellation behaviour, and service quality by date and vehicle type.

---

### 🖥️ Walkthrough of Key Visuals

**Key KPIs (Cards)**
- Total Bookings
- Total Booking Value (Revenue)
- Succeeded Bookings
- Cancelled Bookings
- Cancellation Rate

**Booking Status Page (Overall)**
- Ride Volume Over Time *(Line Chart)* — Tracks daily booking trends across July 2024 to identify demand peaks and dips.
- Booking Status Breakdown *(Pie Chart)* — Splits bookings into Success, Incomplete, and Cancelled categories for a quick health check.
- Total Bookings Value *(KPI Card)* — Displays the aggregate revenue generated across all bookings.

**Revenue Page**
- Revenue by Payment Method *(Column Chart)* — Compares booking value across different payment modes.
- Revenue by Vehicle Type — Breaks down fare contribution by Mini, Auto, Prime Sedan, Prime SUV, Prime Plus, and eBike categories.

**Cancellation Page**
- Cancelled Rides by Customer *(Pie Chart)* — Shows the count and share of customer-initiated cancellations.
- Cancelled Rides by Driver *(Pie Chart)* — Shows the count and share of driver-initiated cancellations.
- Cancellation Reasons Breakdown — Visual breakdown of specific cancellation reasons including:
  - *Customer-side:* Change of plans, Wrong address, Driver asked to cancel, Driver not moving to pickup
  - *Driver-side:* Customer was coughing/sick, AC not working, More than permitted passengers, Personal & car-related issue

**Ratings Page**
- Customer Rating Distribution — Visualises how customers rate their rides.
- Driver Rating Distribution — Visualises how drivers are rated across trips.
- Ratings by Vehicle Type — Compares average ratings across Mini, Auto, Prime Sedan, Prime SUV, Prime Plus, and eBike.

**Vehicle Type Page**
- Performance by Vehicle Category — Side-by-side comparison of booking volume, revenue, and ratings across all six vehicle types.
- Vehicle Type Slicer — Interactive filter panel allowing users to isolate any vehicle category across all visuals.

---

### 💡 Business Impact & Insights

- **Cancellation Management:** Operations teams can identify whether cancellations are predominantly driver- or customer-driven and target interventions accordingly (e.g., driver training, customer incentives).
- **Revenue Optimisation:** Breaking revenue down by vehicle type and payment method helps prioritise high-value segments and preferred payment rails.
- **Service Quality Monitoring:** Rating trends allow management to flag underperforming vehicle categories or time periods and take corrective action.
- **Demand Planning:** The ride volume time series reveals peak demand days in July, enabling smarter driver allocation and surge pricing strategies.
- **Customer Retention:** Understanding top cancellation reasons (e.g., "Driver not moving towards pickup") highlights friction points that directly impact customer experience and loyalty.

---

## 📸 Screenshots / Demo
> Overall
![image](https://github.com/MuralidharChidarala/Ola-Analysis/blob/b3750464f2dea66bd214ab3e044bc9dd1e780319/Screenshot%202026-04-24%20163544.png)

> Vehicle Type 
![image](https://github.com/MuralidharChidarala/Ola-Analysis/blob/64d99a9460f7eec4d1ac08e255eaa704cf51617c/img2.png)
> Revenue 
![image](https://github.com/MuralidharChidarala/Ola-Analysis/blob/b3750464f2dea66bd214ab3e044bc9dd1e780319/Screenshot%202026-04-24%20163544.png)
> Cancellation 
![image](https://github.com/MuralidharChidarala/Ola-Analysis/blob/b3750464f2dea66bd214ab3e044bc9dd1e780319/Screenshot%202026-04-24%20163544.png)
> Rating 
![image](https://github.com/MuralidharChidarala/Ola-Analysis/blob/fc7fc1196433499147f4971233cb297ee082c2ec/img1.png)
