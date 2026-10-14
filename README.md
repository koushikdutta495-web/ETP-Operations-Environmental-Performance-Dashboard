# 🌿 ETP Operations & Environmental Performance Dashboard | Power BI

## 📌 Project Title

**ETP Operations & Environmental Performance Analysis Dashboard**

## 📖 Project Description

This project focuses on developing an interactive **Effluent Treatment Plant (ETP) Operations & Environmental Performance Dashboard** using Microsoft Power BI to analyze operational efficiency, water quality, environmental compliance, resource utilization, maintenance performance, and operating costs.

Using data from the 2025 ETP operations dataset, the project brings together multiple operational areas to provide a centralized view of plant performance. It focuses on monitoring wastewater treatment efficiency, treated-water reuse, water-quality compliance, energy and chemical consumption, sludge management, equipment downtime, and maintenance expenditure.

The dashboard is designed to help management and operational teams compare ETP performance, identify operational inefficiencies, monitor environmental risks, understand cost drivers, and make data-driven decisions.

---

## 🛠️ Tech Stack

- **Power BI Desktop** — Dashboard development and reporting
- **Power Query** — Data cleaning and transformation
- **DAX (Data Analysis Expressions)** — KPI calculations and analytical measures
- **Data Modeling** — Relationships between operational and supporting tables
- **Microsoft Excel** — Data source and initial data preparation
- **Data Visualization** — Interactive charts, KPI cards, trends, and comparisons

---

## 📂 Data Source

- **Dataset:** ETP_City_2025_4Zone_365Days
- **File Format:** Microsoft Excel (.xlsx)
- **Data Period:** 2025
- **Business Domain:** Environmental Analytics / Wastewater Treatment Operations

### Data Tables

The project requirements cover the following data tables:

1. **ETP_Master** — ETP details, zones, wards, capacity, technology, and operational status.
2. **Daily_Operations** — Inlet flow, treated flow, reused water, discharge, operating hours, and downtime.
3. **Water_Quality** — pH, BOD, COD, TSS, TDS, Ammonia, and DO measurements.
4. **Chemical_Consumption** — Chemical usage, quantities, and expenditure.
5. **Energy_Consumption** — Electricity consumption, demand, and energy cost.
6. **Sludge_Management** — Sludge generation, disposal, disposal methods, and costs.
7. **Maintenance** — Equipment problems, maintenance events, downtime, costs, and status.
8. **Calendar** — Date, year, month, quarter, and day attributes.
9. **Parameter_Targets** — Target ranges for water-quality parameters.

---

# 🚀 Dashboard Highlights

## 📌 Business Problem

Effluent Treatment Plants generate operational, environmental, financial, and maintenance data across multiple sources. Analyzing these datasets separately makes it difficult to evaluate plant efficiency, detect water-quality issues, monitor downtime, and understand operating expenditure.

Management needs a centralized reporting solution to answer important questions:

- Which ETPs perform most efficiently?
- How effectively is wastewater being treated?
- How much treated water is being reused?
- Which water-quality parameters fail to meet their defined targets?
- Which zones or plants experience higher downtime?
- Where are chemical, energy, sludge, and maintenance costs concentrated?
- Which equipment problems require management attention?

This project aims to bring these performance indicators together in an interactive Power BI reporting environment.

---

## 🎯 Goal of the Dashboard

The primary goal is to transform raw ETP operational data into actionable business insights.

The dashboard aims to:

- Monitor operational efficiency and plant availability.
- Compare inlet flow, treated flow, reuse, and discharge.
- Track environmental compliance against defined parameter targets.
- Identify water-quality performance gaps.
- Analyze chemical, energy, sludge, and maintenance expenditure.
- Evaluate equipment reliability and downtime.
- Compare ETPs across different zones.
- Monitor daily and monthly performance trends.
- Identify opportunities for cost optimization and operational improvement.

---

# 📊 Key Performance Indicators (KPIs)

## 1. Operational KPIs

### Total Inlet Flow
Measures the total volume of wastewater received by the ETPs.

