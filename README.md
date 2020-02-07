# Student-Admission-Tracking

**Previously:** Admissions and Student Opportunities (ASO) team has used Google Sheets to
share and update how many student applications have been submitted in order to inform 
recruiting efforts in certain school districts and grades. Someone would go into the student
database and manually search for how many applications were submitted by site and grade and
then input these numbers into Google Sheet cells.

Each Site would have a table like this:

| Grade			|New App Target | Submitted Apps |Apps Needed	 |
| :-----------: |:-------------:| :-------------:|:-------------:|
| 6th	        | 25		    | 	13	 		 |	 12	 		 |
| 7th	        | 15	        |   5	 		 |   10			 |
| 8th		    | 10	        |   7	 		 |    3	 		 |
| 9th		    | 10	        |   8	 		 |    2			 |

**Purpose:** Create script to automate the daily searching tasks that ASO needs to make recruiting
decisions during application season. Will save results to a PDF located in the user's Desktop folder.