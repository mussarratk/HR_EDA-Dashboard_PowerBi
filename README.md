# HR Employee Distribution Dashboard in Power BI

## Goal

The goal of this project is to provide insights into various aspects of employee distribution within the company. By analyzing the data, we aim to answer key questions related to gender breakdown, race/ethnicity distribution, age demographics, employment tenure, departmental distribution, turnover rates, location distribution, and changes in employee count over time.

## Implementation

The implementation involved the following steps:

1. **Data Cleaning in PostgreSQL 15**: The raw data was cleaned using PostgreSQL 15. Negative ages and future termination dates were excluded during querying, resulting in a clean dataset for analysis.

2. **Export to CSV Format**: The cleaned dataset was then exported to CSV format for further visualization in Power BI.

3. **Power BI Dashboard**: The CSV data was imported into Power BI, where visualizations and insights were created to address the project's goals and answer the specified questions.

## Key Metrics and Findings

The analysis of the data revealed the following key metrics and findings:

- The distribution of male employees is higher than female employees.
- The majority of employees belong to the White race, while Native Hawaiian and American Indian races are the least represented.
- The age distribution is categorized into 5 groups (18-24, 25-34, 35-44, 45-54, 55-64). The highest number of employees fall into the 25-34 age group.
- Headquarters has a larger employee presence compared to remote locations.
- Terminated employees have an average employment length of around 7 years.
- Gender distribution across departments is relatively balanced, but there is a slight male dominance.
- Marketing department has the highest turnover rate, while Research and Development, Support, and Legal departments have the lowest.
- A significant number of employees are from the state of Ohio.
- The company's employee count has increased over the years.
- Average tenure varies by department, with Legal and Auditing having the highest and Services, Sales, and Marketing having the lowest.

## Limitations

- Negative age records were excluded from analysis (967 records).
- Future termination dates were omitted from analysis (1599 records).
- The age cutoff was set to 18 years and above.
- Some analysis may be limited due to data availability and quality.
