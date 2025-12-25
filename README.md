# 📊 Company P&L Dashboard | Power BI

## 📌 Project Overview
This project is an interactive **Company Profit & Loss (P&L) Dashboard** developed using **Microsoft Power BI**, designed to provide a comprehensive financial overview across months, countries, and lines of business (LOBs).

The dashboard enables stakeholders to:
- Compare Actuals vs Budget
- Analyze P&L variance
- Track revenue performance
- Review all-month financial snapshots in a structured MIS-style format

> ⚠️ **Data Disclaimer:**  
> The dataset used in this project is **synthetic and AI-generated** (fetched using ChatGPT and other AI sources).  
> Hence, numerical values may appear unrealistic.  
> However, the **data modeling approach, DAX logic, report structure, navigation, and analytical views** reflect real-world corporate finance dashboards.

---

## 🧭 Dashboard Navigation & Pages
The report is structured into **four major analytical views**, accessible via interactive navigation buttons:

1. **Global View**  
2. **P&L Variance**  
3. **Revenue vs Budget**  
4. **All Months Snapshot**  

---

### 🌍 1. Global View
**Purpose:** High-level financial performance monitoring  

**Key Features:**
- Year Selector (e.g., 2025)  
- Month-wise toggle buttons (January–October)  
- KPI Cards:
  - Actuals
  - Budget
  - Previous Month
- Actual vs Budget column chart by Month  

**Business Value:**
- Quick comparison between actual performance and planned budget  
- Identify strong and weak months at a glance  

---

### 📉 2. P&L Variance
**Purpose:** Detailed variance analysis across P&L heads  

**Key Features:**
- Month-wise selection  
- Country filter  
- LOB (Line of Business) filter  
- Tabular breakdown of major P&L Heads:
  - Revenue, COGS, Operating Expenses, Travel, EBITDA, IT Infrastructure, FTE Payroll, Net Profit, Training, Marketing, Tax, Consulting, Gross Margin, Depreciation  
- Variance over Budget with conditional formatting:
  - Green → Favorable variance  
  - Red → Unfavorable variance  

**Business Value:**
- Pinpoints cost overruns and revenue shortfalls  
- Supports finance reviews and variance explanations  
- Useful for monthly MIS and management reporting  

---

### 💰 3. Revenue vs Budget
**Purpose:** Performance comparison across geography and business lines  

**Key Features:**
- Year & Month selection  
- Operating Center (Country) wise Actual vs Budget:
  - Australia, United States, China, United Kingdom, India, Germany  
- LOB-wise Actual vs Budget:
  - Manufacturing, Finance, Technology, Automotive, Logistics, Telecom, Retail, Healthcare  

**Business Value:**
- Identify high-performing and underperforming regions  
- Compare business unit contribution to revenue  
- Assist leadership in resource allocation decisions  

---

### 📅 4. All Months Snapshot
**Purpose:** Complete financial overview in a single table  

**Key Features:**
- Year filter  
- Country and LOB slicers  
- Month-wise P&L matrix (January to October) with auto-calculated Total column  
- Covers all major P&L heads  
- MIS-style presentation suitable for finance audits and reviews  

**Business Value:**
- One-stop financial summary  
- Simplifies trend analysis across months  
- Reduces dependency on manual Excel-based reports  

---

## 🧠 DAX Measures & Logic
Key measures implemented using **DAX** include:
- Actual Revenue  
- Budget Revenue  
- Previous Month Revenue  
- Variance over Budget  
- Net Profit  
- EBITDA  
- Gross Margin  
- Month-over-Month comparisons  
- Total aggregations across months  

Focus was placed on **accurate calculations, reusability, and performance optimization**.

---

## 🛠 Tools & Technologies
- Microsoft Power BI  
- Power Query (ETL & data transformation)  
- DAX (Data Analysis Expressions)  
- AI-generated sample financial data  

---

## 🧩 Data Modeling Approach
- Cleaned and structured fact data  
- Dimension tables for:
  - Date  
  - Country  
  - Line of Business  
- Relationships designed to support:
  - Time intelligence  
  - Cross-filtering across pages  
- Optimized for **interactive slicing and drill-down analysis**

---

## 🚀 Key Learnings & Outcomes
- Built a **real-world corporate finance dashboard structure**  
- Strengthened **DAX and Power BI modeling skills**  
- Designed **executive-friendly visuals**  
- Implemented **end-to-end reporting workflow** from data prep to insights  

---

## 📎 Use Cases
- Financial MIS Reporting  
- Monthly Performance Reviews  
- Budget vs Actual Analysis  
- P&L Variance Explanation  
- Management & Leadership Dashboards  

---

## 👤 Author
**Bharat Sharma**  
Data Analyst | Aspiring Data Scientist  
**Skills:** Power BI, DAX, SQL, Python, Data Analytics, Data Visualization
