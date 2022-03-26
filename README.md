# School_District_Analysis.

## Overview of Project 
* We are helping Maria, who works for The City School System, prepare all standardized test scores and funding data for analysis. The data has the Math and Reading scores for each student at every school in the city school system. 

* Before starting the project, I replace the ninth-grade reading and math scores with "NAN = not a number" so they wouldn't affect the final results because there was evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth-graders appear to have been altered. 

## Results 
### District Summary 
* Below is a screenshot of the results before the 9th grader's scores were replaced 
![data-4-7-7-bug-1158](https://user-images.githubusercontent.com/100107588/160216959-7f734a09-440b-4fa6-bb05-a36cfaab0bfc.png)

* Below is a screenshot of the results after the 9th grader's scores were replaced 
<img width="529" alt="Screen Shot 2022-03-25 at 8 22 21 PM" src="https://user-images.githubusercontent.com/100107588/160216968-46520b93-8e0e-4a39-8295-34fcff34d163.png">

* As you can see, there was no major change in the averages and percentages after replacing the 9th grader's scores with NAN. The averages stayed the same when we round them and % lowered around .1 after the replacement. 

### School Summary
* Below is a screenshot of the results before the 9th grader's scores were replace 
<img width="806" alt="Screen Shot 2022-03-25 at 8 41 04 PM" src="https://user-images.githubusercontent.com/100107588/160217675-d0925713-ae74-4588-adaa-beccc5d44b1a.png">

* Below is a screenshot of the results after the 9th grader's scores were replaced 
<img width="1000" alt="THS_summary_dataframe" src="https://user-images.githubusercontent.com/100107588/160217246-8465545f-e965-48cb-98a1-f8c6c69f777f.png">

* All three percentages went down significantly from the 90's % to the 60's %. This shows how much 9th graders' scores influenced the percentages. Without the 9th grader's scores, the school is at the bottom for both math and reading % compared to the other schools 
 

### Math and Reading Scores 
* The scores' absence affected the average reading and math score for the 9th-grade group. We cannot compare their performance to other 9th graders from other schools because we don't have the data. The school was not able to get into the top 5 due to that absence 

### Scores by School Spending
* For the scores by school spending, the numbers didn't change at all once they were rounded up. Thomas High School fell into the $631-645 range. 
 
* Below is a screenshot of the results before the 9th grader's scores were replace 
<img width="805" alt="Screen Shot 2022-03-25 at 8 59 28 PM" src="https://user-images.githubusercontent.com/100107588/160218336-25c96318-7f22-4375-8e99-8c8cc458fc0c.png">

* Below is a screenshot of the results after the 9th grader's scores were replaced  
<img width="532" alt="Screen Shot 2022-03-25 at 8 59 57 PM" src="https://user-images.githubusercontent.com/100107588/160218369-631129f9-5623-4543-9b94-457f401410b3.png">

### Scores by School Size 
* The same situation happened with school size, Thomas High School fell into the Medium reange,  and once the numbers were rounded up there was no difference. They were off by a few decimal places 

### Scores by School Type 
* The same situation happened with school type, Thomas High School fell into the Charter Type,  and once the numbers were rounded up there was no difference. They were off by a few decimal places 

## Summary 
* Without removing the 9th grade population from the Thomas High School anlaysis, the percentages go down significantly. 
* In order to get a better sense of their performance, we only considered the school's 10th to 12th student population. 
* The math and reading percentage went up when we removed the 9th graders' population.
* The results demonstrates that the other grades are doing decently compared to the other schools. 
