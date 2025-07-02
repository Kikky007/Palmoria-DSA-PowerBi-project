# Palmoria Group HR Analytics - Gender Equality Case Study
This project presents a comprehensive HR analytics case study for Palmoria Group, a manufacturing company in Nigeria, currently facing challenges related to gender inequality, pay gaps, and salary compliance across its regions and departments.
Using Power BI, this analysis uncovers critical insights and provides actionable recommendations to help Palmoria build a fairer and more inclusive workplace.



## Objectives
- Analyze **gender distribution** across departments and regions
- Examine **performance ratings** based on gender
- Identify potential **gender pay gaps**
- Assess **salary compliance** with the $90,000 minimum wage regulation
- Allocate **bonus payments** based on departmental performance rules
- Provide **visual insights** and strategic HR recommendations

## Data Cleaning & Preparation
-Removed duplicates and invalid records (e.g., missing salary or department)
-Assigned “N/A” to employees with no gender information
-Transformed bonus rule table to long format using Power Query (unpivoted)
- Merged the PALMORIA employee dataset and bonus rules using Department and Rating

## Tools Used
- Power BI: Data modeling, DAX measures, interactive visualizations
- Power Query in PowerBi (for cleaning)


## Key Insights
- Gender imbalance in Northern region (Kaduna)
- 69% of staff earn below $90,000 threshold
- Bonus payout structure proposed based on rating and department

## Recommendations
- Address gender pay gaps in key departments
- Hire more women in leadership roles
- Ensure all salaries meet the legal threshold
- Implement bonus strategy based on rating to improve performance

## Files
| File Name                        | Description                                  |
|----------------------------------|----------------------------------------------|
| `Palmoria Group emp-data.csv`   | Cleaned employee dataset                     |
| `Bonus Rules.csv`               | Department-based bonus structure             |
| `Palmoria DSA CAPSTONE.pbix`    | Final Power BI dashboard and Report                   |



