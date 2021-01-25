# School District Analysis
## Overview of School District Analysis

In this assignment the task at hand was to assist Maria, the chief data scientist for a city school district. In this project, we performed analysis on multiple datasets containing stats on school funding, student reading and writing standardized test scores as well as other information about the schools they attend. In this analysis the data was aggregate to showcase trends in school performance to ultimately assist the assist School Board and Super Intendent in making decisions regarding the school budgets and prioroties.

## Results

### How is the district summary affected?
**District Summary**
<img align="left" src="https://github.com/hollyouellette/School_District_Analysis/blob/main/Analysis/District_Summary.png">
  - The average Reading and Math scores for the School District were passing grades (over 70%).
  - On average, students in this school district score higher on the Reading standardized test versus Math.
  - While a signicant percentage of students passed each of the Math or Reading standardized tests, significantly less students in this district passed both standardized tests (all indicated by the **% Overall Passing** column)
  
### How is the school summary affected?
**School Summary**
<img align="left" src="https://github.com/hollyouellette/School_District_Analysis/blob/main/Analysis/School_Summary.png">
  - Charter schools have smaller student populations than the District Schools
    - _**District School Total Students Range:**_ 2739 - 4976
    - _**Charter School Total Students Range:**_ 427 - 2283
  - Charter schools have a significantly higher % Overall Passing than the District Schools.
    - Amongst the District Schools, the Overall Passing Percentage consistenly hovered near 50%.
  - Average Reading Scores and % Passing Reading were consistenly high accross all schools (aside from Thomas High School due to NaN values, which will be addressed in the following section).
  - Fluctuations in % Overall Passing were due to signigicantly lower % Passing Math in the District Schools. 
  
### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
**Original Math & Reading Scores for Thomas High School**
<img align="left" src="https://github.com/hollyouellette/School_District_Analysis/blob/main/Analysis/Thomas_High_School_All_Grades.png">

**Math & Reading Scores for Thomas High School without 9th Grade**
<img align="left" src="https://github.com/hollyouellette/School_District_Analysis/blob/main/Analysis/Thomas_High_School_Sr_Grades.png">
