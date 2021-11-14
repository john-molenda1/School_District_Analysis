# School_District_Analysis

## Project Overview
The purpose of this analysis was because Maria and her supervisor at the school board suspected academic dishonesty surrounding reading and math scores for 9th graders at Thomas High School. We initially ran an analysis for the district for all students, to determine average math, reading, and overall passing scores for every school, grade (9th - 12th), and category of school (charter or district). Then, we replaced all the math and reading scores from 9th graders at Thomas High School with null values to check for academic dishonest and ran the results again to see if there was a difference in the two datasets. 

## Analysis 
The following section describes how individual sections of our code were affected by the removal of 9th grade math & reading scores at Thomas High School

### District Summary 
The district summary was changed slightly in the fact that the average math score decreased by .04% (from 78.985% 78.931%) and average reading score decreased from 81.878% to 81.856%. Overall, there were a minor decrease in percentage of students who passed math as 74.98% of students had passed math before the data refactoring, whereas 74.76% passed math in the district with the removal of the 9th grade THS students. The percentae of students who passed reading saw a similar minor decrease from 85.81% passing to 85.66%. Obviously, with both the percentage of studings passing either math or reading, the overall percentage of students who were passing both declined from 65.17% to 64.86%
### School Summary
Simiarly to the district summary, the school summary dataframe saw only minor changes. However, these changes were more noticeable due to the fact that Thomas High School saw roughly 1/4 of its students test grades get removed with null values, while it was comparitively only a miniscule fraction of the district's total number of student test scores.

Average math scores at Thomas dropped from 83.42% to 83.35%. Interestingly enough, average reading scores saw an ever so slight increase from 83.85% to 83.90%

**With all scores included
![image](https://user-images.githubusercontent.com/92773195/141668095-52d6c93d-d17a-48a0-825f-e594fc2c5330.png)

**With 9th grade scores removed
![image](https://user-images.githubusercontent.com/92773195/141668111-10e4ddc7-441f-4409-af31-a5426fbabf2c.png)

### Thomas High School Performance

### Score Statistics
* Math & Reading Scores by Grade

* Scores by school spending

* Scores by school size

* Scores by school type



## Summary

