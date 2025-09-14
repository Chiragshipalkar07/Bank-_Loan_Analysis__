
# Bank Loan Analytics Dashboard
This project showcases comprehensive analysis of bank loan data using Excel, Power BI, and Tableau. The goal is to understand loan distribution trends, customer verification behavior, grade-wise risk patterns, and state-level loan activities. The dashboards provide actionable insights into financial metrics, credit quality, and borrower behavior over the years.

## Project Overview

Banks generate large volumes of loan-related data. This project aims to analyze that data to address key questions:
* What is the total loan distribution and growth trend over the years?
* How does home ownership relate to loan repayment behavior?
* What is the distribution of verified vs. non-verified accounts?
* Which states and credit grades show the highest revolving balances?
* What are the average interest rates across the loan types?

Four interactive dashboards were developed:

1. Excel Dashboard – Summary metrics with slicers and yearly insights
2. Power BI Dashboards (2 pages) – Loan growth, credit grade balances, and loan status breakdown
3. Tableau Dashboard – Deep dive into homeownership, loan distribution, and verified status segmentation

## Tools & Technologies
• Excel – Used for initial dashboard modeling and quick visualization
• Power BI – Developed two analytical dashboards with filters and KPIs
• Tableau – Built interactive visuals for geographical and behavioral patterns
• Data Source – Bank loan dataset (likely from Lending Club or similar datasets)

## Excel Dashboard

### Key Insights:
• Total Funded Amount: 435M
• Total Loan Amount: 446M
• Total Loan Applications: 39,717
• Average Interest Rate: 12.02%

### Highlights:
* Year-wise Loan Growth: Rapid increase from 2007 (251) to 2011 (21,656)
* Home Ownership vs. Last Payment Status:

  * RENT: 18,847 loans
  * OWN: 17,645 loans
  * Minor shares for OTHER and NONE
  * Payment Verification:

  * Verified: 59%
  * Not Verified: 41%
  * Top States by Loans:

  * Highest loan activity in California (\~7,097), followed by New York, Texas, and Florida
  * Grade and Sub-grade Revolving Balance:
  * Highest: Grades B3, B5, B4, and A5
  * Revolving balances trend higher in mid-credit grades (B, A, C)

## Power BI Dashboard – Page 1

### Key Metrics:
• Total Loans: 39.7K
• Total Funded Amount: 446M
• Total Received Amount: 483M
• Average Interest Rate: 12.02%

### Insights:
* Home Ownership vs. Payment Stats:
  * Mortgage & Rent show majority of loan payments
  * Minor share by OWN, OTHER, and NONE
* Verified / Non-Verified Accounts:
  * Verified: 219.89M (58.88%)
  * Not Verified: 153.54M (41.12%)
* Grade-wise Revolving Balances:

 * Top subgrades: B3 (40M), B5 (38M), B4 (35M), A5 (35M)
## Power BI Dashboard – Page 2
## Breakdown:
* Loan Status by State:
  * States like California (5.8K) and Nevada (3.2K) have high volumes
  * Fully Paid loans dominate, followed by Charged Off and Current
* Loan Status by Year:

  * Strong upward trend, peaking in 2016 with 11.9K loans
  * Steady growth seen from 2010 through 2016
--
## Tableau Dashboard

### Key Highlights:
• Total Loan Amount: 446M
• Total Funded Amount: 435M
• Total Accounts: 369K
• Average Interest Rate: 12.02%

### Year-wise Loan Distribution:
* 2007: 2M
* 2008: 14M
* 2009: 46M
* 2010: 122M
* 2011: 261M

### Verified vs. Non-Verified Status:
* Verified: 220M (59.24%)
* Not Verified: 154M (41%)

### Grade & Subgrade Revolving Balance:
 Top Subgrades:
 B3 (39.72M), A5 (35.30M), B5 (37.86M), A4 (34.56M), C1 (29.38M)

### Home Ownership vs. Last Payment Stats:
* Mortgage: 59.24%
* Rent: 33.94%
* Own: 6.83%
* Other / None: Less than 0.1% combined

## Insights
• Loan volumes saw exponential growth from 2007 to 2016, peaking in 2016
• Verified accounts consistently account for nearly 60% of the loan value
• Mortgage and Renters dominate loan portfolios
• Mid-tier credit grades (A & B) show higher revolving balances, suggesting strong borrowing power
• California, Texas, and Nevada show the highest loan activities across all dashboards
• The average interest rate remained consistent at 12.02%

## Future Improvements
• Add default risk prediction using logistic regression or classification models
• Integrate geo-spatial filtering for interactive maps in Tableau
• Enable real-time connections with Power BI Service and SQL backend
• Use DAX formulas for advanced metric calculations
• Develop cohort analysis to monitor borrower behavior over time

## Learning Outcomes
• Gained hands-on experience in dashboard development using Excel, Power BI, and Tableau
• Explored key financial indicators like revolving balance, verification status, and loan grade segmentation
• Learned how to transform raw loan data into decision-ready visuals
• Strengthened understanding of banking KPIs and credit health metrics
• Built scalable and interactive dashboards for stakeholders and loan officers
