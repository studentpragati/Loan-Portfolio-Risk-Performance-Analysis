## Bank Loan Analysis – Power BI Dashboard

## 📊 Project Overview
Business Problem: A bank's loan operations team had no real-time summary of portfolio health — unable to track bad loan exposure, monitor funded vs received amounts, or assess risk by loan status, grade, and purpose on a month-over-month basis.

## 📁 File

Bank_loan_analysis.pbix: The Power BI report file containing data modeling, visualizations, and insights. -'bank_loan_analysis.sql':

Tools Used: Power BI, DAX, Financial Data Modeling

## What I Did:

Modeled 1,028 loan applications with fields for funded amount, received amount, interest rate, DTI, grade, and purpose
Built KPI cards with MTD and MOM variance for: Total Applications (1,028 | MOM +44.1%), Funded Amount ($18.9M | MOM +33.1%), Amount Received ($21.0M | MOM +29.7%), Avg Interest Rate (19.7%), Avg DTI (14.2%)
Created donut charts separating Good Loans (69.7% — 717 applications, $12.9M funded) vs Bad Loans (30.3% — 311 applications, $6.0M funded)
Designed a loan status breakdown table for Current, Charged Off, and Fully Paid — showing funded amount, received amount, MTD figures, avg interest rate, and avg DTI
Added filters for States, Grade (A–F), and Purpose for drill-down analysis
Built 3 report pages: Summary, Overview, and Details

## Key Insights:

30.3% bad loan rate represents $6.0M in risky funded exposure — a significant red flag
Charged Off loans average 19.46% interest — slightly lower than Current loans at 20.01%
MOM growth of 44.1% in applications signals rapid portfolio expansion requiring tighter risk controls
Grand Total funded: $21.0M vs received $21.0M — near parity, indicating healthy collection
DTI of 14.2% avg suggests borrowers have manageable debt loads overall

## Impact: 
Enabled leadership to monitor loan portfolio health in real time; bad loan flag of $6M prompted risk review process; MTD/MOM tracking helped the credit team set monthly targets and course-correct faster

## Dashboard Output: 
3-page Power BI report (Summary, Overview, Details) with KPI cards, good/bad loan donut charts, loan status table, and filters for State, Grade, and Purpose.


