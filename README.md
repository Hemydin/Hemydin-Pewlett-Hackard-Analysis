## Pewlett Hackard Analysis
### Project Overview:
In this challenge, I help Pewlett Hackard future-proof the company. Because many employees soon come to retirement age, Bobby's manager has requested to determine the number of retiring employees grouped by their titles and identify the eligible employees to participate in a mentorship program. To prepare these lists, I build the queries in SQL using filters, joins, and functions.
### Results:
#### Deliverable 1: The Number of Retiring Employees by Title
To retrieve the number of employees by their most recent job title who are about to retire, I prepared the following tables: 
* The Retirement Titles table holds all the titles of employees born between January 1, 1952, and December 31, 1955.

![1](https://user-images.githubusercontent.com/100629325/180325707-f3a632f5-ea18-40d4-9129-adbd765e6ee0.png)
* Because some employees held multiple titles throughout their employment with a company, I created the Unique Titles table containing each employee's most recent title.

![2](https://user-images.githubusercontent.com/100629325/180326134-370ce4f1-74a8-4994-b511-4cff7a704fbf.png)
* Finally, using the COUNT function, I created the Retiring Titles table with the number of retirement-age employees by most recent job title.

![3](https://user-images.githubusercontent.com/100629325/180326246-b18f22e9-f180-4171-99b0-08911bb86722.png)
#### Deliverable 2: The Employees Eligible for the Mentorship Program
The Mentorship Eligibility table holds the current employees who are eligible to participate in a mentorship program.

![4](https://user-images.githubusercontent.com/100629325/180326992-6a82a9f3-11f9-44b0-b3c7-d2fe1bddbd6e.png)
### Summary:
* How many roles will need to be filled as the "silver tsunami" begins to make an impact?
    * There are 72,458 current employees eligible to retire within a short period.

![5](https://user-images.githubusercontent.com/100629325/180327913-a0500787-14a0-4eb9-8e37-32819d654565.png)
* Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
    * 1,549 retirement-ready employees qualify for a mentorship role which is not nearly enough to replace retired employees.

![6](https://user-images.githubusercontent.com/100629325/180328808-c9528f46-eb8f-4e2c-9b83-1ea832b2f0c4.png)
