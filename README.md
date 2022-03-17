# School Analysis

## Overview of District Analysis
The purpose of this analysis is to modify the results of a district-wide analysis based on previously reported standardized test scores from 15 schools. The reason for this modification is suspected academic dishonesty related to the math and reading scores for ninth graders at one particular high school: Thomas High School (THS).

## Results
The below section addresses the results of the original analysis compared to the revised results:

### District Summary
The district summary results show very minor changes to the math and reading scores as a result of removing the ninth grade scores.
- Initially, average math and reading scores were 79.0 and 81.9, respectively. After removing the questionable scores, the average math score dropped slightly to 78.9 while the average reading score stayed the same. 
- Similarly, the percentage of students passing (scores 70 and above) showed very minor decreases from the original results to the revised ones.

**Original District Summary**
![Original District Summary](https://user-images.githubusercontent.com/99286327/158854980-9ced9e6d-16d4-4bc1-a253-e36d02f87099.png)

**Revised District Summary**
![Revised District Summary](https://user-images.githubusercontent.com/99286327/158854987-1b2f9a18-3fdf-4302-8a6d-fd27943f9957.png)

### School Summary
Changes to the overall school summary are more difficult to see after the removal of 461 scores of ninth graders from THS. This analysis only dropped the scores of these students, but did not remove them entirely from the dataset. Since school budgets were approved before the students underwent standardized testing, it would be erroneous to remove the ninth graders from the rest of the school summary (for example: spending per capita). 

Looking at all 15 high schools in one table without any conditional formatting makes spotting changes to the overall school summary difficult (see below). However, the following sections will address the results at a more granular level.

![Screen Shot 2022-03-17 at 12 17 48 PM](https://user-images.githubusercontent.com/99286327/158857517-c9df8487-9b36-4474-a92b-6cc85ff7207b.png)

### Relative Performance of Schools
After removing the suspected scores, we see that THS is still the second highest performing school in the district. Again, while we see minor changes across the average scores and percentage of students passing, the revised analysis does not show large swings in the data. See below comparisons:

**Original Top Schools**
![Original Top Schools](https://user-images.githubusercontent.com/99286327/158854981-34f42a13-677c-416e-a390-ff7db8d31f2f.png)


**Revised Top Schools**
![Revised Top Schools](https://user-images.githubusercontent.com/99286327/158854990-b1c8a6fe-53cf-4763-89d7-79a1defc7eb2.png)

The biggest take-away after removing the math and reading scores for the 9th graders at THS shows little proof that the scores were subject to academic dishonesty relative to other schools. If the 9th grade scores were indeed dishonest, one would expect to see the revised results for THS drop more significantly since cheating/dishonesty should have been inflating the scores more dramatically. However, we are only seeing minor changes after removing almost 30% of the students at THS, implying that the depth of dishonesty is fairly limited, if it exists at all.


### Thomas High School's Performance
We can also look at THS' performance before the 9th grade scores were replaced and afterwards and review the impact:

1. Math and reading scores by grade: no impact. Average math and reading scores for all other grades remained the same. Only THS ninth grade indicates no data provided. Screenshots for average math score by grade provided below. The same is true for reading scores.

**Original:**
![Original Average Math](https://user-images.githubusercontent.com/99286327/158854975-82fbbd87-aeb3-41bc-9c37-860deb190175.png)
  
**Revised:**
![Revised Average Math](https://user-images.githubusercontent.com/99286327/158854983-3fa9aaf4-c1d4-45c7-b710-5c36b3c9006d.png)
  
2. Scores by school spending: no impact. THS spent $638.00 per student and if there were any noticeable differences prior to the removal of scores, we'd expect to see changes in the bin for $630-644, however, the results remained the same.
![Spending Per Capita](https://user-images.githubusercontent.com/99286327/158854997-dcfcbd62-f280-4c4a-b17b-8985d76cc312.png)

3. Scores by school size: no impact. Grouping by school size showed no change between the original analysis and the revised analysis.
![School Size](https://user-images.githubusercontent.com/99286327/158859460-244330b8-7aaa-485c-a089-e782d9b44780.png)
  
4. Scores by school type: no impact. There was no change to the scores or percentage of students passing in the original analysis versus the revised analysis.


![School Type](https://user-images.githubusercontent.com/99286327/158854993-4911d908-9f5e-419c-ba47-1f936d482513.png)

## Summary
There were four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School were replaced with NaNs. After removing the scores of 461 ninth graders at THS, the four changes were:
1. The district's average math score dropped from 79.0 to 78.9.
2. The percentage of students who passed reading dropped from 85.8% to 85.7%.
3. The percentage of students who passed math dropped from 75.0% to 74.8%.
4. The percentage of students who passed overall (math AND reading) dropped from 65.2% to 64.9%.

Once again, the changes we see in the revised analysis compared to the original analysis reveal very minor changes and indicate the fear of widespread academic dishonesty is likely unfounded.


