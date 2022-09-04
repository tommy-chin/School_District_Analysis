# PyCitySchools Analysis
## Overview
### Purpose
A client named Maria requested that an analysis be done on the performance trends and patterns on the city school districts that she oversees. An initial analysis was completed with all of the schools in the school district. However, it was then requested that the math and reading standardized testing scores of the 9th grade class for Thomas High School be excluded from the analysis due to academic dishonesty. In this analysis, the student standardized testing performances and the spending budgets of the schools excluding the 9th grade class of Thomas High School will be compared to the original analysis that was performed. 
## Results
* __How is the district summary affected?__ 
  * The district summary was slighty affected after the exclusion of 9th grade testing scores from Thomas High School. The average math score, percentage of students passing math, percentage of students passing reading, and overall percentage of students all slightly decreased. The average reading scores of the district summary stayed the same. 
  * __District Summary Before Thomas High School 9th Grade Exclusion__
  ![district summary before.PNG](https://github.com/tommy-chin/School_District_Analysis/blob/main/Resources/district%20summary%20before.PNG)
  * __District Summary After Thomas High School 9th Grade Exclusion__
  ![district summary after.PNG](https://github.com/tommy-chin/School_District_Analysis/blob/main/Resources/district%20summary%20after.PNG)
 
* __How is the school summary affected?__
  *  The school summary was slightly affected in that only the school summary analysis for Thomas High School was adjusted. The averages math scores, reading scores, percentage of students passing math, percentage of students passing reading, and overall percentage of students passing were all slightly lowered. 
  *  __School Summary Analysis Before Thomas High School 9th Grade Exclusion__
  ![no exclusion school analysis.PNG](https://github.com/tommy-chin/School_District_Analysis/blob/main/Resources/no%20exclusion%20school%20analysis.PNG)
  *  __School Summary Analysis After Thomas High School 9th Grade Exclusion__ 
  ![school analysis after exclusion of 9th thomas.PNG](https://github.com/tommy-chin/School_District_Analysis/blob/main/Resources/school%20analysis%20after%20exclusion%20of%209th%20thomas.PNG)
*  __How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?__
   * Even after the exclusion of the 9th grade testing scores from Thomas High School, the school still remains in the top 5 performing schools in overall passing    percentage for standardized testing. 
   * __Top 5 Schools Before Thomas High School 9th Grade Exclusion__
    ![top 5 schools before.PNG](https://github.com/tommy-chin/School_District_Analysis/blob/main/Resources/top%205%20schools%20before.PNG)
   * __Top 5 Schools After Thomas High School 9th Grade Exclusion__
    ![top 5 schools after.PNG](https://github.com/tommy-chin/School_District_Analysis/blob/main/Resources/top%205%20schools%20after.PNG)
* __How does replacing the ninth-grade scores affect the following:__
  *  Math and reading scores by grade
     *   The math and reading scores by grade analysis was affected in that the Thomas High School 9th grade math and reading scores were replaced with nan.
  *  Scores by school spending
     *  The scores by school spending analysis was affected in that the average scores and percentage of students passing for reading, math, and overall were slightly lowered. 
  *  Scores by school size
     *  The scores by school size analysis was affected since Thomas High School is classified as a medium sized school. All of the medium sized school testing scores and percentage of students passing were slightly lowered. 
  *  Scores by school type
     *  The scores by school type analysis was affected since Thomas High School is classified as a charter school. The average testing scores and passing percentage of students were slightly lowered for charter schools. 
  
    
## Summary
### Key Takeaways
After replacing the 9th grade Thomas High School testing scores with NaNs, the school district analysis was slightly changed. The dataset that was most directly affected was the School Summary dataset since this data set specifically showed the statistics for Thomas High School. The percentage changes were most significant in this analysis. The other analyses were much more broad so their statistics were not affected as much. An example of this would be the scores by school size analysis. The small sized and larged sized school testing scores were not affected at all since Thomas High School was classified as a medium sized school. The medium sized school testing performances were not greatly affected since Thomas High School was just one of the schools in the medium sized category. To add to that, only the 9th grade class of Thomas High School was adjusted which only adds to the fact that there was not a signiciant change in the medium sized school testing performances. 
    
