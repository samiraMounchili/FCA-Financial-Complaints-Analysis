# FCA Financial Complaints Analysis

## Project Overview

This project analyses firm-level financial complaints data published by the Financial Conduct Authority (FCA).

The aim was to explore complaint volumes across financial products and firms, compare complaints opened and closed, and examine complaint uphold rates.

The analysis was completed using Excel, MySQL and Power BI.

---

## Tools Used

- Excel
- MySQL
- Power BI

---

## Data Source

Financial Conduct Authority (FCA), Firm-level complaints data, 2025 H2.

The dataset includes complaint information across financial firms and product categories such as:

- Banking & Credit Cards
- Decumulation & Pensions
- Home Finance
- Insurance & Pure Protection
- Investments

---

## Project Workflow

### 1. Excel Analysis

Excel was used for the initial review and exploration of the dataset.

Tasks included:

- Reviewing the structure of the data
- Checking complaint volumes by product
- Comparing firms
- Identifying key complaint categories
- Reviewing complaint uphold percentages

### 2. SQL Analysis

The analysis was recreated and expanded in MySQL.

SQL was used to:

- Clean and convert complaint values into numeric formats
- Create clean views for opened, closed and upheld complaints
- Calculate total complaints by product
- Identify the top firms by complaint volume
- Compare opened and closed complaints
- Calculate complaint shares by product
- Analyse complaint uphold rates
- Compare high-volume firms by uphold rate

### 3. Power BI Dashboard

Power BI was used to create a one-page dashboard summarising the key findings from the analysis.

The dashboard includes:

- Total number of firms
- Total complaints opened
- Total complaints closed
- Opened complaints by product
- Closed complaints by product
- Top 10 firms by opened complaints
- Top 10 firms by closed complaints
- Opened vs closed complaints by firm
- Average uphold rate by product
- Banking uphold rates for firms with 10,000+ complaints
- Insurance uphold rates for firms with 10,000+ complaints

---

## Key Findings

- The dataset included 219 financial firms.
- Approximately 1.65 million complaints were opened.
- Approximately 1.63 million complaints were closed.
- Banking & Credit Cards recorded the highest number of opened complaints, at approximately 845,000.
- Insurance & Pure Protection recorded approximately 621,000 opened complaints and was the second-largest category.
- NatWest, Lloyds, Barclays and HSBC were among the firms with the highest complaint volumes.
- Complaint uphold rates varied considerably across both products and firms.
- Among firms with more than 10,000 Banking & Credit Card complaints, uphold rates differed significantly.
- High-volume Insurance firms also showed substantial differences in uphold rates.
- Opened and closed complaint volumes were broadly similar overall, although individual firms showed differences between the two.

---

## Power BI Dashboard

The dashboard provides a visual summary of complaint volumes, firm-level performance and complaint outcomes.

![FCA Financial Complaints Power BI Dashboard](fca_complaints_powerbi_dashboard.png)

---

## Skills Demonstrated

- Data cleaning
- Data validation
- SQL querying
- Aggregation
- Filtering
- CASE statements
- Views
- Joins
- Data transformation
- KPI analysis
- Financial services data analysis
- Power BI dashboard development
- Data visualisation
- Business insight generation

---

## Repository Contents

- `FCA_Financial_Complaints_SQL_Analysis.sql`
- `fca_complaints_powerbi_dashboard.png`
- `README.md`

---

## Future Development

Possible extensions to this project include:

- Comparing multiple FCA reporting periods to identify longer-term trends
- Analysing changes in complaint volumes over time
- Exploring additional complaint outcome measures
- Applying further statistical analysis to complaint patterns
- Comparing complaint behaviour across different financial product categories
