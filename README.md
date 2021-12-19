# Pewlett-Hackard-Analysis
# 1.Overview of the analysis:
well in this project am gonna help Bobby to analyiz and convert the data of the  Pewlett Hackard company employees from CSV files and VBA files using SQL and determine how many employees gonna retired? and how many job position gonna need to be coverd ?now we gonna do that using:

a.Postgres:Database system for holsing the data that we gonna analyiz.

b.Pgadmin:interface that talks to Postgres.

c.ERD's :entity relationships diagram.

d.Quick DBD:quick database diagram creating.

# 2.Results:
so after doing the reserch and analyiz all the given data we got the most important four tables :
# 2.a. retirment titles:
which provide us with the information of the employees with birth date between 1952-1955 with their title and (first name ,last name)as showed in the code using the "FROM * TABLE" method 

![this is picture](https://github.com/Farah86/Pewlett-Hackard-Analysis/blob/main/hackars%20png's/retirment_title.png)

and this is what the table show us:
![this is picture](https://github.com/Farah86/Pewlett-Hackard-Analysis/blob/main/hackars%20png's/retirment%20_title_table.png)

# 2.b.unique titles : 
which show us the ascending order by the employee number and descending order by the last date as shown in the code below using the DISTINCT ON statement to retrieve the first occurrence of the employee number

![this is picture](https://github.com/Farah86/Pewlett-Hackard-Analysis/blob/main/hackars%20png's/unique_title.png)

and this is the result table that we got:

![this is picture](https://github.com/Farah86/Pewlett-Hackard-Analysis/blob/main/hackars%20png's/unique_title%20table.png)

# 2.c.Retiring Titles:
which help us find the number of employees retiring with specific titles as shown in the code below:

![this is picture](https://github.com/Farah86/Pewlett-Hackard-Analysis/blob/main/hackars%20png's/retiring_title_code.png)

give us the following result wth the count of each specific title for the employees :

![this is picture](https://github.com/Farah86/Pewlett-Hackard-Analysis/blob/main/hackars%20png's/retiring_title.png)

# 2.d.mentorship_eligibilty:
which we Filtered the data on the to_date column to all the current employees, then we filtered the data on the birth_date columns to get all the employees whose birth dates are between January 1, 1965 and December 31, 1965.and Order the table by the employee number as shown in the code below:

![this is picture](https://github.com/Farah86/Pewlett-Hackard-Analysis/blob/main/hackars%20png's/mentorship_elegibelity.png)

which show us the following results table:

![this is picture](https://github.com/Farah86/Pewlett-Hackard-Analysis/blob/main/hackars%20png's/metorship_table.png)


# 3.Summary: 
 from the mentorship_eligibility table and the retiring_titles table we can find out all of the employees who are retiring by title and are eligible for he mentorship program,and as the upcoming "silver tsunami" start to impact on Pewlett Hackard me and Bobby created  tables to determine the count of the employees who will be retiring in a table called retireing_titles_still_working. the total number of employees retiring comes out to 72,458 as shown in the code below:
 
 ![this is picture](https://github.com/Farah86/Pewlett-Hackard-Analysis/blob/main/hackars%20png's/retiring_people_still_working.png)
 
 and with the information that we got from the table employees_currently_working with total of 240,124 employee in Peweltt hackard show us that about more than 25% of the employee will be retiring soon so it would be a lot of opining posotions in Pewlett-Hackard that gonna effect them especially with the Silver Tsunami set to hit soon. The Mentoring Program however allows retiring employees to work in a capacity where they will be working part-time hours to help mentor new employees. This would make the new employees life easier to start in the company , which after all the search and the data that we found it gonna be easier to select the right people for the opening positions.
 
 








