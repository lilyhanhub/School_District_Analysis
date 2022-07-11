# School_District_Analysis
## Overview of the school district analysis
The chief data scientist of the PyCity School District, Maria has been tasked to analyze data from the students' standardized test scores. The analysis report will be used to for informed discussions and strategic decisions at school and district levels. After generating a high-level snapshot of the school district's key metrics, the school board has identified academic dishonesty with 9th grade math and reading scores at Thomas High School. The purpose of this analysis is to assist Maria to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact, and to recreate the following metrics:
* District Summary - provides a snapshot of the districts' key metrics
* Per School Summary - provides key metrics for each school
* A table presenting the top 5 and bottom 5 performing schools based on the overall students passing
* Average math and reading scores for each grade level from each school
* School performance based on the budget per student
* School performance based on the school size
* School performance based on the school type

## Results
Below are the comparison of orignal and amended results after removing all the math and reading scores of Thomas High School 9th graders, which was a total of 461 students. 

1. **Amended District Summary**
![Amended district summary](https://github.com/lilyhanhub/School_District_Analysis/blob/main/Screenshots%20/district_summary_amended.png)
   **Orignial District Summary**
![Original district summary](https://github.com/lilyhanhub/School_District_Analysis/blob/main/Screenshots%20/district_summary_original.png)

2. **Amended Per School Summary**
![Amended School Summary](https://github.com/lilyhanhub/School_District_Analysis/blob/main/Screenshots%20/school_summary_amended.png)
  **Original Per School Summary**
![Original School Summary](https://github.com/lilyhanhub/School_District_Analysis/blob/main/Screenshots%20/school_summary_original.png)

3. **Amended Top 5 School Summary**
![Amended Top 5 School Summary](https://github.com/lilyhanhub/School_District_Analysis/blob/main/Screenshots%20/top5schools_amended.png)
  **Original Top 5 School Summary**
![Original Top 5 School Summary](https://github.com/lilyhanhub/School_District_Analysis/blob/main/Screenshots%20/top5schools_original.png)

4. **Amended Average Math Scores by Grade Level**
![Amended Scores by Grade Level](https://github.com/lilyhanhub/School_District_Analysis/blob/main/Screenshots%20/math_scores_by_grade_amended.png)
   **Original Average Math Scores by Grade Level**
![Original Scores by Grade Level](https://github.com/lilyhanhub/School_District_Analysis/blob/main/Screenshots%20/math_scores_by_grade_original.png)

5. **Effects of replacing the ninth-grade scores for Thomas High School(THS)**
  * No changes to the Math and reading scores by grade except for the THS 9th graders being replaced with NaNs
  * No changes to the bottom 5 school summary
  * No changes to the School Spending Summary 
  * No changes to the School Size Summary
  * No changes to the School Type Summary

## Summary
(Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.)
According to the above results, after removing the math and reading scores of the THS 9th graders 



## Resources
* Data Source: 
  * [schools_complete.csv](https://github.com/lilyhanhub/School_District_Analysis/blob/main/Resources/schools_complete.csv)
  * [students_complete.csv](https://github.com/lilyhanhub/School_District_Analysis/blob/main/Resources/students_complete.csv)
  * [clean_students_complete.csv](https://github.com/lilyhanhub/School_District_Analysis/blob/main/Resources/clean_students_complete.csv)
* Software: Jupyter Notebook, Anaconda 4.13.0
