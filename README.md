# School_District_Analysis

## Project Overview
The purpose of this analysis was because Maria and her supervisor at the school board suspected academic dishonesty surrounding reading and math scores for 9th graders at Thomas High School. We initially ran an analysis for the district for all students, to determine average math, reading, and overall passing scores for every school, grade (9th - 12th), and category of school (charter or district). Then, we replaced all the math and reading scores from 9th graders at Thomas High School with null values to check for academic dishonest and ran the results again to see if there was a difference in the two datasets. 

## Analysis 
The following section describes how individual sections of our code were affected by the removal of 9th grade math & reading scores at Thomas High School

### District Summary 
The district summary was changed slightly in the fact that the average math score decreased by .04% (from 78.985% 78.931%) and average reading score decreased from 81.878% to 81.856%. Overall, there were a minor decrease in percentage of students who passed math as 74.98% of students had passed math before the data refactoring, whereas 74.76% passed math in the district with the removal of the 9th grade THS students. The percentae of students who passed reading saw a similar minor decrease from 85.81% passing to 85.66%. Obviously, with both the percentage of studings passing either math or reading, the overall percentage of students who were passing both declined from 65.17% to 64.86%

**With all scores included
![image](https://user-images.githubusercontent.com/92773195/141694662-9d6ef3c3-c7ac-41e2-847d-1d28e1f9024c.png)


**With 9th grade scores removed
![image](https://user-images.githubusercontent.com/92773195/141694641-5a07adae-0140-4ac6-805d-b399e08aaae2.png)

### School Summary
The school summary changes were more noticeable due to the fact that Thomas High School saw roughly 1/4 of its students test grades get removed with null values, while it was comparitively only a miniscule fraction of the district's total number of student test scores.

Average math scores at Thomas dropped from 83.42% to 83.35%. Interestingly enough, average reading scores saw an ever so slight increase from 83.85% to 83.90%. However, while the average scores saw little change with the removal of the 9th graders at Thomas, there was a significant shift in the total percentage of students passing math, reading, and overall pass rates. When all students were included in the dataframe at Thomas, 93.27% were passing math, 97.31% were passing reading, and 90.95% of students were passing both. However, once we removed the 9th graders from the data, those scores plummted to 66.91%, 69.66%, and 65.08%, respectively.

**With all scores included
![image](https://user-images.githubusercontent.com/92773195/141668095-52d6c93d-d17a-48a0-825f-e594fc2c5330.png)

**With 9th grade scores removed
![image](https://user-images.githubusercontent.com/92773195/141668111-10e4ddc7-441f-4409-af31-a5426fbabf2c.png)

### Thomas High School Performance
Before the 9th grade scores were removed, Thomas High School ranked 2nd in overall pass percentage with 90.95% of students passing both reading and math. However, Thomas's overall percentage of overall students passing became average at best after the removal with only 65.08% of all 10th - 12th graders passing. 
![image](https://user-images.githubusercontent.com/92773195/141695682-e90f212c-0bef-4b17-9f94-d5182d9041e6.png)

### Score Statistics
* Math & Reading Scores by Grade
![image](https://user-images.githubusercontent.com/92773195/141695150-8ac35c86-83f5-462a-8c90-603bcf310ded.png)
![image](https://user-images.githubusercontent.com/92773195/141695157-64bdd40d-3a62-4357-9a25-4da9fc61b07b.png)
![image](https://user-images.githubusercontent.com/92773195/141695187-c48d3a65-5859-4c1b-bb3d-68b39c3f93b7.png)
![image](https://user-images.githubusercontent.com/92773195/141695232-a9bd67f3-bb3b-4383-ad36-9ccabc1a3c67.png)

The only real difference in the math and reading scores by grade is that with the refactored code, we see null values in place of the scores for both sections at Thomas because we've removed their scores from consideration. 

* Scores by school spending
The only minor changes in school spending scores were in the $630-644 bin. before the 9th graders at Thomas score removal, 73.48% were passing math, 84.39% were passing reading, and 62.86% were passing both. After their removal, these scores became 73.46%, 84.32%, and 62.78%, respectively. 

![image](https://user-images.githubusercontent.com/92773195/141695659-9f7588a4-8edf-412c-b378-755a7d805406.png)
![image](https://user-images.githubusercontent.com/92773195/141695665-3a56245e-52f3-4fb9-8a04-117801685fd9.png)


* Scores by school size
![image](https://user-images.githubusercontent.com/92773195/141695735-df45899c-dceb-4ca9-aaa7-19066f405bad.png)
![image](https://user-images.githubusercontent.com/92773195/141695745-039b284d-e00b-4f07-8360-44c6428e6f87.png)

The only changes in the school size data were marginal at most and saw only changes to several hunderdths of a percentage in all of the scores. The only bin being affected was the Medium (1000-2000) bin
* Scores by school type
*9th grade scores at Thomas removed
![image](https://user-images.githubusercontent.com/92773195/141695780-626249e4-13fa-443c-8093-03e36ba0e4fb.png)

* All scores included
![image](https://user-images.githubusercontent.com/92773195/141695804-d779e98f-d213-4df4-840b-62dcc0500a81.png)

With Thomas being a charter high school, it stands to reason that the only bin we would see changes in would be the charter schools, with the data having only been minorly impacted. 


## Summary
### Changes in the data due to the removal of Thomas High School 9th Grade Reading & Math Scores
1) Compared to other high schools, Thomas did not perform as well in the overall passing percentage metric with the removal of the 9th graders
2) The percentage of students passing, math, reading, and overall pass percentages dipped slightly when these scores were removed
3) The performance based on school spending saw a minor dip for scores in the $630-644 range  
4) The performance based on school size saw a similar minor drop in performance among medium sized schools 
