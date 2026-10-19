# Travel & Expense Process Analytics
**Hasselt University | Data Science for Business (5082) | Group 6**

## Project Summary
Analysis of Hasselt University's travel authorisation and 
expense reimbursement process using process mining techniques. 
The study covers 6,375 international expense claims across 
2017-2018 and identifies a systemic compliance gap where 
EUR 377,549 was reimbursed without valid travel authorisation.

## Research Questions
1. To what extent are expense claims correctly preceded by 
   an approved travel authorisation?
2. Can anomalies or outliers be detected indicating 
   non-standard or risky behaviour?
3. How can end-to-end throughput time be improved when 
   multiple claims are linked to one authorisation?

## Key Findings
- 93.1% of cases were compliant; 438 cases (6.9%) had 
  no permit approval
- All 438 non-compliant cases linked to a single dummy 
  permit (permit 424) with identical trip date 2018-04-10
- 426 of those 438 cases (97.3%) were paid out regardless
- Non-compliant cases have a 47% higher amount outlier rate
  than compliant cases (7.8% vs 5.3%)

## Tools Used
- KNIME Analytics Platform — data preparation, process mining
- Power BI — interactive compliance dashboard
- Microsoft Word — analytical report

## Team
Group 6
