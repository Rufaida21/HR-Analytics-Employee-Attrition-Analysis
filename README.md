# HR Analytics: Employee Attrition & Retention Analysis

## Project Overview
This project explores employee attrition using HR data to identify patterns and factors associated with employees leaving an organization.

The analysis focuses on overtime, job satisfaction, and monthly income to better understand employee turnover and potential retention risks.

## Dataset
- **Source:** [Kaggle – IBM HR Analytics Employee Attrition & Performance](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)
- **Rows:** 1,470 employees
- **Columns:** 35 features

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Analysis Performed
- Inspected dataset structure and data types.
- Checked for missing values and duplicate records.
- Analyzed overall employee attrition.
- Explored the relationship between overtime and attrition.
- Examined job satisfaction levels and attrition.
- Analyzed monthly income distribution.
- Identified potential high-income outliers using the IQR method.
- Created visualizations to communicate key findings.

## Key Findings

**1. Employee Attrition**
- 237 employees left the organization.
- The overall attrition rate was approximately 16.1%.

**2. Overtime and Attrition**
- Employees who worked overtime had an attrition rate of approximately 30.5%.
- Employees who did not work overtime had an attrition rate of approximately 10.4%.

**3. Job Satisfaction**
- Employees with the lowest job satisfaction rating had a higher attrition rate (22.8%) compared to those with the highest rating (11.3%).

**4. Monthly Income**
- The income distribution was right-skewed.
- 114 potential high-income outliers were identified using the IQR method. These values were flagged for examination, not removed.

## Conclusion
The analysis highlights patterns associated with employee attrition, particularly overtime and job satisfaction.

These findings can help inform HR discussions about employee retention. However, the analysis identifies associations and does not establish direct causal relationships.

## Project Files
- `HR_Analytics_Employee_Attrition_Analysis.ipynb` – Jupyter Notebook containing the analysis and visualizations.
