# Corporate Expense Optimization Analyzer

## 🚀 Objective

Large organizations often need to understand how departmental spending varies
across different regions and how spending patterns relate to overall profitability.

This full-stack data analytics project aims to:

- Analyze and visualize departmental spending
- Identify high-spending departments across different states
- Compare spending patterns across R&D, Marketing, and Administration
- Analyze the relationship between corporate spending and company profitability
- Generate actionable insights for corporate cost-control and resource allocation

---

## 🔗 Dataset Used

- Source: Custom synthetic single-company financial dataset created for the project
- Format: Excel (.xlsx)
- Records: 1,080 expense records covering 2025
- Company Scope: Single company
- Departments: R&D, Marketing, Administration
- States: California, Florida, New York
- Fields:
  - `Date`
  - `Department`
  - `State`
  - `Spend`
  - `Company Profit`

The dataset represents expense activity for a single organization across three
departments and multiple states. Company Profit represents the overall company's
profit for the corresponding period and is used to analyze the relationship
between corporate spending and profitability.

---

## 🛠️ Tech Stack & Tools

| Tool | Purpose |
|------|---------|
| Excel | Data cleaning, validation and preparation |
| Power Query | Data transformation and preprocessing |
| MySQL | SQL-based data analysis and aggregation |
| Tableau Public | Interactive dashboards and visual analytics |

---

## 🔄 Project Workflow

### ✅ 1. Data Collection

- Created a single-company financial expense dataset for analysis
- Dataset contains expense records across R&D, Marketing, and Administration
- Includes state-wise spending across California, Florida, and New York
- Contains company-level profit data for studying the relationship between
  spending and profitability
- Covers the complete 2025 period

---

### ✅ 2. Excel Preprocessing

- Imported and reviewed the raw Excel dataset
- Checked for null values and duplicate records
- Standardized department and state names
- Validated numerical fields and date values
- Prepared the dataset for SQL analysis and Tableau visualization

Final columns:

`Date`, `Department`, `State`, `Spend`, `Company Profit`

### ✅ 3. SQL Analysis (MySQL):
 
Imported the cleaned Excel into MySQL as expenses table,
Key SQL queries:
 
<img width="812" height="473" alt="Screenshot 2025-08-06 222139" src="https://github.com/user-attachments/assets/6bb27896-3c11-412e-a6d6-e2a736bb7d32" />

 ###✅ 4. Data Visualization (Tableau Public)
Dashboard Views:

📊 Spend by Department (Bar Chart)

📍 Department-Wise Spend by State (Stacked Bar)

📈 Spend vs Profit (Scatter Plot)

📋 Profit Efficiency Table 

<img width="1237" height="699" alt="Screenshot 2025-08-06 005350" src="https://github.com/user-attachments/assets/97a06212-cfe0-4a17-9108-8d6a43d969f1" />






## KPIs Tracked

| **KPI**                    | **Description**                                                  |
|---------------------------|------------------------------------------------------------------|
| Total Spend               | Total expenditure across all departments                         |
| Total Profit              | Net profit earned per department                                 |
| Profit Efficiency         | Ratio of profit to spend across each state and department        |
| State-Wise Budget Share   | Proportion of overall budget allocated to each state             |

---

## Business Questions Answered

- Which department is overspending the most?
- Is there a strong correlation between spend and profit?
- Which state is allocating the highest budget for R&D?
- Which departments are the most efficient in terms of profit generation?
- Can reallocating the budget improve overall profitability?

---

## Use Cases

- Corporate budget review meetings
- Strategic cost optimization planning
- Departmental performance audits
- Data-driven decision support for C-level executives

---

## Final Outcome

A complete, end-to-end data analytics solution developed using **Excel**, **MySQL**, and **Tableau**. The project provides a centralized, interactive platform to:

- Monitor corporate spending
- Identify inefficiencies
- Evaluate departmental performance
- Support strategic financial decision-making














