# digital-payments-performance-analysis
A fintech payments analysis project using PostgreSQL, Power BI and Jira to investigate transaction performance and payment failures.
# Digital Payments Performance & Failure Analysis

## About the Project

I wanted to get a better understanding of how fintech payment businesses monitor transactions, deal with failed payments and use data to improve performance.

For this project, I worked with 20,000 simulated payment transactions. I used PostgreSQL to explore the data, Power BI to build a dashboard and Jira to organise the project and document requirements.

The main focus was to understand how well payments were performing, spot any unusual patterns and consider what a payments team could do to investigate them.

## Tools I Used

- **PostgreSQL** – to prepare, query and analyse the transaction data.
- **Power BI** – to build dashboards and present the findings.
- **Jira** – to organise the project, create tasks and document acceptance criteria.
- **GitHub** – to bring the project files and documentation together.

## What I Found

A few things stood out during the analysis:

- Analysed 20,000 transactions.
- Overall payment success rate of 80%.
- 4,000 failed transactions, representing a 20% failure rate.
- Total transaction value of 19,872,200 currency units.
- Failed transaction value of 3,996,790 currency units.
- All 4,000 failed transactions were associated with one merchant, Flipkart.
- Failure rates were almost identical across payment methods, banks and cities.

The merchant finding was particularly interesting. It raised questions about whether there could be an issue somewhere in the merchant's payment journey, although the data alone couldn't establish the cause.

## What I Recommended

Based on the findings, I identified a few areas that a payments business could look into:

1. Investigate why failed transactions were concentrated around Flipkart.
2. Improve monitoring of payment success rates and failed transaction values.
3. Capture more detail about failed payments, including error codes and failure reasons.
4. Introduce regular performance reviews and track actions taken to resolve issues.

## What's Included

- SQL queries used to investigate transaction performance.
- Power BI dashboard showing overall and merchant-level performance.
- Business analysis report covering findings, recommendations and data limitations.
- Jira project showing how I organised the work and documented requirements.

## A Note on the Data

The dataset is simulated, rather than taken from a real payments business. The findings are therefore useful for demonstrating the analysis process, but shouldn't be treated as evidence of actual payment infrastructure problems.

## Project Status

Completed – Personal Portfolio Project
