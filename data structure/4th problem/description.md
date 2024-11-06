# Department Query Problem

Write a query that outputs the following information about departments (name each printed column as indicated):

- `department_name` - the name of the department
- `emp_cnt` - the number of employees working in this department. If no one works in the department, print N/A
- `job_cnt` - the number of different positions in this department. If no positions exist under the department, print N/A
- `sum_sal` - the total salary in this department. If NULL, print N/A (0.75 points)
- `sum_min_max` - the sum of the minimum and maximum salaries in this department. If NULL, print N/A
- `phone_numbers` - the number of employees in this department whose phone number's first two digits' product is greater than the sum of the last two digits

Exclude departments with names containing two or more words. Words are separated by spaces, and there may be more than one space between words. For example, if the department name is "A," this department is within our area of interest, but if the department name is "A B," it should be excluded

Also, exclude departments where the `COUNTRY_ID` does not match the beginning of `COUNTRY_NAME`. Character case should be ignored

Sort the data by `COUNTRY_ID` in ascending order and then by `COUNTRY_NAME` in descending order
