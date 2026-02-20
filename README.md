# Road Accidents Analysis Dashboard (Power BI)

Interactive **Power BI** dashboard analyzing road accident patterns to identify high-risk periods, locations, and contributing factors.  
This project covers the full workflow: **data cleaning (Power Query)** → **data modeling** → **DAX measures** → **dashboard reporting**.

## 📌 Project Objective
Provide a clear view of accident trends and severity to support reporting and help identify where/when accidents are most frequent and which segments show higher risk.

## ✅ Key Features
- Accident trend analysis by time (month/day/hour if available)
- Breakdown by severity (fatal/serious/slight if available)
- Location-based insights (regions/areas/road types if available)
- Interactive filtering and drill-down analysis

## 📊 KPIs & Insights
Typical KPIs included:
- **Total Accidents**
- **Accidents by Severity**
- **Severity Rate (%)**
- **High-risk time periods and locations**
- **Top contributing factors** (weather, lighting, road conditions—if available)

## 🧰 Tools & Skills Used
- **Power BI Desktop**
- **Power Query (M)** for data cleaning and transformation
- **DAX** for KPI measures and analysis
- **Excel / CSV** as the data source
- **Data Modeling** for consistent filtering

## 🗂 Dataset
The original dataset file is not included in this repository because it is too large to upload via GitHub.
To run the dashboard locally, download the dataset separately and update the file path in Power BI:
**Transform data → Data source settings → Change source**.

## 🗂 Files in This Repository
- `dashboard/Road_Accidents_Dashboard.pbix` — Power BI report file  
- `dashboard/screenshots/` — dashboard screenshots  
- `data/` — dataset used (or sample dataset if needed)  
- `docs/` — documentation

## 🖼 Dashboard Screenshots
Example:
![Road Accidents Dashboard](01_overview.jpg)

## ▶️ How to Open and Run
1. Download this repository  
2. Open `dashboard/Road_Accidents_Dashboard.pbix` in **Power BI Desktop**  
3. If Power BI asks for the data source path:
   - Go to **Transform data → Data source settings**
   - Change the source path to your local dataset inside the `data/` folder

## 👤 Author
**John Okoye**  

GitHub: https://github.com/Kennywhite2







