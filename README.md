# Human-Resources-Project-SQL
Analysis of a Human Resource data for gathering of insights and visualization
**Project Overview**
Data Source
Tools Used
Data Preparation and Data Cleaning
Data Analysis
Findings
**Project Overview**
The objective of this HR analytics project is to analyze workforce dynamics and trends within our organization. By examining the HR dataset, we aim to identify patterns in employee demographics, tenure, turnover rates, and departmental distributions. The insights gained from this analysis will enable decision-makers to optimize HR strategies, improve employee retention, and enhance overall organizational performance.
**Data Source**
The primary dataset utilized for this analysis is sourced from the "Human_Resources.csv" file, comprising comprehensive employee data essential for the HR analytics project.
**Tools Used**
Microsoft Excel:To clean and analyze the data.
PowerBI Desktop: To visualize the outcomes.
**Data Preparation and Data Cleaning Process in Microsoft Excel**
Open Data: Open the csv file using microsoft excel.
Check Data Types: Review data types of all columns using the "DESCRIBE" command.
Standardize Date Formats: Use SQL functions to standardize date formats and convert text to date data types.
Handle Special Characters: Rename columns with special characters using the "ALTER TABLE" command.
Address Missing Values: Identify and handle missing values, particularly in date columns like "termdate."
Update Data Types: Modify data types as needed, such as changing text to date or integer.
Add New Columns: Introduce new columns like "age" for additional analysis.
Calculate Derived Metrics: Calculate metrics like age based on existing data.
Ensure Data Integrity: Validate data integrity and consistency throughout the process.
Questions Answered in Data Analysis Process in MSSQL
Total Number of Employees.
Avearge age of Employees.
The gender breakdown of employees in the company.
Race/ethnicity breakdown of employees.
Age distribution of employees.
Number of employees at headquarters versus remote locations.
Average length of employment for terminated employees.
Gender distribution across departments and job titles.
Distribution of job titles across the company.
Department with the highest turnover rate.
Distribution of employees across locations by city and state.
Employee changes count over time based on hire and termination dates.
Tenure distribution for each department
Note: Data cleaning and data analysis SQL files are attached for reference.
**Findings from the Analysis**
The company employs a total of 22,214 individuals, with an average age of 35 years. There is a higher representation of male employees compared to females.
White individuals constitute the majority racial group, while Native Hawaiian and American Indian individuals are the least represented.
The age of employees ranges from 21 to 58 years, with the youngest being 21 and the oldest being 58.
Employees were categorized into five age groups: 18-24, 25-34, 35-44, 45-54, and 55-64. The largest proportion of employees falls within the 35-44 age group (4,997 employees), followed by the 25-34 age group (4,932), while the smallest group is 55-64 (1,021 employees).
The majority of employees (75%) work at the headquarters, with the remaining 25% working remotely.
The average length of employment for terminated employees is approximately 8 years.
Gender distribution across departments is relatively balanced, with a slightly higher proportion of male employees across all departments. The Engineering department boasts the highest number of employees, while the Auditing department has the fewest.
The Auditing department (termination rate of 0.18) experiences the highest termination rate, followed by the Legal department (0.13). The Marketing department exhibits the lowest termination rate at 0.09.
A significant portion of employees originate from the state of Ohio.
