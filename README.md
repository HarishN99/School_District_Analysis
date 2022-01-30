# School_District_Analysis

## Analysis Overview

Purpose: This analysis was intended to investigate the academic dishonesty claims made by the school board which found that the reading and math grades for Thomas High School (THS) 9th graders appear to have been altered. For the analysis, THS 9th grade reading and math scores were replaced with NaNs as to compare with a previous analysis which included 9th grade data. This was done to determine whether including the THS 9th grader data changes the results drastically; the follwoing criteria were observed in both analysis:

- Top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score received by students in each grade level at each school
- The average reading score received by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size 
- School performance based on the type of school


## Results
### How is District Summary Affected?

![Original District Summary](https://user-images.githubusercontent.com/94864663/151683399-5ef2b41b-8889-4072-ac75-ab83561d4382.png)
 
 Table 1. Original District Summary

![Adj District Summary](https://user-images.githubusercontent.com/94864663/151683575-a4f41571-5619-431f-8a55-b8949f833961.png)
 
 Table 2. Adjusted District Summary

Comparing the data between the two, the average math score drops from 79.0 to 78.9 after the data from the 9th graders at THS is omitted. This means there was only a difference of 0.1 in average math scores between the original and adjusted district summary. The average reading score is relatively unchanged remaining at 81.9. About 75% of the students in the original analysis were passing math and 86% were passing reading and about 65% were passing overall. Omitting the THS 9th graders, 74.8% of students were passing Math, 85.7% passing reading, and 64.9%. Therefore, in most cases removing the 9th graders at THS does contribute to a very small decrease in scores. 

It is important to note that the “Total Students” column does not appear to change because the count was based on student ID rather than the actual data, therefore the 9th graders at THS were still counted in the total students column but their score data was not included in the adjusted analysis. 


### How is School Summary Affected?

![Original School Summary](https://user-images.githubusercontent.com/94864663/151683407-e84b4d9d-6509-4df3-834d-023d10e59960.png)
Table 3. Original School Summary


![Adj School Summary](https://user-images.githubusercontent.com/94864663/151683567-47e6dfc1-53fb-496a-8390-1ecec4866b74.png)
Table 4. Adjusted School Summary

Specifically looking at THS, in the new analysis, the average reading score for THS is 83.9 which is slightly higher than the average reading score of 83.8 in the previous analysis. However, the average math score for THS in the new analysis is slightly lower at 83.35 as opposed to 83.4 in the original. In terms of passing percentages, in the original analysis 93.3%, 97.3%, 90.9% were passing math, reading, and passing overall respectively. Without the 9th graders the percent passing math, reading and overall drops to 93.3%, 97.0%, 90.6% respectively. 


### How Does Repalcing the Ninth graders' Math and Reading scores Affect THS's Performance Relative to the Other Schools?

![Original T5](https://user-images.githubusercontent.com/94864663/151683427-265c34f1-364c-446d-b37f-0d489f0ae9fb.png)
Table 5. Orignal Top 5 Schools


![Adj T5](https://user-images.githubusercontent.com/94864663/151683555-16315481-ea84-4f64-ad81-e26d9e4178a8.png)
Table 6. Adjusted Top 5 Schools

Above are the top five schools based on overall passing percentage, the top five standings do not change based on the adjusted data. However, specific numbers for Average math, Average Reading, percent passing math, percent passing reading, and percent passing overall do decrease for THS, they do not drop enough to take THS out of second place below Cabrera High School. Therefore, replacing the ninth graders' math and reading scores does not appear to significantly affect THS's performance relative to the other schools. 


### How Does Replacing the Nith-Grade Scores Affect the Following:

#### Math and Reading Scores by Grade

![Math By Grade](https://user-images.githubusercontent.com/94864663/151683455-db282ac7-6fb8-4bbf-8d73-c0db15736952.png)

Table 7. Adjusted Math Scores by Grade


![Reading By Grade](https://user-images.githubusercontent.com/94864663/151683465-3f86ad42-6120-4c00-921c-3f6a59a01930.png)

Table 8. Adjusted Reading Scores by Grade

Looking at math and reading scores specifically by grade, it is expected that the data for all the schools should not change for grades 10 -12 between the original analysis and the new analysis. However, in the new analysis, it is important to note the reading and math scores for 9th graders at THS is replaced by “nan”. This shows the adjusted data was successful in omitting scores for 9th graders. 


#### Scores by School Spending

![Original Spending](https://user-images.githubusercontent.com/94864663/151683478-41da8792-4320-4e4a-bb89-f5fe70d82be8.png)

Table 9. Orignal Scores by Spending

![Adj Spending](https://user-images.githubusercontent.com/94864663/151683547-c66b52b1-971e-42b4-8f0d-6df0eee861a1.png)

Table 10. Adjusted Scores by Spending

Analyzing scores by school spending, the average scores themselves do not change between the original analysis and the adjusted data set. However, the percent passing math, reading, and overall passing percentage all experience a very small increase after omitting the THS 9th graders scores with the exception of percent passing reading in the $585 – 629 spending range and percent passing overall in the $645 – 675 spending range which both experience a slight drop in their percentage. 


#### Scores by School Size

![Original Size](https://user-images.githubusercontent.com/94864663/151683489-6839ef68-cc6c-4a8a-bd4c-e535d0aba81d.png)

Table 11. Original Scores by School Size


![Adj Size](https://user-images.githubusercontent.com/94864663/151683539-d8e7fdb1-4401-4f4c-a769-50af0852b86e.png)

Table 12. Adjusted Scores by School Size

In terms of scores by school size, once again, the average scores do not change but the percent passing varies between the original and adjusted data. All school sizes experienced a slight drop in their percentage of students passing. However, large schools did not change in the percentage of students passing math and increased by 0.3% in the percentage of students passing overall. 


#### Scores by School Type

![Original Type](https://user-images.githubusercontent.com/94864663/151683502-e48a1485-12e6-4238-9912-3d2487cdae45.png)

Table 13. Orignal Scores by School Type

![Adj Type](https://user-images.githubusercontent.com/94864663/151683530-2315607d-d451-4a86-8768-dac5bd270d90.png)

Table 14. Adjusted Scores by School Type

The average math and reading scores based on charter vs district type schools do not change between the original and adjusted data. The percentage of students passing math and reading drops slightly in both school types without the THS 9th graders. Looking at the percentage of students passing overall, Charter schools saw an increase of 0.4% while district schools saw a decrease of 0.3%.  

## Summary

Comparing the original and adjusted dataset, it is important to consider the changes caused replacing math and reading scores for 9th graders at THS with NaNs. 

1. In the district summary, the percentage of students passing math, reading, and passing overall all experienced a decrease after the scores from the THS 9th graders were omitted. 
2. Similarly, these passing percentages also saw a slight dip in the school summary looking when looking at THS specifically. 
3. Both small and medium sized schools also only experienced dips in their passing percentages when looking at scores by school size. This may be expected to be different seeing as THS is a medium sized school. 
4. Looking at scores by school type, district schools experienced dips in all their passing percentages as well. This is interesting because THS is a charter school and charter schools saw an increase of 0.4% in the percentage of students passing overall after the reading and math scores for THS 9th graders were omitted.

