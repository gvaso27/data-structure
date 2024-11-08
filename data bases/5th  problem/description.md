# Job Position Query Problem

Write a query that outputs the following information about job positions (name each printed column as indicated):

- `job_id` - the ID of the position
- `name` - the name of the position
- `emp_cnt` - the number of employees working in this position with an odd `EMPLOYEE_ID`. If zero, print N/A
- `avg_sal` - the average salary of employees with an even `EMPLOYEE_ID` in this position. If zero, print N/A
- `mx_cnt` - the number of employees with the maximum salary in this position. If zero, print N/A

Exclude positions where the ID is less than 4 characters

Also, exclude positions where the difference between `MAX_SALARY` and `MIN_SALARY` is the greatest.

Sort the data by position ID as follows: first, show records where the position ID contains the word "IT," followed by all other records sorted alphabetically