### Total Treated Flow
Measures the total volume of wastewater treated.

### Treatment Efficiency (%)
Measures treated flow as a percentage of inlet flow.

**Formula:** Treated Flow ÷ Inlet Flow × 100

### Water Reuse Rate (%)
Measures the proportion of treated water reused.

**Formula:** Reused Water ÷ Treated Water × 100

### Plant Availability (%)
Measures the proportion of total recorded operating and downtime hours spent operating.

**Formula:** Operating Hours ÷ (Operating Hours + Downtime Hours) × 100

### Total Downtime
Measures the total recorded plant downtime in hours.

### Capacity Utilization (%)
Compares inlet flow against designed treatment capacity.

**Formula:** Inlet Flow ÷ Designed Capacity × 100

---

## 2. Environmental KPIs

- Overall Compliance (%)
- pH Compliance (%)
- BOD Compliance (%)
- COD Compliance (%)
- TSS Compliance (%)
- TDS Compliance (%)
- Ammonia Compliance (%)
- Dissolved Oxygen (DO) Performance

These indicators help evaluate water-quality performance against the targets defined in the dataset.

---

## 3. Financial KPIs

- Total Chemical Cost
- Total Energy Cost
- Total Sludge Disposal Cost
- Total Maintenance Cost
- Total Operating Cost
- Cost per KL Treated

**Total Operating Cost:**

Chemical Cost + Energy Cost + Sludge Cost + Maintenance Cost

**Cost per KL Treated:**

Total Operating Cost ÷ Total Treated Flow

---

# 📈 Walkthrough of Key Visuals

## 1️⃣ Executive Overview

Provides a high-level summary of ETP operational, environmental, and financial performance.

**Key metrics:**
- Total Inlet Flow
- Total Treated Flow
- Treatment Efficiency
- Water Reuse Rate
- Plant Availability
- Total Downtime
- Overall Compliance
- Total Operating Cost
- Cost per KL Treated

**Business purpose:** Help management quickly understand overall performance and identify areas requiring further investigation.

## 2️⃣ Operational Performance Analysis

Analyzes wastewater flow, treatment efficiency, capacity utilization, operating hours, and downtime across ETPs and zones.

**Key visualizations:**
- Monthly Inlet vs. Treated Flow
- ETP-wise Performance Comparison
- Capacity Utilization Analysis
- Water Reuse vs. Discharge
- Monthly Downtime Trend
- ETP Performance Ranking

**Business purpose:** Identify differences in operational performance and highlight plants that may require efficiency improvements.

## 3️⃣ Water Quality & Environmental Compliance

Evaluates water-quality parameters against their defined target ranges.

**Key visualizations:**
- Parameter Compliance Analysis
- Inlet vs. Outlet Water Quality
- Monthly Water-Quality Trends
- Parameter Target vs. Actual
- ETP-wise Compliance Comparison
- Non-Compliance Analysis

**Business purpose:** Identify parameters and plants requiring closer monitoring or corrective action.

## 4️⃣ Cost & Resource Efficiency

Examines operating expenditure and resource consumption across different cost categories.

**Key visualizations:**
- Operating Cost Breakdown
- Monthly Operating Cost Trend
- Chemical Consumption Analysis
- Chemical Cost by Type
- Energy Cost Analysis
- Sludge Disposal Cost
- Maintenance Cost by ETP
- Cost per KL Treated

**Business purpose:** Identify major expenditure categories and potential opportunities for cost optimization.

## 5️⃣ Maintenance & Reliability

Analyzes maintenance activities, equipment problems, downtime, and maintenance expenditure.

**Key visualizations:**
- Downtime by Equipment
- Maintenance Cost by Equipment
- Problems by Frequency
- Maintenance Events by ETP
- Monthly Maintenance Trend
- Maintenance Status Analysis

**Business purpose:** Identify recurring equipment issues and understand their contribution to operational disruption.

## 6️⃣ ETP-Level Deep Dive

Provides a detailed view of a selected treatment plant using operational, environmental, financial, and maintenance indicators.

