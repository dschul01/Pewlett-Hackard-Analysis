# Pewlett-Hackard_Analysis
Analysis of HR data utilizing Postgres and pgAdmin


## Overview of Pewlett-Hackard Analysis
The purpose of this project is to utilize Postgres and pgAdmin to update Pewlett-Hackard's (PH) HR data environment into a SQL database from previously maintained Excel files.   An Entity Relationship Diagram (ERD) was used to create and document the new database as seen below.  After which, SQL queries were developed to pull some critical employee data PH is needing; employees reaching retirement by title and eligible employees to participate in a mentorship program.  The final analysis of the data provides impacts from the high volumes of soon-to-be retirees. 

![EmployeesDB.png](https://github.com/dschul01/Pewlett-Hackard-Analysis/blob/main/EmployeesDB.png)


## Results
PH is needing to know the number of retiring employees per title as well as tenured employees eligibile to participate for a mentorship program.  Potential retirees were determined by querying unique active employees born between 1/1/1952 and 12/31/1955 while the pool of mentorship program participants were based on those born in 1965.  The following was determined from those queries:
1) There are 72,458 or 32% of PH employees who are approaching retirement age. 
2) The breakout of retirees by title is provided below.  PH needs to assess workload to determine if remaining employees can maintain current levels and cost/benefit of increasing workload.
	
<img src="https://github.com/dschul01/Pewlett-Hackard-Analysis/blob/main/Retiring_Title.png" width="200" height="200">
3) There are 1,549 employees who meet the mentorship eligibility parameters.  Breakdown by job title is provided below.

<img src="https://github.com/dschul01/Pewlett-Hackard-Analysis/blob/main/Mentorship_Eligible.png" width="200" height="200">
4) PH should look at expanding eligibility for the mentorship program as there are only 2% (1,549 eligible compared to 72,458 retirees) of retiring employees which meet the current criteria.


## Summary
PH is facing a significant volume of 72,458 retirees in the coming years as illustrated above.  The company needs to assess workload and other factors before determining if all retirees should be replaced.  The table below shows non-retirees outnumber retirees 2.3 : 1 per title.  It's possible the remaining workforce can keep up with the current workload, but deeper analysis is necessary.


<img src="https://github.com/dschul01/Pewlett-Hackard-Analysis/blob/main/Ratio_Title.png" width="600" height="200">

PH should think about expanding its criteria for qualified retirement-ready employees to mentor the next generation of employees.  There are only 1,549 eligible using their current criteria.  Expanding the birthdate range by one year to include 1964 increases the eligibility pool from 1,549 to 19,905.  SQL code is provided to show the impact of adding one year to the mentorship criteria.

<img src="https://github.com/dschul01/Pewlett-Hackard-Analysis/blob/main/Expanded_Mentorship_Criteria.png" width="400" height="400">
