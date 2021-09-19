# School District Analysis
## Overview of the school district analysis: 
The school board discovered that Thomas High School 9th grade math and reading scores were compromised. Hence the school district student performance analysis needed to be reanalyzed without 9th grade scores from Thomas High School. The 9th grade scores from Thomas High School is overwritten with NaNs and data analysis was performed again. 

## Results
Below are summary of results after Thomas High School's 9th grade math and reading scores were replaced with NaNs. Please note all references to **Prior** Data are based on analysis prior to replacing Thomas High School scores and is saved on PyCitySchools.ipynb file.

### **School District Summary**
* The school district overall passing percentage is reduced slightly from 65.2% to 64.9%. 
* The school district's average Math score, passing Math percentage and passing Reading percentage also decreased slightly.
* The Total Schools, Total Students, Total Budget and average Reading score remained same.

    * Prior School District Summary
![myimage-alt-tag](/Resources/SchoolDistrictSummary-Before.png)
    * Updated School District Summary   
![myimage-alt-tag](/Resources/SchoolDistrictSummary-After.png)
 
### **School Summary**
* After the ninth grader's math and reading scores are replaced for Thomas High School, average Math score, average Reading score, passing Math percentage and passing Reading percentage and overall passing percentage was slightly reduced.
* The other metrics, Total School Budget, per Student Budget, Spending Range (per student) and school size remained same.
The school overall passing percentage is reduced slightly from 65.2% to 64.9%. 
    * Prior School Summary
![myimage-alt-tag](/Resources/PriorSchoolSummary.png)
    * Updated School Summary   
![myimage-alt-tag](/Resources/UpdatedSchoolSummary.png)
 
### **Thomas High School performance relative to other schools**

* Thomas High School remained top school with ~91% overall passing percentage before and after replacing Thomas High School’s  ninth graders’ math and reading scores.
    * Prior Top 5 Schools
![myimage-alt-tag](/Resources/PriorTop5Schools.png)
    * Updated Top 5 Schools  
![myimage-alt-tag](/Resources/UpdatedTop5Schools.png)


* Besides Thomas High School, the other schools has no impact on any of following metrics:

    * Math Scores by Grade remained unchanged except for Thomas High School 9th graders' math score.
        ![myimage-alt-tag](/Resources/MathScoresByGrade.png)

     
    * Reading Scores by Grade was not affected besides Thomas High School 9th graders' reading score
     ![myimage-alt-tag](/Resources/ReadingScoresByGrade.png)
     
   
    * Scores by school spending was not impacted after the update. 
    ![myimage-alt-tag](/Resources/ScoresBySpending.png)
    
    * Scores by school size did not change after the update. 
    ![myimage-alt-tag](/Resources/ScoresBySchoolSize.png)

    * Scores by school type was not changed after the update.
    ![myimage-alt-tag](/Resources/ScoresBySchoolType.png)

## Summary

After reading and math scores for the ninth graders at Thomas High School are replaced with NaNs following metrics decreased slightly.
* School District's 
    * Average Math score 
    * Passing Math percentage
    * Passing Reading percentage  
* Thomas High School's 
    * Average Math score
    * Average Reading score
    * Passing Math percentage
    * Passing Reading percentage 
    * Overall passing percentage  