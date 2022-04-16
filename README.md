# School District Analysis

## Overview of the School District Analysis:
In this analysis we are using two CSV files to help analysis student and school data for Maria and the school board. The below shows the results for the Thomas High School data have adjusting for null values. 
## Resuts of School District Analysis:
The below is broken out by bullet points.
***
* How is the district summary affected?
    The number of NaN values need to be removed from the entire data sample to complete the percentage that does not include those test scores. 
* How is the school summary affected?
    Fortunately, for Maria the school summary is very much unchanged. The other data methods can still be used for the remainder of the schools. 
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    Once replacing the math and reading scores of the dishonest students, the data shows that Thomas High School performs very while when comparing vs the other schools. The average test scores are in line with the other schools. 
* How does replacing the ninth-grade scores affect the following:
    * Math and reading scores by grade
    The underlying averages are not that much different with the test scores being in middle of the range. 
    * Scores by school spending
    The school spending was unchanged and stayed the same. 
    * Scores by school size
    Same with the previous bullet, the changes are the same. 
    * Scores by school type
    Schools by type are unchanged. 

### Summary:
* The total number of students used to calculate the average test scores and passing percentage was adjusted for the cheating students in 9th grade at Thomas High School.
* We included a **.loc** function that was used on teh per school summary to insert changes that were needed without causing isuses with the other data. 
* Code that was added to help pull the averages for the remaining population once we removed the other students that had NaN. 
* Put the data together that calculated the data by average type which was Charter or District.
###
![](school_type.png)