**Analysis areas:**
- ETP Profile and Designed Capacity
- Inlet, Treated, Reused, and Discharge Flow
- Treatment Efficiency and Availability
- Water-Quality Parameters
- Compliance Performance
- Chemical, Energy, Sludge, and Maintenance Costs
- Equipment Problems and Downtime

**Business purpose:** Support detailed plant-level performance investigation and comparisons.

*Note: The page descriptions above reflect the project requirements. Retain only the pages and visuals implemented in the final Power BI report.*

---

# 🎛️ Filters & Interactivity

The project requirements include interactive filtering by:

- Year
- Quarter
- Month
- Zone
- ETP
- Technology
- Sample Point
- Chemical
- Equipment
- Maintenance Status

These filters are intended to help users compare plant performance across different time periods, operational zones, and analysis categories.

---

# 💡 Business Insights

The dashboard is designed to help stakeholders identify:

- ETPs with higher or lower treatment efficiency.
- Plants operating above or below their designed capacity.
- Changes in water reuse and discharge patterns.
- Water-quality parameters with higher non-compliance.
- Zones experiencing higher downtime.
- Chemicals contributing significantly to expenditure.
- Equipment associated with recurring failures.
- Monthly changes in operating costs and plant performance.
- Differences in cost per KL treated across ETPs.

**Note:** These are intended analytical outcomes. Specific findings and rankings should be added after validating the actual dashboard results.

---

# 📈 Business Impact

The dashboard can support better operational and management decisions by helping teams:

- Monitor ETP performance from a centralized reporting interface.
- Identify plants requiring operational attention.
- Improve visibility into environmental compliance.
- Track downtime and maintenance performance.
- Understand major operating cost drivers.
- Evaluate resource utilization and treated-water reuse.
- Compare performance across zones and individual plants.
- Identify potential cost-saving opportunities.
- Support more informed environmental and operational decisions.

The dashboard supports decision-making; actual improvements depend on operational follow-up and corrective actions.

---

# 🧠 Skills Demonstrated

- Data Cleaning & Quality Checks
- Data Transformation
- Power Query
- Data Modeling
- DAX Measure Development
- KPI Design
- Environmental Data Analysis
- Operational Performance Analysis
- Water-Quality Compliance Analysis
- Cost Analysis
- Maintenance & Downtime Analysis
- Interactive Dashboard Development
- Business Intelligence
- Data Visualization
- Business Requirement Analysis
- Data Storytelling

---

# 🔄 Project Workflow

1. Requirement Gathering and Business Understanding
2. Data Walkthrough
3. Data Connection
4. Data Cleaning and Quality Checks
5. Data Modeling
6. Data Processing
7. DAX Calculations
8. KPI Development
9. Dashboard Layout and Design
10. Chart Development and Formatting
11. Report Development
12. Insights Generation

---

# 📸 Dashboard Preview

### Executive Overview
![ETP Executive Overview](https://github.com/koushikdutta495-web/ETP-Operations-Environmental-Performance-Dashboard/blob/main/ETP%20Project%20Overview.png
)

### Operational Performance
![ETP Operational Performance](https://github.com/koushikdutta495-web/ETP-Operations-Environmental-Performance-Dashboard/blob/main/ETP%20Project.png
)

### Water Quality & Compliance
![ETP Water Quality and Compliance](https://github.com/koushikdutta495-web/ETP-Operations-Environmental-Performance-Dashboard/blob/main/ETP%20Project.png
)

### Cost & Resource Efficiency
![ETP Cost Analysis](https://github.com/koushikdutta495-web/ETP-Operations-Environmental-Performance-Dashboard/blob/main/ETP.png)



# ⭐ Project Outcome

This project demonstrates how Microsoft Power BI can be used to organize complex ETP operational data into a structured business intelligence solution.

By combining operational KPIs, environmental compliance indicators, resource consumption, financial analysis, and maintenance metrics, the dashboard aims to support a more comprehensive understanding of treatment plant performance.

**The ultimate objective is to support efficient wastewater treatment operations, better environmental monitoring, improved cost visibility, and data-driven management decisions.**
