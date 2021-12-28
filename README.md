## Project Summary
By filtering, sorting and creating new tables, I created lists of candidates for mentorship using different queries and joins.

## ERD.png
<img src="/Challenge/Pictures/ERD.png"
     alt="Home Screen"
     style="float: left; margin-right: 10px;"
     width="310"/>
<br/>
## Challenge Summary  
### Number of [titles] Retiring  
<img src="/Challenge/Pictures/number_of_titles.png"
     alt="Home Screen"
     style="float: left; margin-right: 10px;"
     width="310"/> <img src="/Challenge/Pictures/number_of_titles_output.png"
     alt="Home Screen"
     style="float: left; margin-right: 40px;"
     width="500"/>  

Created the table which contains employee #, name, title, from date, and salary using right join command. Exported the table into a csv file. In addtion, created a query which would return a list of current employees could be retired and their most recent titles to find out new potential mentors. 


### Only the Most Recent Titles
<img src="/Challenge/Pictures/most_recent_titles_only.png"
     alt="Home Screen"
     style="float: left; margin-right: 10px;"
     width="400"/> <img src="/Challenge/Pictures/most_recent_titles_only_output.png"
     alt="Home Screen"
     style="float: left; margin-right: 40px;"
     width="332"/>    

Listed the count of employee titles in descending order. Made partitions in the data to make sure there will be no duplicates and to reach the final list with the most recent titles. Using query that would return how many current employees of each title are eligible for retirement.  
  
  

### Who’s Ready for a Mentor?
<img src="/Challenge/Pictures/ready_for_mentor.png"
     alt="Home Screen"
     style="float: left; margin-right: 10px;"
     width="390"/> <img src="/Challenge/Pictures/ready_for_mentor_output.png"
     alt="Home Screen"
     style="float: left; margin-right: 40px;"
     width="455"/>
<br/>
<br/>
<br/>
Set up birth date from 01/01/1965 to 12/31/1965 and found employees who would be ready for a mentorship;created a new table. Only current employees were included. Using the final query to reach the data contains potential mentor's employee #, name, title, birth date, and employement date. 
