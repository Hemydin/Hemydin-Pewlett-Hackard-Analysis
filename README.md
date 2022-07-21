## Pewlett Hackard Analysis
### Project Summary
In this challenge, I help Pewlett Hackard future-proof the company. Because many employees soon come to retirement age, Bobby's manager has requested to determine the number of retiring employees grouped by their titles and identify the eligible employees to participate in a mentorship program. To prepare these lists, I build the queries in SQL using filters, joins, and functions.
### Results
#### The Number of Retiring Employees by Title.
To retrieve the number of employees by their most recent job title who are about to retire, I prepared the following tables: 
* The Retirement Titles table holds all the titles of employees born between January 1, 1952, and December 31, 1955.
![1](https://user-images.githubusercontent.com/100629325/180325707-f3a632f5-ea18-40d4-9129-adbd765e6ee0.png)
* Because some employees held multiple titles throughout their employment with a company, I created the Unique Titles table containing each employee's most recent title. 
![2](https://user-images.githubusercontent.com/100629325/180326134-370ce4f1-74a8-4994-b511-4cff7a704fbf.png)
* Finally, using the COUNT function, I created the Retiring Titles table with the number of retirement-age employees by most recent job title.

![3](https://user-images.githubusercontent.com/100629325/180326246-b18f22e9-f180-4171-99b0-08911bb86722.png)

