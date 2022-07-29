# Pewlett-Hackard-Analysis

## Project Overview
Pewlett-Hackard is a large company boasting several thousand employees and it's been around for a long time. As baby boomers begin to retire at a rapid rate Pewlett-Hackard is looking toward the future in two ways. First, it's offering a retirement package for those who meet certain criteria. Second, it's starting to think about which positions will need to be filled in the near future. The number of upcoming retirements will leave thousands of job openings. Bobby is an up and coming HR Analyst whose task is to preform employee research. Specifically, he needs to find answers to the following questions, Who will be retiringin the next few years, and how many positions will Pewlett-Hackard need to fill? This analysis will help future-proof Pewlett-Hackard by generating a list of all employees eligible for the retirement package. The employee data Bobby needs is only available in the form of six CSV files because Pewlett-Hackard has been mainly using Excel and VBA to work with their data, but now they've finally decided to update their methods and instead use SQL. Your task is to help Bobby build an employee database with SQL by applying your data modeling, engineering and analysis skills. 

## Resources
- Data Source: departments.csv, dept_emp.csv, dept_manager.csv, employees.csv, salaries.csv, titles.csv
- Software: PostgreSQL 11.16, pgAdmin 4

## Challenge Overview

Now that Bobby has proven his SQL chops, his manager has given both of you two more assignments: determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program. Then, you’ll write a report that summarizes your analysis and helps prepare Bobby’s manager for the “silver tsunami” as many current employees reach retirement age.

#### Results
From the analysis of the employees that are close to retirement it is found that:

1) The majority of retiring employees hold the titles of Senior Engineer or Senior Staff

<p align="center">
Retiring Emploees by Title
</p>

<p align="center">  
<img src="https://github.com/mcgibbenyd1/Pewlett-Hackard-Analysis/blob/main/Tables_Pictures/Retiring_Titles.png" width="35%"/>
</p>

2) With number of senior positions retiring then they will have many promotions into those senior roles creating a younger and possibly inexperienced company

3) Employees born in 1965 are eligible to participate in a mentorship program. With the majority of job titles covered for the retirees so the handoff of knowledge is possible. 

<p align="center">
Eligible Employees for Mentorship Program
</p>

<p align="center">  
<img src="https://github.com/mcgibbenyd1/Pewlett-Hackard-Analysis/blob/main/Tables_Pictures/Retiring_Mentors_Titles.png" width="35%"/>
</p>

4) There are two Managers retiring whose role will need to be replaced 

## Summary
- How many roles will need to be filled as the "silver tsunami" begins to make an impact?

<p align="center">
Number of roles needing to be replaced for the retiring employees. 
</p>

<p align="center">  
<img src="https://github.com/mcgibbenyd1/Pewlett-Hackard-Analysis/blob/main/Tables_Pictures/Replacement_roles.png" width="20%"/>
</p>

- Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?

<p align="center">
Number of roles needing to be replaced for the retiring employees. 
</p>

<p align="center">  
<img src="https://github.com/mcgibbenyd1/Pewlett-Hackard-Analysis/blob/main/Tables_Pictures/Replacement_roles.png" width="35%"/>
</p>
