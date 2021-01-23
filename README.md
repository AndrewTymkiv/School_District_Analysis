# School District Analysis
---
## Analysis Overview
The purpose of this analysis was to analyze the student and school data of 15 schools in the district. The main points of analysis were the math and reading scores across students in the different schools, and how the grades differed based on the school size, budget, and type.

#### Analysis Tasks
1. Clean the list of student names, removing certain prefixes and suffixes
2. Replace the math and reading scores of 9th grade students at Thomas High School with NaNs
3. Calculate the new total student count at Thomas High School without the 9th graders
4. Calculate the percentage of students passing math and reading at Thomas High School
5. Create a DataFrame for a summary of the district with passing percentages and average scores
6. Create a DataFrame for a per school summary of budget, average scores, and percentage of students passing 
7. Calculate percentage of 10th-12th grade students passing at Thomas High School
8. Sort and show the top 5 performing schools in the district
9. Sort and show the bottom 5 performing schools in the district
10. Calculate average scores by grade for all schools in the district
11. Create a DataFrame showing average scores by the amount spent per student
12. Create a DataFrame showing average scores by school size
13. Create a DataFrame showing average scores by school type

---
## Results
##### How is the district summary affected?
- The district summary remains nearly unaffacted because only the 9th graders at Thomas High School were removed from the analysis. The percentage of students passing drops slightly as a result of this. 
![V1_District_Summary](https://github.com/AndrewTymkiv/School_District_Analysis/blob/main/Resources/V1_District_Summary.PNG)
![03_District_Summary](https://github.com/AndrewTymkiv/School_District_Analysis/blob/main/Resources/03_District_Summary.PNG)

##### How is the school summary affected?
- As expected, the only change in the school summary is with the Thomas High School data. The average scores and passing percentages all decrease as a result of the absence of the 9th graders' scores.
![V1_Per_School_Summary](https://github.com/AndrewTymkiv/School_District_Analysis/blob/main/Resources/V1_Per_School_Summary.PNG)
![04_Per_School_Summary](https://github.com/AndrewTymkiv/School_District_Analysis/blob/main/Resources/04_Per_School_Summary.PNG)

##### How does replacing the 9th graders' math and reading scores affect Thomas High School's performance relative to other schools?
- Thomas High School's overall average performance worsens compared to other school's when replacing the scores of the 9th graders. It is clear that the 9th graders had very high scores that helped the school's performance significantly.

##### How does replacing 9th grade scores affect math and reading scores by grade?
- The value decreases becase the 9th grade scores were removed
![09_Average_Math_Grades](https://github.com/AndrewTymkiv/School_District_Analysis/blob/main/Resources/09_Average_Math_Grades.PNG)
![10_Average_Reading_Grades](https://github.com/AndrewTymkiv/School_District_Analysis/blob/main/Resources/10_Average_Reading_Grades.PNG)

##### How does replacing 9th grade scores affect scores by school spending?
- The scores in the $630-644 range decreased
![11_School_Spending_Grades](https://github.com/AndrewTymkiv/School_District_Analysis/blob/main/Resources/11_School_Spending_Grades.PNG)

##### How does replacing 9th grade scores affect scores by school size?
- The scores in the 1000-2000 range decrease
![12_Scores_by_School](https://github.com/AndrewTymkiv/School_District_Analysis/blob/main/Resources/12_Scores_by_School.PNG)

##### How does replacing 9th grade scores affect scores by school type?
- The scores for charter schools decreases
![13_Scores_By_Type](https://github.com/AndrewTymkiv/School_District_Analysis/blob/main/Resources/13_Scores_by_Type.PNG)

---
## Summary
The four major changes to the school district summary after the replacement of the math and reading scores are:
1. The performance of Thomas High School compared to other schools
2. The 9th grade overall scores
3. The scores by school spending
4. The scores by school size
