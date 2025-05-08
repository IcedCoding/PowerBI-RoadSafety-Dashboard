# 🚦 Road Safety Dashboard (2007–2018)

A Power BI dashboard created for the **U.S. National Highway Traffic Safety Administration (NHTSA)** to visualize road safety improvements across U.S. states over the period **2007 to 2018**.

## 📊 Objective

This dashboard highlights how each state is performing in terms of **road fatalities per 100,000,000 miles driven**, compared to the NHTSA’s safety target of **1.02 fatalities**. It provides interactive visual analysis by year and state.

---

## 📁 Data Source

- **Workbook**: `PowerBIData`
- **Sheet**: `PA - Driving Safety`
- **Data Includes**:
  - State
  - Year
  - Miles Traveled
  - Actual Fatalities
  - Fatalities per 100M Miles
  - Fatality Target (1.02)
  - Actual 2018 Fatality Rate

---

## 📈 Dashboard Features

### **Main Page (Interactive Overview)**
- **State Slicer**: Single select dropdown to choose a state
- **Selected State Card**: Displays the selected state
- **Gauge**: 
  - Visualizes 2018 fatality rate for selected state
  - Ranges from `0` to `2.5`
  - Target set to `1.02`
  - **Conditional colors**:
    - Blue ≤ 0.8 (Good)
    - Yellow = 1.02 (Target)
    - Red ≥ 2.5 (Poor)
- **Map**:
  - Highlights the selected state
  - Filled with the same color as the gauge
- **KPI Visual**:
  - Indicator: Fatalities
  - Trend Axis: Year
  - Target Goal: Avg. Target Fatalities
  - Settings: `Decreasing is positive`, `Low is good`
- **Cards**:
  - Total Miles Driven
  - Number of Fatalities

---

## 📊 Additional Pages (Detailed Analysis)

### **Page 1: Fatalities Over Time**
- **Bar Chart**: Shows fatalities year-over-year
- **Conditional Formatting**: Color varies based on values
- **Drillthrough Enabled** (by State)

### **Page 2: Miles Driven Over Time**
- **Bar Chart**: Visualizes total miles traveled each year
- **Drillthrough Enabled**

### **Page 3: Fatality Rate vs Target**
- **Combo Chart**: 
  - Bars: Actual fatality rate per year
  - Line: Constant value (1.02 target)
- **Target Line Column**: `Target1.02 = 1.02`
- **Drillthrough Enabled**

🔁 **Back Button Included** on drillthrough pages

---

## 🛠 Tools & Skills Used

- Power BI Desktop
- Power Query Editor
- DAX Calculated Columns (e.g., `Target1.02`)
- KPI & Gauge Visuals
- Conditional Formatting
- Drillthrough Navigation
- Map & Geographic Visuals

---

## 📌 Project Purpose

Designed as a **practice activity** to demonstrate:
- Power BI dashboard creation
- Data storytelling
- Conditional visuals
- KPI tracking
- Drillthrough and navigation

---

## 📂 File

- `RoadSafetyDashboard.pbix` – Full Power BI report

---

## 📬 Contact

For any questions or feedback, feel free to open an issue or reach out.

