# Pewlett Hackard Analysis

## Project Overview
The manager of a company would like to know the number of retiring employees and those employees that are eligible to 
participate in a mentorship program.

1. Find the number of retiring employees by title.
2. Group together the eligible employees for a mentorship program.

## Resources
- Data Source: departments.csv, titles.csv, employees.csv, salaries.csv, dept_emp.csv, dept_manager.csv
- Software: pdAdmin 4 v6, PostgreSQL 13.6

## Results
- There are 133,776 entries in the retirement_titles.csv where many are repeats of employees who have been promoted and given new titles.
- There are 72,458 entries in the unique_titles.csv so that means that many employees had been promoted or moved to different deparments over the years due to 
the difference in numbers between the retirement_titles.csv and the unique_titles.csv.
- The actual number of employees retiring can be seen through the retiring_titles.csv where the sum of the entries equals the sum of the entries within the unique_titles.csv.
- Even though there are many retiring from various positions, there are only 1,549 employees eligible for a mentorship program.

## Summary
Based on the analysis, it shows that there are not enough employees to fill in the gap that will be made from the retiring employees.  
The company will be left with 70,909 empty positions if all those eligible for the mentorship program were to fill in the gap.
  
## Challenge Overview
This analysis was challenging in that it was more of a conceptual matter when finding connections between the tables in SQL as well as using the primary keys to make new tables.
