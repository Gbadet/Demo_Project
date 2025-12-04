# Human Resources
This project explores Human Resource (HR) Analytics using data-driven insights to help organizations make smarter workforce decisions. It focuses on analyzing employee data to uncover trends in attrition, performance, demographics, job satisfaction, and workforce diversity.

### Data Source
The source of this dataset is kaggle.com. The primary dataset used in this analysis is HR.csv

### Tools
- Excel - Data Cleaning [Download Here](hr_data_cleaned.csv)
- SQL - Data Analysis
- Power BI - Data Visualization

### Data Cleaning
1. Remove duplicated rows
2. Replagce null values
3. Data formatting

### Exploratory Data Analysis
1. What is total number of employees?
2. What is the total number of job candidates?
3. What is the attrition rete?

### Analysis
```
SELECT COUNT(*) FROM EMPLOYEE
  WHERE ENDDATE IS NOT NULL
```

### Result/Findings
1. Total number of Employees is 140
2. A total of 14 employees left the firm.
3. The attritin rate is 1.24%

### Recommendations
1. Improve employee retention to reduce employee turnover
