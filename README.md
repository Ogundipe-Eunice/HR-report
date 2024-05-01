
| Dashboard image |
| ----------- |
|[View Dashboard image](HR_Dashboard.png)|


## Dashboard: 
[View Dashboard](https://app.powerbi.com/links/HH5SA-6EjJ?ctid=5781ca16-51a6-4e98-9be9-dc2b9d03b82d&pbi_source=linkShare)



## Overview
Our Human Resources department has compiled an extensive dataset over the past years that encapsulate various aspects of employee information and their professional journey within the company. However, there is a gap in extracting meaningful insights from this rich data, which could be leveraged to enhance employee satisfaction, streamline HR processes, and improve overall workforce management.

## Challenge
The current HR Dashboard indicates several potential areas of concern:
- A significant number of terminations compared to the total employee count.
- Disparities in the age distribution of employees which may point to generational gaps in the workforce.
- Differences in promotion eligibility that could imply underlying issues in career progression or performance evaluation processes.

## Objective
To address these challenges, we aim to:
1. Understand the factors contributing to employee turnover and devise strategies to enhance employee retention.
2. Analyze the age distribution and employment type to ensure a diverse and well-balanced workforce.
3. Investigate the promotion eligibility criteria to promote fairness and transparency in career advancement opportunities.

## Data Analysis Goals
- To conduct a thorough analysis of the employee lifecycle within the company.
- To identify patterns and trends that correlate with employee satisfaction and retention.
- To provide actionable recommendations to the HR department to foster a positive work environment and employee growth.

## Expected Outcome
By harnessing the insights derived from our HR dataset, we expect to improve our HR strategies, leading to increased employee engagement, reduced turnover rates, and a more dynamic, satisfied workforce.




### Steps followed For data importing and cleaning in Power Query


# Data Cleaning Steps for HR Dataset

The HR dataset was subjected to the following data cleaning process:

1. **Promoted Headers**: The first row of the dataset was converted to column headers to accurately represent the dataset fields.

2. **Changed Type**: Data types for various columns were changed to ensure each field in the dataset was represented by the correct data type (e.g., numerical fields as integers or floats, dates formatted as date types).

3. **Inserted Age**: An 'Age' column was computed, likely from a 'Date of Birth' column to understand the age distribution of employees.

4. **Added Custom**: Custom columns were created for specific calculations that were not originally present in the dataset.

5. **Changed Type1**: A subsequent change in data types indicates an iterative approach to ensuring data types were correctly applied after initial transformations.

6. **Removed Columns**: Some columns were removed, possibly because they were redundant, not needed for analysis, or contained sensitive information.

7. **Reordered Columns**: Columns were reordered to place key fields in a more logical arrangement for analysis.

8. **Removed Columns1**: Additional columns were removed in a separate step, suggesting a multi-stage approach to refining the dataset.

9. **Renamed Columns**: Columns were renamed to more descriptive titles, aiding in clarity and understandability for end-users.

10. **Removed Columns2**: Further removal of columns, indicative of an ongoing effort to streamline the dataset.

11. **Inserted Age1**: Another 'Age' related column was inserted, possibly to correct or enhance the previous age calculation.

12. **Added Custom1**: Additional custom calculations were introduced for deeper data insights.

13. **Changed Type2**: Additional changes to data types, indicating refinement of earlier steps or application to new columns.

14. **Removed Columns3**: Further streamlining of the dataset by removing superfluous columns.

15. **Merged Queries**: Data from different queries were merged to consolidate information into a single dataset.

16. **Expanded Nationality.1**: The 'Nationality' column was expanded, which might have involved unpacking a nested data structure such as JSON or XML.

17. **Filtered Rows**: Rows were filtered to exclude irrelevant data, such as incomplete records or outliers.

18. **Removed Columns4**: Final removal of columns not required for the intended analysis.

19. **Renamed Columns1**: Final renaming of columns for consistency and clarity before analysis.

Each of these steps was performed iteratively to ensure the dataset was clean, relevant, and ready for insightful analysis.





| Data cleaning |
| ----------- |
|[View Applied steps](Applied_steps.png)|





| DAX Calculated image|
| ----------- |
|[View calculated measures](Calculations_HR.png)|


# Valuable Insights from HR Dashboard

The HR Dashboard provides critical metrics that can help in understanding the workforce dynamics, identifying areas for improvement, and informing strategic decisions. Below are some key insights drawn from the HR data:

## 1. Gender Distribution
- The nearly equal distribution of male and female employees suggests effective gender diversity practices. However, the significant number of employees identifying as 'Other' warrants a deeper understanding of gender diversity and inclusion policies.

## 2. Employee Age and Tenure
- The age distribution shows a balanced workforce across different age groups. Continuous strategies to engage both younger and older demographics are crucial for maintaining a dynamic and experienced workforce.

## 3. Termination Trends
- A relatively high total termination rate could indicate potential issues in employee satisfaction, job fit, or organizational culture. Further analysis is needed to identify the root causes and reduce turnover rates.

## 4. Employment Type Distribution
- The close numbers in full-time, part-time, and contract employee ratios highlight a flexible employment strategy. This can be a strong point in attracting diverse talents preferring different kinds of work arrangements.

## 5. Promotion Eligibility
- With a considerable portion of the workforce eligible for promotion, it's essential to ensure that the promotion processes are transparent and merit-based to keep employees motivated and engaged.

## 6. Performance Metrics
- Monitoring the average performance and identifying departments or positions with prevalent low performance can help target specific training programs and improve overall productivity.

## 7. Salary Distribution
- The total salary expenditure in relation to departmental and positional breakdowns can provide insights into budget allocation efficiency and whether compensation strategies align with industry standards.

## 8. Active vs. Inactive Employees
- The high percentage of active employees is positive, but the factors contributing to the inactivity of the remainder should be investigated to ensure it does not impact the operational efficiency.

## Actions Recommended
- **Diversity and Inclusion Initiatives:** Explore more about the needs and expectations of employees who identify as 'Other' to enhance inclusivity policies.
- **Retention Strategies:** Develop targeted employee retention programs based on the insights from termination trends.
- **Performance Improvement Plans:** Implement or reevaluate performance improvement strategies focusing on areas or groups showing lower performance scores.
- **Compensation Review:** Conduct a thorough review of compensation packages against performance metrics and market standards to ensure fairness and competitiveness.

These insights should guide the strategic HR decisions to foster a more engaged and productive workforce.
