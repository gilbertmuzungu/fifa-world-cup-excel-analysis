# fifa-world-cup-excel-analysis
An Excel-based data analysis project exploring FIFA World Cup match data (1930–2022) using PivotTables, calculated fields, and interactive dashboards to uncover key performance insights.
# 🌍 FIFA World Cup Data Analysis (1930–2022)

An Excel-based analytical project exploring FIFA World Cup match data through structured cleaning, pivot table-driven analysis, and a fully interactive dashboard.

---

## ✅ Project Workflow Summary

### 📂 1. Data Cleaning & Preparation

The raw match data was transformed into an analysis-ready format using the following key steps:

#### 🔹 Column Reduction
Removed unnecessary technical columns such as:
- Match IDs
- Team and stadium IDs
- Redundant win flags and score margins
- Unused penalty detail fields

#### 🔹 Duplicate Removal
- Removed duplicate match records to ensure integrity and accuracy.

#### 🔹 Data Formatting
- Standardized the `Match Date` column to a consistent date format.
- Renamed inconsistent or unclear columns (e.g., changed `Country Name` to `Host Country Name`).

#### 🔹 Data Type Correction
- Ensured all score columns were numeric.
- Confirmed all date fields were formatted as proper date types.

#### 🔹 Missing Value Detection
- Used filters to review and resolve blank or missing data fields.

#### 🔹 Fixed Inconsistencies
- Standardized team name variants (e.g., “West Germany” → “Germany”).
- Unified stage names and tournament labels.

#### 🔹 Derived Columns Created
- **Total Goals**: `Home Team Score + Away Team Score`
- **Winning Team**: Created using a nested `IF` formula comparing scores

---

### 📊 2. Data Analysis with Pivot Tables

Four problem-solving pivot tables were created to answer key analytical questions:

#### 🔸 Pivot 1 – Match Wins by Team
**Problem:** Which teams have the most match wins?  
- **Rows:** Winning Team  
- **Values:** Count of Wins

#### 🔸 Pivot 2 – Goals by Stage
**Problem:** Where are the most goals scored?  
- **Rows:** Stage Name  
- **Values:** Sum of Total Goals  

#### 🔸 Pivot 3 – Host Nation Performance
**Problem:** Do hosts perform better?  
- **Rows:** Host Country Name  
- **Values:** Count of Wins, Sum of Total Goals  

#### 🔸 Pivot 4 – Penalty Shootouts by Stage
**Problem:** Are penalty shootouts more common in certain stages?  
- **Rows:** Stage Name  
- **Values:** Count of Penalty Shootouts  

---

### 📈 3. Dashboard Creation

A single dashboard was created combining all four pivot charts.

#### 🧩 Features:
- Interactive **slicers** for dynamic filtering:
  - `Tournament`
  - `Host Country Name`

- All slicers are connected via **Report Connections** to update pivot charts simultaneously.
- Clean and labeled chart titles, axes, and data labels for presentation.

---

## 🧠 Final Result

- ✅ Interactive Excel dashboard answering key questions about the FIFA World Cup
- ✅ Professionally structured data model
- ✅ Insightful visualizations around team performance, stage dynamics, hosting impact, and penalty shootouts
- ✅ Ready for portfolio, GitHub, or stakeholder presentation

---

## 🛠️ Tools Used

- Microsoft Excel (PivotTables, Charts, Slicers)
- Excel Functions (`IF`, `SUM`, etc.)
- GitHub for publishing and version control

---

## 📁 Files Included

- `FIFA_World_Cup_Analysis.xlsx` — cleaned dataset, pivot tables, and dashboard

---

## 👤 Author

> Gilbert Karani Muzungu

---

## 📬 Feedback or Questions?

Feel free to open an issue or reach out with suggestions and improvements.

