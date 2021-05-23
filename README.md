# School_District_Analysis

## Overview 
In Module 4, a chief data scientist, Maria, for a city school district was tasked to prepare and analyze student funding and standardized testing data for city schools. The purpose of the analysis was to aggregate data to report trends in school performance that will assist the school board in making decisions regarding school budgets and priorities.

## Scope
After the initial analysis, Maria was notified by the school board of potential academic dishonesty specifically in regard to 9th grade reading and math score for Thomas high School. 

In order to maintain the integrity of state testing standards, the board has requested the analysis repeated by replacing Thomas High School 9th grade math and reading score with NaN. Finally, an analysis report will be provided to examine how these changes impacted overall analysis.

## Resources
- Data Source:
    - Resources\schools_complete.csv
    - Resources\students_complete.csv
- Code files:
    - PyCitySchools.ipynb (original analysis)
    - PyCitySchools_Challenge.ipynb (challenge 4 analysis)

## Results


 - **District Summary:** Comparing summary results of the original and repeated analysis, we can see that there isn't any significant difference in average and percentage scores. Repeated analysis shows fractionally differences. Overall passing percentage difference is -0.15%
<br />

Original:
<img src="/Images/original_district_summary.png" width=700 align=center>
<br />

Repeated:
<img src="/Images/repeated_district_summary.png" width=700 align=center>
<br />
<br />

- **School Summary:** Thomas High School summary comparison between original and repeated analysis again shows small differences. Percentages and average scores in the second pass with 9th grade's score replaced with NaNs is slight lower than the original analysis. Overall passing % difference is 0.34%. All other school's averages and percentages remain the same.
<br />

Original:
<img src="/Images/original_school_summary.png" width=700 align=center>

<br />
<br />

Repeated:
<img src="/Images/repeated_school_summary.png" width=700 align=center>
<br />
<br />

- **Thomas High School’s performance relative to the other schools:** School's standing is still the 2nd highest performing school even after replace 9th grade's math and reading scored with NaNs.

<br />
<br />

- **Affect of replacing  ninth-grade scores on the following:** Since there is no significant impact on Thomas High School performance as result of repeating analysis with 9th grade scores set to NaNs, there is:
    - No impact on other grade's (10th-12th) math and reading scores by grade for Thomas High School
    - No impact on scores by school spending 
    - No impact on scores by school size
    - No Impact on scores by school type

<br />
<br />

## Summary

<br />

Overall, there does not seem to be any significant differences in averages and passing percentages after excluding 9th grade score from the analysis to indicate academic  dishonesty:
1) Thomas High school shows 0.34% decrease in overall passing % which is a fractional difference. 
2) Thomas High School maintains its status as 2nd highest performing school in the district.
3) No changes/pattern changes were observed on metrics such as scored by school spending, size and type.
4) District level summary does not show any major shift in stats, overall passing % decrease was 0.15% which is fairly minor as well.
    
<br />
