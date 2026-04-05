# 📊 Insurance Analytics Dashboard

An end-to-end data analytics project that integrates multi-source insurance business data, performs in-depth analysis using **SQL & Excel**, and delivers interactive dashboards in **Tableau** and **Power BI** to track KPIs across key business streams.

---

## 📌 Project Highlights

| Feature | Detail |
|---|---|
| Data Sources | Invoice, Brokerage, Meetings, Opportunities |
| Tools Used | SQL, Excel, Tableau, Power BI |
| Business Streams | New Business, Cross-Sell, Renewal |
| Key Finding | Renewal at 150% of target; New Business gap flagged |
| Output | Interactive KPI Dashboards for management reporting |

---

## 🎯 Project Objective

To build a unified analytics solution for an insurance business that:
- Consolidates data from multiple sources into a single analysis-ready format
- Tracks performance KPIs across **New Business**, **Cross-Sell**, and **Renewal** streams
- Delivers actionable insights to support strategic decision-making

---

## 🗂️ Project Structure

```
insurance-analytics-dashboard/
│
├── data/
│   ├── raw/                    # Raw source files (invoice, brokerage, etc.)
│   └── cleaned/                # Cleaned & processed data
│
├── sql/
│   ├── data_cleaning.sql       # Missing value treatment, deduplication
│   ├── kpi_queries.sql         # KPI calculations per business stream
│   └── data_integration.sql    # Joining multi-source tables
│
├── excel/
│   └── insurance_analysis.xlsx # Pivot tables, VLOOKUP, summary sheets
│
├── dashboards/
│   ├── insurance_dashboard.twbx   # Tableau workbook
│   └── insurance_dashboard.pbix   # Power BI file
│
├── screenshots/
│   ├── tableau_dashboard.png
│   └── powerbi_dashboard.png
│
└── README.md
```

---

## 📂 Data Sources Used

| Source | Description |
|---|---|
| **Invoice Data** | Premium amounts, policy numbers, payment status |
| **Brokerage Data** | Broker details, commission, channel performance |
| **Meetings Data** | Client meetings, follow-ups, conversion rates |
| **Opportunities Data** | Leads, pipeline stages, win/loss status |

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **SQL / MySQL** | Data extraction, cleaning, joining, KPI queries |
| **Microsoft Excel** | Pivot tables, VLOOKUP/XLOOKUP, data wrangling |
| **Tableau** | Interactive visual dashboards |
| **Power BI** | KPI tracking, management reporting dashboards |

---

## 🔄 Project Workflow

```
Raw Data (Multi-source)
        ↓
Data Cleaning & Integration (SQL + Excel)
  • Removed duplicates
  • Handled missing values
  • Standardized formats
  • Merged invoice, brokerage, meetings & opportunities tables
        ↓
Exploratory Data Analysis
  • Identified trends across business streams
  • Calculated KPIs: hit rate, conversion %, premium growth
        ↓
Dashboard Development
  • Tableau → Visual storytelling & trend analysis
  • Power BI → KPI cards, slicers, management view
        ↓
Insights & Recommendations
```

---

## 📊 KPIs Tracked

| KPI | Business Stream |
|---|---|
| Premium Target vs Actual | New Business, Renewal, Cross-Sell |
| Conversion Rate | New Business |
| Renewal Retention Rate | Renewal |
| Cross-Sell Hit Rate | Cross-Sell |
| Broker Performance | All Streams |
| Meeting-to-Close Ratio | New Business |

---

## 💡 Key Insights

- ✅ **Renewal stream** performing at **150% of target** — strong client retention
- ⚠️ **New Business stream** showing a significant gap vs target — flagged for strategic review
- 📈 **Cross-Sell** opportunities identified in mid-tier broker segment
- 🤝 Top 3 brokers contributing to 60%+ of total premium volume

---

## 📸 Dashboard Screenshots

### Tableau Dashboard
![Tableau Dashboard](screenshots/tableau_dashboard.png)

### Power BI Dashboard
![Power BI Dashboard](screenshots/powerbi_dashboard.png)

> *Add your actual dashboard screenshots to the `screenshots/` folder*

---

## 🚀 How to Use

### SQL Queries
1. Import raw data into MySQL or SQL Server
2. Run `sql/data_cleaning.sql` first
3. Run `sql/data_integration.sql` to merge sources
4. Run `sql/kpi_queries.sql` to generate KPI outputs

### Excel
- Open `excel/insurance_analysis.xlsx`
- Navigate through sheets: Raw → Cleaned → Pivot Summary → KPI View

### Tableau
- Open `dashboards/insurance_dashboard.twbx` in Tableau Desktop/Public
- Interact with filters: Stream, Date Range, Broker, Region

### Power BI
- Open `dashboards/insurance_dashboard.pbix` in Power BI Desktop
- Use slicers to filter by business stream and time period

---

## 📚 Skills Demonstrated

- ✅ Data Cleaning & Wrangling (SQL + Excel)
- ✅ Multi-source Data Integration
- ✅ KPI Development & Business Metrics
- ✅ Dashboard Design (Tableau + Power BI)
- ✅ Insight Generation & Business Reporting
- ✅ Analytical Thinking & Storytelling with Data

---

## 👩‍💻 Author

**Nishita Thakur**
Entry-Level Data Analyst | SQL | Power BI | Tableau | Excel
[LinkedIn](https://www.linkedin.com/in/nishitathakur-/) · [GitHub](https://github.com/YOUR_USERNAME)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
