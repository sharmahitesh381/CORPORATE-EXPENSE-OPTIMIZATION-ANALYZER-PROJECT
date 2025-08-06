#  Corporate Expense Optimization Analyzer

## 🚀 Objective

Large organizations often struggle with optimizing budgets and tracking departmental efficiency across multiple regions. This full-stack data analytics project aims to:

. Analyze and visualize departmental spending
- Identify budget inefficiencies across states and departments
- Correlate spend with profit to drive actionable cost control decisions

  ## 🔗 Dataset Used
- Source: [Kaggle - 1000 Companies Financial Dataset](https://www.kaggle.com/datasets)  
- Format: Excel (.xlsx)  
- Structure: Department-level spend and profit across different U.S. states


## 🛠️ Tech Stack & Tools

| Tool      | Purpose                            |
|-----------|------------------------------------|
| Excel     | Data wrangling, transformation     |
| Power Query | Data reshaping (wide to long)    |
| MySQL     | Data analysis via SQL queries      |
| Tableau Public | Dashboard and visual analytics |


## 🔄 Project Workflow

### ✅ 1. Data Collection:

- Sourced from Kaggle’s “1000 Companies Financial Dataset”
- Contains spending & profit by department and state

### ✅ 2. Excel Preprocessing:

- Reshaped data using Power Query
- Cleaned null values and removed duplicates
- Final columns: `Department`, `Spend`, `Profit`, `State`

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














