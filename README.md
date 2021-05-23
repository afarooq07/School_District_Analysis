# School_District_Analysis

## Overview 
In Module 4, a chief data scientist, Maria, for a city school district was tasked to prepare and analyze student funding and standardized testing data for city schools. The purpose of the analysis was to aggregate data to report trends in school performance which willl assist the school board in making decisions regarding school budgets and priorities

## Scope
After the initial analysis, Maria was notified by the school board of potential acedamic dishonesty specifically in regards to 9th grade reading and math score for Thomas high School. 

In order to maintain the integrity of state testing standards, the board has request the analysis repeated by replacing Thomas High School 9th grade math and reading score with NaN. Finally, an analysis report will be provided to examine how these changes impacted overall analysis

## Resources
- Data Source:
    - Resources\schools_complete.csv
    - Resources\students_complete.csv
- Code files:
    - PyCitySchools.ipynb (original analysis)
    - PyCitySchools_Challenge.ipynb (challenge 4 analysis)

## Results


 - **District Summary:** Comparing summary results of the original and repeated analysis, we can see that there isn't any significant difference in average and percentage scores. Repeated analysis show fractionally differences. Overall passing percentage difference is -0.15%
<br />

Original:
<img src="/Images/original_district_summary.png" width=700 align=center>
<br />

Repeated:
<img src="/Images/repeated_district_summary.png" width=700 align=center>
<br />
<br />

- **School Summary:** Thomas High School summary comparison between original and repeated anaysis again shows small differences. Percentages and average scores in the second pass with 9th grade's score replaced with NaNs is slight lower than the original analysis. Overall passing % difference is 0.34%. All other school's averages and percentages remain the same.
<br />

Original:
<img src="/Images/original_school_summary.png" width=700 align=center>

<br />
<br />

Repeated:
<img src="/Images/repeated_school_summary.png" width=700 align=center>
<br />
<br />

- **Thomas High School’s performance relative to the other schools:** School's standing is still the 2nd highest performaning school even after replace 9th grade's math and reading scored with NaNs.

<br />
<br />

- **Affect of replacing  ninth-grade scores on the following:** Since there is no significant impact on Thomas High School performance as result of repeating anlysis with 9th grade scores set to NaNs, there is:
    - No impact on other grade's (10th-12th) math and reading scores by grade for Thomas High School
    - No impact on scores by school spending 
    - No impact on scores by school size
    - No Impact on scores by school type

<br />
<br />

## Summary
