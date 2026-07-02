# 📊 Employee Performance Dashboard | Power BI Business Intelligence Project

# 📌 Project Overview

This project showcases an **interactive Employee Performance Dashboard** developed using **Microsoft Power BI**. The dashboard transforms raw employee work logs into actionable business insights, enabling managers and stakeholders to monitor workforce productivity, billable utilization, client coverage, and operational performance.

The dashboard provides an intuitive interface with KPI cards, slicers, charts, and DAX-powered calculations for effective decision-making.

---

# 🎯 Project Objectives

- Analyze employee productivity
- Monitor billable and non-billable hours
- Track client assignments and client coverage
- Compare employee and location performance
- Create interactive filters for dynamic analysis
- Build reusable DAX measures
- Design an executive-level Business Intelligence dashboard

---

# 📊 Dataset Information

| Feature | Details |
|----------|----------|
| Dataset | Employee Work Log |
| Total Records | 7,999 |
| Employees | 10 |
| Locations | 4 |
| Date Range | Jan 1, 2020 – Apr 9, 2020 |
| Total Hours | 31,823 Hours |
| Billable Hours | 15,712 Hours |
| Client Records | 23,915 Assigned |

---

# 🛠️ Tools & Technologies

- Microsoft Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- CSV Dataset
- Data Visualization
- Business Intelligence

---

# 📂 Repository Structure

```
Employee-Performance-Dashboard/
│
├── Employee_data.csv
├── Employee_Performance.pbix
├── Employee_Dashboard.pdf
├── README.md
├── dashboard_screenshot.png
└── images/
    ├── dashboard_overview.png
    ├── employee_performance.png
    ├── location_analysis.png
    ├── utilization_chart.png
    └── client_coverage.png
```

---

# 📈 Dashboard Features

### 📌 KPI Cards

- Total Hours Worked
- Billable Hours
- Billable Utilization %
- Clients Assigned
- Clients Seen
- Client Coverage %

---

### 📊 Interactive Visualizations

- Employee Performance Comparison
- Billable vs Non-Billable Hours
- Daily Productivity Trend
- Location-wise Performance
- Client Coverage Analysis
- Employee KPI Matrix

---

### 🎛️ Interactive Filters

- Employee Name
- Office Location
- Date Range

---

# 📐 DAX Measures Created

### Billable Utilization

```DAX
Billable Utilization % =
DIVIDE(
    SUM(Employee_data[Billable Hours]),
    SUM(Employee_data[Total Hours]),
    0
) * 100
```

### Client Coverage

```DAX
Client Coverage % =
DIVIDE(
    SUM(Employee_data[Clients Seen]),
    SUM(Employee_data[Clients Assigned]),
    0
) * 100
```

### Non-Billable Hours

```DAX
Non-Billable Hours =
SUM(Employee_data[Total Hours]) -
SUM(Employee_data[Billable Hours])
```

---

# 📊 Dashboard Insights

- 📈 Total Hours Worked: **31,823**
- 💼 Billable Hours: **15,712**
- 📊 Billable Utilization: **49.4%**
- 👥 Total Clients Assigned: **23,915**
- ✅ Clients Seen: **16,028**
- 📍 Client Coverage: **67%**
- 🏢 Four office locations were analyzed.
- 👨‍💼 Employee productivity remains consistent across locations.

---

# 🔍 Key Business Insights

- Nearly **half of all working hours are billable**.
- Client coverage is approximately **67%**, indicating opportunities for operational improvement.
- Employee performance is relatively balanced across the organization.
- Location C records the highest billable utilization.
- Location B shows comparatively lower productivity.
- KPI cards allow managers to monitor performance instantly.

---

# 🧹 Data Preparation

The dataset was prepared using **Power Query** by:

- Removing unnecessary columns
- Formatting date fields
- Correcting data types
- Cleaning employee names
- Preparing the model for DAX calculations

---

# 💼 Business Use Cases

This dashboard can be used by:

- HR Department
- Operations Managers
- Project Managers
- Finance Teams
- Executive Leadership

---

# 📚 Skills Demonstrated

- Power BI Dashboard Design
- Business Intelligence
- Data Visualization
- KPI Development
- Power Query
- DAX Measures
- Data Modeling
- Interactive Reporting
- Dashboard Storytelling

---

# 🚀 Future Enhancements

- Employee Performance Forecasting
- Revenue Dashboard
- Drill-through Employee Profiles
- Conditional KPI Formatting
- Mobile Dashboard Layout
- Automated Data Refresh
- Department-wise Analysis

---

# ▶️ How to Use

1. Download the repository

```bash
git clone https://github.com/your-username/employee-performance-dashboard.git
```

2. Open

```
Employee_Performance.pbix
```

using **Microsoft Power BI Desktop**.

3. Interact with:

- Employee slicers
- Date filters
- Location filters
- KPI cards
- Charts

---

# 📸 Dashboard Preview

Add screenshots inside the **images** folder.

```
images/
├── dashboard_overview.png
├── employee_performance.png
├── utilization_chart.png
├── location_analysis.png
└── client_coverage.png
```

---

# 👨‍💻 Author

**Prince Maheta**

📊 Aspiring Data Analyst | Business Intelligence Developer

🔗 **GitHub:** https://github.com/princemaheta2627-glitch

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 📜 License

This project is intended for learning, portfolio, and educational purposes.
