# Chicago Crime Power BI Dashboard

This **Power BI dashboard** maps, categorizes, and visualizes reported crime incidents in Chicago.  
It can be utilized by **law enforcement**, **government officials**, and **community leaders** to monitor and analyze crime patterns throughout the city.

---

## 🧭 How to Use

### 1. Prerequisites
- Must have the **desktop version of Power BI** installed.  
- Only the `.pbix` file needs to be downloaded, as all data sources are already loaded within it.

---

### 2. Data Sources

**Main Dataset:**  
[City of Chicago Data Portal – Crimes 2024](https://data.cityofchicago.org/Public-Safety/Crimes-2024/dqcy-ctma/about_data)

**Supplementary Dataset:**  
[Daily Sunrise and Sunset Times (Chicago)](https://www.timeanddate.com/sun/usa/chicago)

> The crimes dataset was merged with daily sunrise/sunset data to enable analysis of crime occurrence by time of day (day vs. night).

---

### 3. Key Visualizations and Features

#### A. Number of Incidents Filters
- **Incident Type Filter** – Selects which crime type to display.  
- **Date Filter** – Filters data between selected dates. *(Available range: Jan 1, 2024 – Nov 12, 2024)*

#### B. Number of Incidents Visuals
- **Incidents Heatmap** – Displays geographic frequency of reported crimes across Chicago.  
- **Incidents by Month and Arrest** – Shows incident counts by month and highlights how many resulted in arrests.

#### C. Time of Incidents Filters
- **Incident Type Filter** – Selects which crime type to display.  
- **Time of Day Filter** – Filters by the hour a crime occurred *(0 = 12 AM, 23 = 11 PM)*.

#### D. Time of Incidents Key Visuals
- **Crimes by Night and Day** – Heatmap showing where crimes occurred, with color differentiation for nighttime incidents.  
- **Number of Incidents by Hour of Day** – Displays the hourly distribution of crime occurrences.

---
