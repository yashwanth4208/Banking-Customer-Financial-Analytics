# Banking Customer & Financial Analytics

## 📊 Project Overview

An interactive banking analytics project using Microsoft Power BI and
Excel to analyze customer profiles, banking relationships, loans,
deposits, savings, credit card balances, income, loyalty and financial
performance.

The dashboard analyzes approximately 3,000 customer records to provide
insights into customer demographics, lending activity, deposit behavior,
financial products and individual customer profiles.

---

## 📂 Dataset

This project uses a banking customer dataset containing approximately
3,000 customer records.

The dataset contains information related to:

- Customer demographics
- Age and gender
- Nationality
- Occupation
- Income
- Banking relationships
- Loyalty classification
- Loans
- Deposits
- Savings accounts
- Checking accounts
- Foreign currency accounts
- Credit card balances
- Business lending
- Properties owned
- Risk weighting

The source Excel dataset is included in the repository under:

`data/Banking Dashboard data.xlsx`

---

## 🎯 Business Questions

- How many customers are included in the banking portfolio?
- What is the overall loan exposure?
- What is the total deposit balance?
- How are loans distributed across banking relationships?
- Which nationalities contribute the highest loan exposure?
- How does income relate to loan activity?
- How are customers distributed across loyalty classifications?
- How do customers use different financial products?
- How do deposits and savings vary across customer segments?
- How do customer financial profiles differ by demographics?
- What financial information is associated with individual customers?

---

## 🛠️ Tools & Technologies

- Microsoft Power BI
- DAX
- Power Query
- Microsoft Excel
- Data Modeling
- Data Visualization
- Business Intelligence
- Git/GitHub

---

## 🔄 Data Workflow

Banking Excel Dataset
        ↓
Data Preparation
        ↓
Power BI Data Model
        ↓
DAX Measures & Calculations
        ↓
Interactive Visualizations
        ↓
Banking Analytics Dashboard
        ↓
Customer-Level Drill-Through

---

## 🧹 Data Preparation

The banking dataset was prepared for analysis and visualization using
Power BI and Power Query.

The data preparation and modeling process includes:

- Reviewing dataset structure and data types
- Preparing customer demographic fields
- Organizing banking relationship information
- Preparing financial metrics
- Structuring loan and deposit fields
- Preparing savings and checking account information
- Organizing customer loyalty classifications
- Preparing fields for interactive filtering
- Building relationships required for dashboard analysis
- Creating calculated measures for financial KPIs

### Key Analytical Metrics

- Total Customers
- Total Loans
- Total Deposits
- Total Fees
- Credit Card Balance
- Savings Balance
- Bank Loan
- Business Lending
- Customer Income
- Customer Financial Products
- Risk Weighting
- Loyalty Classification

---

# 📊 Power BI Dashboard

The dashboard contains five analytical pages.

## 1. Home

The Home page provides a high-level overview of the banking portfolio
and customer financial activity.

### Key KPIs

- Total Customers
- Total Loans
- Total Deposits
- Total Fees
- Credit Card Balance
- Savings Balance

### Filters

- Time Period
- Gender
- Banking Relationship
- Investment Advisor

The page provides an overall view of customer and financial metrics
before moving into detailed loan, deposit and customer analysis.

![Home Dashboard](docs/home.png)

---

## 2. Loan Analysis

The Loan Analysis page focuses on lending activity and customer loan
behavior.

### Key Analysis

- Bank Loan by Banking Relationship
- Bank Loan by Nationality
- Bank Loan by Income Band
- Total Loan
- Bank Loan
- Business Lending
- Credit Card Balance
- Loan distribution across customer segments

The page allows loan exposure to be explored across customer
characteristics and banking relationships.

![Loan Analysis](docs/loan-analysis.png)

---

## 3. Deposit Analysis

The Deposit Analysis page focuses on customer deposits and savings
products.

### Key Analysis

- Total Deposits
- Savings Accounts
- Checking Accounts
- Foreign Currency Accounts
- Deposit distribution
- Customer financial segments
- Deposit-related customer analysis

The page provides an overview of how customers use different deposit
and savings products.

![Deposit Analysis](docs/deposit-analysis.png)

---

## 4. Customer Summary

The Customer Summary page focuses on customer characteristics,
financial profiles and banking relationships.

### Key Analysis

- Customer demographics
- Customer income
- Loyalty classification
- Banking relationship
- Financial product usage
- Customer financial metrics
- Customer segmentation

The page provides a broader view of customer behavior and financial
relationships across the banking portfolio.

![Customer Summary](docs/summary.png)

---

## 5. Customer Drill-Through

The Drill-Through page provides a detailed customer-level view.

### Customer-Level Analysis

- Customer income
- Loans
- Deposits
- Savings
- Credit card balance
- Financial products
- Customer classification
- Banking relationship
- Other available customer financial metrics

The drill-through functionality allows users to move from summary
analysis to a more detailed individual customer profile.

![Customer Drill-Through](docs/drill-through.png)

---

# 💡 Key Business Insights

### 1. Customer Portfolio

The dataset contains approximately 3,000 customer records, allowing
customer demographics and financial activity to be analyzed at both
portfolio and individual-customer levels.

### 2. Loan Exposure

Loan activity can be analyzed across banking relationships,
nationalities and income bands to understand differences in lending
exposure across customer segments.

### 3. Deposit & Savings Behavior

Customer deposits can be examined alongside savings, checking and
foreign currency accounts to understand the usage of different
financial products.

### 4. Customer Loyalty

Loyalty classification provides a way to segment customers and
compare their financial relationships and product usage.

### 5. Customer Financial Profiles

The combination of income, loans, deposits, savings, credit card
balances and other financial products provides a broader view of
individual customer financial profiles.

---

# 📌 Business Recommendations

- Monitor loan exposure across different customer segments.
- Analyze income and lending relationships when evaluating customer
  financial profiles.
- Identify customer segments with higher deposit and savings activity.
- Use loyalty classifications to understand differences in customer
  financial-product usage.
- Monitor credit card balances alongside other customer financial
  products.
- Use customer-level drill-through analysis to investigate individual
  financial profiles.
- Compare customer demographics with financial activity to identify
  meaningful portfolio patterns.

---

# 📁 Project Structure

```text
Banking-Customer-Financial-Analytics/
│
├── data/
│   └── Banking Dashboard data.xlsx
│
├── docs/
│   ├── home.png
│   ├── loan-analysis.png
│   ├── deposit-analysis.png
│   ├── summary.png
│   └── drill-through.png
│
├── powerbi/
│   └── Banking Dashboard.pbix
│
└── README.md
