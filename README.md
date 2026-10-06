# 🚕 Uber Trip Analysis Dashboard | Power BI

## 📌 Project Overview

The **Uber Trip Analysis Dashboard** is an interactive **Power BI project** designed to analyze Uber trip data and provide meaningful insights into **bookings, revenue, trip distance, trip duration, vehicle performance, payment methods, time-based trends, and location patterns**.

The dashboard helps stakeholders make **data-driven decisions** by identifying peak demand periods, high-performing locations, popular vehicle types, and revenue trends.

---

# 📊 Dashboard Structure
(![imagealt](https://github.com/tusharsgupta7/PowerBI-Uber-Trip-Analysis-Dashboard/blob/09851b9201e6825374157cbc846240144b6dc471/Screenshot/Overview%20Analysis.png)

## 🎯 Business Objective

The main objective of this project is to analyze Uber trip data and answer key business questions related to:

- 📊 Booking trends
- 💰 Revenue and booking value
- 🚕 Trip distance and duration
- 🚗 Vehicle type performance
- 💳 Payment method preferences
- 🕐 Peak and off-peak periods
- 📍 Pickup and drop-off locations
- 📅 Daily and weekly demand patterns

---
## 1️⃣ Overview Analysis

The **Overview Dashboard** provides a high-level summary of Uber trip performance.

### 🔑 KPIs

- **Total Bookings** – Total number of Uber trips.
- **Total Booking Value** – Total revenue generated from bookings.
- **Average Booking Value** – Average revenue per booking.
- **Total Trip Distance** – Total distance covered by all trips.
- **Average Trip Distance** – Average distance travelled per trip.
- **Average Trip Time** – Average duration of trips.

### 📈 Key Visualizations

- Dynamic Measure Analysis
- Bookings by Payment Type
- Bookings by Trip Type – Day/Night
- Vehicle Type Performance Grid
- Total Bookings by Day
- Top 5 Pickup Locations
- Most Frequent Pickup Point
- Most Frequent Drop-off Point
- Farthest Trip
- Most Preferred Vehicle by Pickup Location

### 🔄 Dynamic Measure Selector

A **Disconnected Table** is used to create a dynamic measure selector containing:

- Total Bookings
- Total Booking Value
- Total Trip Distance

The selected measure dynamically updates multiple dashboard visualizations.

### 🎛️ Interactive Features

- Date Slicer
- City Slicer
- Dynamic Titles
- Tooltips
- Sorting and Filtering
- Conditional Formatting

---

# 2️⃣ ⏰ Time Analysis

The **Time Analysis Dashboard** focuses on understanding Uber demand throughout different time periods.

### 📈 Visualizations

#### Pickup Time – 10-Minute Intervals
An **Area Chart** groups bookings into 10-minute intervals to identify:

- Peak demand periods
- Off-peak periods
- High-demand time slots

#### Day Name Analysis
A **Line Chart** displays booking trends from:

**Monday → Sunday**

This helps compare **weekday and weekend demand**.

#### Hour & Day Heatmap

A **Matrix Heatmap** displays:

- Rows → Hours of the Day (0–23)
- Columns → Days of the Week
- Values → Selected Dynamic Measure

This helps identify **peak booking hours across different days**.

### 🌐 Global Dynamic Measure

The same dynamic measure selector is used across the Time Analysis dashboard:

- Total Bookings
- Total Booking Value
- Total Trip Distance

---

# 3️⃣ 📋 Details Tab

The **Details Dashboard** provides granular trip-level information.

### 📑 Grid Table

The grid displays important trip details such as:

- Trip ID
- Pickup Time
- Drop-off Time
- Passenger Count
- Trip Distance
- Pickup Location
- Drop-off Location
- Payment Type
- Fare Amount
- Surge Fee
- Vehicle Type

### 🔍 Drill-Through

Users can **right-click on a data point** from other dashboard visuals and drill through to the Details page.

This allows users to investigate the underlying trip records related to a selected:

- Date
- Location
- Vehicle
- Time period
- Other dashboard selections

### 🔖 Bookmark

A **"View Full Data" Bookmark** allows users to switch between:

- Filtered drill-through data
- Complete dataset

---

# 📍 Location Analysis

Location analysis helps understand where Uber trips are concentrated.

### Key Analysis

**Most Frequent Pickup Point**  
Identifies locations with the highest number of trip pickups.

**Most Frequent Drop-off Point**  
Identifies the most common trip destinations.

**Farthest Trip**  
Identifies the trip with the longest travel distance.

**Top 5 Locations**  
Highlights the five locations with the highest number of bookings.

**Preferred Vehicle by Location**  
Identifies the most frequently used vehicle type at each pickup location.

---

# 🛠️ Tools & Technologies

- **Power BI Desktop**
- **Power Query**
- **DAX**
- **Data Modeling**
- **Excel / CSV Dataset**
- **Power BI Bookmarks**
- **Power BI Drill-Through**
- **Interactive Slicers**
- **Dynamic Measures**
- **Conditional Formatting**

---

# 🧮 DAX & Power BI Concepts Used

This project demonstrates practical use of:

- Measures
- Calculated Columns
- Disconnected Tables
- Dynamic Measure Selection
- Dynamic Titles
- DAX Functions
- Date & Time Analysis
- Relationships
- Active & Inactive Relationships
- Filter Context
- Conditional Formatting
- Drill-Through
- Bookmarks
- Tooltips
- Slicers

---

# 📌 Data Model

The project uses two main tables:

### 🚕 Trip Details

Contains information about individual Uber trips, including:

- Trip ID
- Pickup Time
- Drop-off Time
- Passenger Count
- Trip Distance
- Pickup Location ID
- Drop-off Location ID
- Payment Type
- Fare Amount
- Surge Fee
- Vehicle

### 📍 Location Table

Contains:

- Location ID
- Location
- City

The **Trip Details** table is connected to the **Location Table** using location IDs for pickup and drop-off analysis.

---

# 💡 Key Business Insights

The dashboard is designed to help stakeholders:

- Identify **peak booking periods**
- Understand **revenue trends**
- Find **high-demand locations**
- Analyze **vehicle preferences**
- Compare **payment methods**
- Identify **long-distance trips**
- Understand **weekday vs. weekend demand**
- Optimize **driver allocation**
- Improve **pricing strategies**
- Support better **operational planning**

---

# 🎛️ Additional Dashboard Features

### 🔖 Data Details Bookmark

Provides information about:

- KPI definitions
- Tables used
- Data source
- Data refresh information

### 🧹 Clear Filters

A **Clear Filters** button allows users to reset slicer selections and quickly return to the default dashboard view.

### 📥 Download Raw Data

Users can export underlying data for further analysis using available **Power BI export functionality**.

---

# 📂 Project Structure

```text
Uber-Trip-Analysis/
│
├── Dataset/
│   ├── Trip_Details.csv
│   └── Location.csv
│
├── PowerBI/
│   └── Uber_Trip_Analysis.pbix
│
├── Screenshots/
│   ├── Overview.png
│   ├── Time_Analysis.png
│   └── Details.png
│
└── README.md
```

---

# 🚀 Project Outcome

This project demonstrates how **Power BI can transform raw Uber trip data into an interactive business intelligence solution**.

The dashboard combines **KPIs, dynamic measures, time analysis, location analysis, vehicle analysis, drill-through, bookmarks, and interactive filters** to provide a comprehensive view of Uber trip performance.

---

## 👩‍💻 Skills Demonstrated

**Power BI | DAX | Power Query | Data Cleaning | Data Modeling | Data Visualization | Business Analysis | KPI Development | Time Analysis | Location Analysis**
