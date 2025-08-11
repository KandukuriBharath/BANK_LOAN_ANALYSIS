# Bank Loan Analysis Dashboard (Power BI & SQL)

📊 **Dashboard Link**:  
[Click here to view the dashboard](https://app.powerbi.com/links/YOUR-DASHBOARD-LINK)

Project Overview :
This dashboard helps banks analyze loan borrower profiles, assess loan performance, and identify key risk factors. It provides actionable insights into loan approvals, repayments, default risks, and customer financial behavior to optimize decision-making.

Steps followed :
Data Collection & Import
Imported loan data into MS SQL Server for cleaning and analysis. Data Cleaning & Preparation (SQL)
Removed duplicates, handled null values, and standardized loan status.
Formatted dates and classified loans into Good & Bad categories. Data Analysis & Querying (SQL)
Extracted key metrics: Total Loans, Funded Amount, Interest Rate, DTI.
Analyzed monthly, quarterly, and yearly trends. Data Modeling & Transformation (Power BI)
Connected Power BI to SQL Server and created relationships.
Used Power Query for data transformation. Dashboard Development (Power BI & DAX)
Built interactive visualizations for loan trends, borrower risk, and regional insights.
Used DAX formulas for KPIs like MoM & MTD changes.


Report Snapshot (Power BI DESKTOP)

<img width="1047" height="590" alt="Report-1" src="https://github.com/user-attachments/assets/89a82438-e1d0-4b5f-8519-08539ee89e8e" />


<img width="1038" height="593" alt="Report-2" src="https://github.com/user-attachments/assets/6d7a91cb-00c1-47c2-98e6-75776c43ae91" />


<img width="1041" height="583" alt="Report-3" src="https://github.com/user-attachments/assets/df59dc5c-43e2-4759-9542-e904466a15e0" />



Key Insights & Findings
Loan Approvals & Funding:
Total Applications: 38,000+ processed.

Total Funded Amount: $435M+ disbursed.

MoM Growth: 7% increase in new loan applications.

Good vs. Bad Loans:
Good Loans: 87% repayment success rate.

Bad Loans: 13% default risk, with $50M at risk.

Interest Rate Analysis: Avg. 12.5%, fluctuating 1.2% MoM.

Customer & Risk Analysis:
Homeownership Impact: 65% of borrowers own homes, leading to 20% lower default rates.

Employment Factor: Borrowers with >5 years of employment had 30% lower default risk.

Regional & Trend Analysis:
Highest Loan Activity: California, Texas, and New York.

Seasonal Trend: Loan applications peak in Q2 (+15%) due to tax refunds.

Debt-to-Income Ratio (DTI): Avg. 13%, higher DTI correlates with 10%+ default risk.

Technology Stack
Database:MS SQL Server (Data Cleaning, Querying, Analysis)

Visualization: Power BI (DAX, KPIs, Interactive Dashboard)

Data Processing: Power Query (ETL, Transformations) Dashboard Features

## 📂 Files Included
| File Name                    | Description                             |
|-----------------------------|-----------------------------------------|
| `financial_loan.csv`        | Raw dataset used for the dashboard      |
| `BANK_PROJECT_BHARATH.pdf`  | PDF summary report                      |
| `Bank_Loan_PowerBI_PPT.pptx`| PowerPoint presentation of key insights |
| `Query_Doc.docx`            | SQL queries used for preprocessing      |

---

## 🛠 Tools & Tech
- Power BI (Slicers, KPIs, Drillthrough)
- SQL Server (Joins, CTEs, Aggregations)
- Excel & Power Query
