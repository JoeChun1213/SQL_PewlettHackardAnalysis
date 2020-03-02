# Pewlett-Hackard-Analysis
### Module 7

## Challenge Overview
By filtering, sorting and creating new tables, I created lists of candidates for mentorship using different queries and joins.

## Challenge Summary  

### Number of [titles] Retiring  
<img src="/Challenge/Pictures/Number_of_[titles]_Retiring.png"
     style="float: left; margin-right: 10px;"
     width="310"/> <img src="/Challenge/Pictures/Number_of_[titles]_Retiring_Output.png"
     style="float: left; margin-right: 40px;"
     width="500"/>  
<br/>
We were instructed to create a new table using a RIGHT JOIN that contains Employee number, First and last name, Title, from_date, and Salary. Then, export the data as a CSV. To create the new list of potential mentors, we created a query that returns a list of current employees eligible for retirement, as well as their most recent titles.  
<br/>
<br/>
<br/>
### Only the Most Recent Titles
<img src="/CHALLENGE/pics%20of%20code/only_the_most_recent_titles.png"
     alt="Home Screen"
     style="float: left; margin-right: 10px;"
     width="400"/> <img src="/CHALLENGE/pics%20of%20output/only_the_most_recent_excel.png"
     alt="Home Screen"
     style="float: left; margin-right: 40px;"
     width="332"/>    
<br/>
Here, we were instructed to list the frequency count of emplyee titles in decending order. To get the final list with the recent titles, we partition the data so that each employee is only included on the list once. In addition, we performed a query that shows how many current employees of each title are presently eligible for retirement.    
<br/>     
<br/>
<br/> 
### Who’s Ready for a Mentor?
<img src="/CHALLENGE/pics%20of%20code/whos_ready_for_a_mentor.png"
     alt="Home Screen"
     style="float: left; margin-right: 10px;"
     width="390"/> <img src="/CHALLENGE/pics%20of%20output/whos_ready_for_a_mentor_excel.png"
     alt="Home Screen"
     style="float: left; margin-right: 40px;"
     width="455"/>
<br/>
To find who's ready for a mentor, we created a new table. The birth date was set to be between January 1, 1965 and December 31, 1965. Also, we made sure only current employees were included in this list. The final query returns the potential mentor’s employee number, first and last name, their title, birth date and employment dates.
