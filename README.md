# Lending Club Loan Risk Analysis | Tableau Project

This Tableau project explores loan performance and customer risk levels using Lending Club financial data. The goal was to answer key business questions around income distribution, debt-to-income (DTI) ratios, and payment behaviors using **custom-calculated fields**.

## Project Objectives
- Analyze the distribution of Total Annual Income and DTI
- Identify customer segments (Low, Medium, High DTI)
- Evaluate payment-to-loan ratios across loan purposes
- Detect underperforming loan categories for risk monitoring

## Key Calculated Fields
- `Total Annual Income`: Combines individual and joint income
- `DTI`: Total Debt / Total Annual Income × 100
- `DTI Level`: Categorized DTI as Low (≤35), Medium (35–49), High (≥50)
- `Total Payments to Loans`: Paid Total / Loan Amount
- `Payments to Loans Categories`: Flags loans with low repayment rates

## Visualizations
- Histogram of Total Annual Income (bin size: 25K)
- Histogram of DTI (bin size: 1, interval 2)
- Text table of DTI Level counts
- Bar chart of Loan Amounts by Purpose for Medium/High DTI customers
  - Colored by payment ratio category
  - Labeled with percentage paid

## Tools Used
- Tableau (Live Connection)
- Calculated fields, custom bins, parameter controls
- Modified OpenIntro dataset (via Brightspace)

## 🔗 Tableau Public
[View the Dashboard](https://public.tableau.com/app/profile/jessica.meza.perez/viz/lendingclubloanriskanalysis/Chart4?publish=yes)
