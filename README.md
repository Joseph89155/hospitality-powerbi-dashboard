# 🏨 Hospitality Business Intelligence Dashboard with Power BI

This project showcases an end-to-end **Business Intelligence solution** developed using **Power BI** for the hospitality industry. The dashboard provides deep insights into hotel performance metrics such as Revenue, RevPAR, Occupancy Rate, ADR, and Realisation %, enabling hotel managers and executives to make data-driven decisions.

> 📊 **Objective**: To analyze hotel data using Power BI and build an interactive dashboard that supports effective business decision-making.

---

## 🚀 Project Overview

This project was built following a structured data analysis pipeline:

1. **Load and Transform Data**
2. **Data Modeling using Star Schema**
3. **DAX for Metrics Creation**
4. **Interactive Dashboard Design**

All steps are based on a real-world dataset provided via Codebasics' Data Analyst resources.

---

## 🔧 Steps Followed

### 1. 🗂️ Load and Transform Data
- Imported multiple CSV files including:
  - `dim_date`
  - `dim_rooms`
  - `dim_hotels`
  - `fact_bookings`
- Used Power Query Editor to clean, filter, and rename columns.
- Ensured consistency in data types and handled missing values for robust transformation.

### 2. 🌟 Build the Data Model (Star Schema)
- Constructed a **Star Schema** where:
  - `fact_bookings` serves as the central fact table
  - Dimension tables: `dim_date`, `dim_hotels`, `dim_rooms`, and others
- Established one-to-many relationships using appropriate keys.
- Ensured referential integrity for seamless analysis across tables.

### 3. 🧠 Create Columns & Measures using DAX
- Developed DAX Measures to compute:
  - `Revenue`
  - `RevPAR (Revenue per Available Room)`
  - `Occupancy %`
  - `ADR (Average Daily Rate)`
  - `Realisation %`, `DSRN`, `DBRN`
- Added time intelligence measures using `dim_date` to analyze trends across weeks and months.
- Created calculated columns to segment by booking platform and room type.

### 4. 📈 Design an Interactive Dashboard
- Built an intuitive dashboard with:
  - **KPI cards** for high-level metrics
  - **Trend lines** to observe changes in RevPAR, ADR, and Occupancy over time
  - **Pie chart** to segment revenue by category (Luxury vs Business)
  - **Bar & line combo chart** to show Realisation % vs ADR by booking platform
  - **Data table** for detailed property-level performance
- Added dynamic filters for:
  - City
  - Room Type
  - Date and Week Range
- Prioritized visual storytelling and business clarity for stakeholders.

---

## 📸 Dashboard Preview

![Hospitality Dashboard](![10  Dashboard](https://github.com/user-attachments/assets/da4c7f50-36b4-4d06-9e20-7ab084a908fd)
)

---

## ✅ Business Impact

This dashboard enables:
- Real-time performance tracking across hotel properties
- Identification of high and low-performing cities, room types, and booking platforms
- Enhanced revenue forecasting and customer behavior analysis
- Strategic data-driven decision making

---

## 📚 Data Source

- Dataset: Provided by [Codebasics Data Analyst Project](https://codebasics.io/resources/end-to-end-data-analyst-project)

---

## 🧠 Key Learnings

- Applied **Power Query** for real-world data cleaning
- Practiced **data modeling** using best practices in dimensional modeling
- Gained proficiency in **DAX** to compute actionable KPIs
- Learned to design user-friendly and insightful dashboards for executives

---

## 📁 Folder Structure

📦PowerBI-Hospitality-Project

┣ 📊 Dashboard.pbix

┣ 📁 data

┃ ┣ dim_date.csv

┃ ┣ dim_hotels.csv

┃ ┣ dim_rooms.csv

┃ ┣ fact_bookings.csv

┣ 📷 10. Dashboard.JPG

┗ 📄 README.md

---

## 🧑‍💼 Author

**Joseph Maina**  
Power BI Developer & Data Scientist/Analyst  

---

## 📌 License

This project is for educational purposes only. Data used is publicly available via Codebasics.

