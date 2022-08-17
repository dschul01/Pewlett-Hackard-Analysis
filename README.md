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
3)

4)


Provide a bulleted list with four major points from the two analysis deliverables. Use images as support where needed.

## Summary


<img src="https://github.com/dschul01/Pewlett-Hackard-Analysis/blob/main/Non_Retiring_Title.png" width="200" height="200">

<img src="https://github.com/dschul01/Pewlett-Hackard-Analysis/blob/main/Ratio_Title.png" width="500" height="200">


Provide high-level responses to the following questions, then provide two additional queries or tables that may provide more insight into the upcoming "silver tsunami."

How many roles will need to be filled as the "silver tsunami" begins to make an impact?

Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?