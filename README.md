# Banking Customer Analytics | Power BI Project

An interactive **Banking Customer Analytics Dashboard built with Microsoft Power BI** to explore customer demographics, transaction activity, banking products, account performance, loan portfolios, credit risk, revenue, and profitability.

This project brings together five dashboard pages to provide a consolidated view of banking operations and financial performance. It demonstrates how data analytics, business intelligence, and interactive visualization can support customer analysis, product monitoring, loan portfolio assessment, and management reporting.

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Microsoft%20Excel-Source%20Data-217346?logo=microsoftexcel&logoColor=white)
![Project](https://img.shields.io/badge/Project-Portfolio-blue)
![Dataset](https://img.shields.io/badge/Dataset-Synthetic-orange)

---

## Project Overview

The Banking Customer Analytics project focuses on understanding customer behavior and evaluating banking performance through interactive Power BI dashboards.

The report covers five analytical areas:

- **Customer & Transaction Analytics:** Customer activity, transaction volume, transaction value, and banking channels.
- **Customer Demographics & Segmentation:** Customer profiles, income bands, age groups, regions, and customer segments.
- **Accounts & Product Performance:** Account balances, account status, banking products, and product revenue.
- **Loans & Credit Risk:** Loan exposure, outstanding balances, loan status, interest rates, and risk categories.
- **Revenue & Management:** Revenue, costs, profit, profit margin, growth, and target-oriented reporting.

**Project Type:** Personal Data Analytics Portfolio Project  
**Dataset:** Synthetic / Practice Dataset  
**Primary Tool:** Microsoft Power BI Desktop  
**Source Data:** Microsoft Excel  
**Report Pages:** 5

## Dashboard Pages

### 1. Banking Executive Overview

**Focus:** Customer Base, Transaction Activity, Financial Performance & Banking Trends

![Banking Executive Overview](screenshots/banking-executive-overview.png)

Provides a high-level overview of banking activity and financial performance.

**Key KPIs**
- Total Customers
- Total Transactions
- Transaction Amount
- Total Revenue
- Total Profit
- Profit Margin

**Key Analyses**
- Monthly Transaction Trend
- Transaction Activity by Channel
- Transaction Value by Type
- Revenue by Banking Product
- Monthly Revenue Trend
- Customer Segment Distribution

### 2. Customer Demographics & Segmentation

**Focus:** Customer Profiles, Income Distribution, Segments & Banking Behavior

![Customer Demographics & Segmentation](screenshots/customer-demographics-segmentation.png)

Explores customer characteristics and compares customer groups across demographic and financial categories.

**Key KPIs**
- Total Customers
- Active Customers
- Annual Income
- Average Account Balance
- Revenue per Customer

**Key Analyses**
- Customer Distribution by Region
- Customers by Income Band
- Customer Distribution by Age
- Customer Segment Distribution
- Customer Segment & Income Analysis
- Customer Gender Distribution

### 3. Accounts & Product Performance

**Focus:** Account Portfolio, Balances, Banking Products & Customer Activity

![Accounts & Product Performance](screenshots/accounts-product-performance.png)

Examines account activity, banking products, balances, and reported product revenue.

**Key KPIs**
- Total Accounts
- Active Accounts
- Total Account Balance
- Average Account Balance
- Total Revenue

**Key Analyses**
- Transactions by Banking Product
- Account Balance by Type
- Revenue by Banking Product
- Accounts by Account Type
- Revenue by Product Category
- Banking Product Performance
- Average Balance by Account Type
- Account Status Distribution

### 4. Loans & Credit Risk

**Focus:** Loan Portfolio, Outstanding Exposure, Interest Rates & Credit Risk

![Loans & Credit Risk](screenshots/loans-credit-risk.png)

Examines loan portfolio distribution and the risk indicators presented in the report.

**Key KPIs**
- Total Loans
- Active Loans
- Total Loan Amount
- Loan Balance
- Default Rate
- High Risk Loan

**Key Analyses**
- Loan Status Distribution
- Loan Portfolio by Product
- Average Interest Rate by Product
- Outstanding Balance by Risk Category
- Loan Exposure by Customer Segment
- Loans by Risk Category

### 5. Revenue & Management

**Focus:** Financial Performance, Target Achievement & Management KPIs

![Revenue & Management](screenshots/revenue-management.png)

Provides a financial overview of banking products, profitability, and management performance indicators.

**Key KPIs**
- Total Revenue
- Total Cost
- Total Profit
- Profit Margin
- Revenue Target
- Revenue YoY Growth

**Key Analyses**
- Monthly Revenue vs Target
- Monthly Transactions vs Target
- Profit by Banking Product
- Revenue by Banking Product
- Revenue by Customer Segment
- Product Management Performance
- Revenue Target Achievement by Product

---

## Key Performance Indicators

The following figures are displayed in the supplied Power BI report. They are reported dashboard values and should be interpreted subject to the validation considerations documented below.

| KPI | Reported Value |
|---|---:|
| Total Customers | 5K |
| Active Customers | 5K |
| Total Transactions | 30K |
| Transaction Amount | 4bn |
| Total Revenue | 69.30M |
| Total Profit | 36.59M |
| Profit Margin | 52.80% |
| Total Accounts | 8K |
| Active Accounts | 7K |
| Total Account Balance | 9bn |
| Total Loans | 3K |
| Active Loans | 2K |
| Total Loan Amount | 6bn |
| Loan Balance | 2.36bn |
| Default Rate | 4.07% |
| High Risk Loan | 17.90% |
| Revenue YoY Growth | 102.20% |

## Business Questions Addressed

The dashboard is designed to investigate the following business questions:

1. How is the banking customer base distributed across demographic and income groups?
2. Which customer segments contribute to banking revenue?
3. How does transaction activity vary across banking channels?
4. Which banking products generate the highest transaction activity and revenue?
5. How are customer account balances distributed across account types?
6. What is the distribution of active, dormant, and closed accounts?
7. How is the loan portfolio distributed across products and risk categories?
8. Which customer segments account for the largest loan exposure?
9. How do default rates and high-risk loan indicators appear across the portfolio?
10. How do revenue, costs, profit, and management targets compare?

## Data Validation & Analytical Considerations

Data validation is an important part of this project. The following observations should be investigated before interpreting the dashboard figures as confirmed business results.

| Validation Area | Observation | Recommended Check |
|---|---|---|
| Transaction totals | Executive page reports 30K; product table reports 20,023 | Check transaction coverage, filters, and aggregation |
| Transaction amount | Executive page displays 4bn; product table displays 2,472M | Reconcile units, date ranges, and transaction populations |
| Customer segmentation | Customer page reports 5K; segment and income table totals 2,864 | Investigate missing classifications and filter context |
| Active customers | Total and active customers both display 5K | Confirm the active-customer definition |
| Revenue target | KPI is displayed as 1.95% | Verify unit, measure, and number formatting |
| Revenue growth | Reported YoY growth is 102.20% | Validate comparison periods and date calculations |
| Loan risk | Default Rate and High Risk Loan are displayed | Confirm denominators and risk classification rules |
| Date consistency | Selected year and month should be reconciled with trend-chart periods | Check date relationships, slicers, and filter interactions |

These observations are validation tasks, not proof of errors in the underlying Power BI model. The final interpretation of each measure should be based on the source data, DAX definition, and filter context.

## Dataset Information

This project uses a **synthetic / practice banking dataset** for portfolio demonstration and analytical learning.

The report explores customer, transaction, account, banking product, loan, risk, and financial information.

The Excel workbook is the supplied source file. Exact worksheet names, row counts, and data-model relationships should be documented after inspecting the workbook and Power BI model.

**Data Disclaimer:** This project does not represent verified customer records, financial results, or credit-risk reporting from a real banking institution.

## Tools & Technologies

| Technology | Application |
|---|---|
| Microsoft Power BI Desktop | Dashboard development and interactive reporting |
| Microsoft Excel | Source data and workbook |
| DAX | KPI calculations and measures, where implemented |
| Power Query | Data preparation and transformation, where implemented |
| Data Visualization | Charts, KPI cards, tables, and slicers |
| Business Intelligence | Customer, product, financial, and risk analysis |

## Skills Demonstrated

- Banking and financial analytics
- Customer demographics and segmentation
- Transaction and channel analysis
- Banking product performance analysis
- Account portfolio analysis
- Loan portfolio monitoring
- Credit risk analysis
- Revenue and profitability reporting
- KPI and target monitoring
- Power BI dashboard development
- Data validation and analytical thinking
- Business-focused data visualization

## Repository Structure

```text
Banking-Customer-Analytics-Power-BI/
│
├── README.md
│
├── Banking Customer Analytics.pbix
├── Banking Customer Analytics.xlsx
├── Banking Customer Analytics.pdf
│
├── screenshots/
│   ├── banking-executive-overview.png
│   ├── customer-demographics-segmentation.png
│   ├── accounts-product-performance.png
│   ├── loans-credit-risk.png
│   └── revenue-management.png
│
└── documentation/
    ├── project-overview.md
    ├── business-requirements.md
    ├── dashboard-documentation.md
    ├── kpi-dictionary.md
    ├── data-dictionary.md
    └── data-validation.md
```

## How to Explore the Project

1. Clone or download this repository.
2. Open `Banking Customer Analytics.pbix` using Microsoft Power BI Desktop.
3. Navigate through all five dashboard pages.
4. Explore the slicers and interactive visuals.
5. Review the Excel source workbook.
6. Inspect the data model and DAX measures.
7. Review the validation notes before interpreting reported KPIs.

## Project Purpose

This project demonstrates the application of Power BI to banking business intelligence. It combines customer analytics, transaction analysis, account and product performance, loan portfolio monitoring, credit-risk indicators, and financial reporting in one interactive reporting experience.

It is designed to demonstrate both business understanding and technical data analytics skills in a portfolio context.

## Author

**Altamash Nizamuddin**

Data Analyst | Excel • Power BI • Python • MySQL

- GitHub: [@altamash-analyst](https://github.com/altamash-analyst)
- Email: [altamash9876@gmail.com](mailto:altamash9876@gmail.com)

---

## Suggested GitHub Repository Description

Power BI Banking Customer Analytics Dashboard analyzing customer segmentation, transaction activity, banking products, account performance, loan portfolios, credit risk, revenue, and profitability using a synthetic dataset.

## GitHub Topics

`power-bi` `banking-analytics` `customer-analytics` `financial-analytics` `credit-risk-analysis` `loan-portfolio-analysis` `customer-segmentation` `banking-dashboard` `business-intelligence` `data-analytics` `dax` `microsoft-excel` `data-visualization` `Altamash-Analyst`
