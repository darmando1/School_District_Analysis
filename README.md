# School District Analysis
## **Summary**
Utilizing code to identify the following based on math and reading scores:
  - The top 5 performing schools based on overall passing rate
  - The bottom 5 performing schools based on the overall passing rate
  - The average math score for each grade level from each school
  - The average reading score for each grade level from each school
  - The scores by school spending per student
  - The scores by school size
  - The scores by school type
## Analysis Results Based on THS 9th Grade Modification
As mentioned above, the results previously generated were skewed by incorrect 9th Grade data provided by Thomas High School. The staff decided to rerun the analysis without data specifically for 9th graders at Thomas High School ("THS"). The following questions have been addressed:
  - How is the district summary affected?
    - The staff notes the following in district summary
    - Please see below for image with THS 9th Grade data
     ![District Summary With THS 9th](https://github.com/darmando1/School_District_Analysis/blob/main/Resources/district_summary_THS9th.JPG)
    - Please see below for image without THS 9th Grade data
     ![District Summary Without THS 9th](https://github.com/darmando1/School_District_Analysis/blob/main/Resources/district_summary_noTHS9th.JPG)
      1. Average Math Score: Change from 79.0% to 78.9%.
      2. Average Reading Score: No change from 81.9%
      3. % Passing Math: Change from 75.0% to 93.2%
      4. % Passing Reading: Change from 85.8% to 97.0%
      5. % Overall Passing: Change from 65.2% to 90.6%
    - **The staff notes significant changes in the % Passing for Math, Reading, and Overall**
  - How is the school summary affected?
    - The staff notes the following in the school summary
    - Please see below for image with THS 9th Grade data
     ![School Summary With THS 9th](https://github.com/darmando1/School_District_Analysis/blob/main/Resources/school_summary_THS9th.JPG)
    - Please see for image without THS 9th Grade data
     ![School Summary Without THS 9th](https://github.com/darmando1/School_District_Analysis/blob/main/Resources/school_summary_noTHS9th.JPG)
      1. Changes should not have occurred and did not occur in any school other than THS
      2. Average Math Score changed from 83.42% to 83.35% in THS
      3. Average Reading School changed from 83.85% to 83.90% in THS
      4. % Passing Math decreased from 93.27% to 93.19% in THS
      5. % Passing Reading decreased from 97.30% to 97.02% in THS
      6. % Overall Passing decreased from 90.95% to 90.63% in THS
    - **The staff notes % Passing decreased in Math, Reading and Overall**
  - How does replacing the ninth graders' math and reading scores affect THS's performance relative to other schools?
    - Please see below for image with THS 9th Grade Data
     ![Top 5 Schools With THS 9th](https://github.com/darmando1/School_District_Analysis/blob/main/Resources/top_five_overall_passing_THS9th.JPG)
    - Please see below for image without THS 9th Grade Data
     ![Top 5 Schools Without THS 9th](https://github.com/darmando1/School_District_Analysis/blob/main/Resources/top_five_overall_passing_noTHS9th.JPG)
    - Overall Passing (2nd place): No change although as mentioned above, % Passing Math, Reading, and Overall decreased.
    - **The staff notes that although 9th grade scores were omitted from the analysis, THS still placed in the top 5 schools overall**
  - How does replacing the ninth-grade scores affect the following:
    - Math and Reading scores by Grade: No change aside from NaN values for THS 9th grade.
    - Scores by school spending: No change
    - Scores by school size: No change
    - Scores  by school type: No change
## Summary
As mentioned above, on a broader level there were no changes affecting scores on an overall school level (by school spending, school size, and school type). This makes sense as the portion of corrupted data was a significantly smaller number than the group as a whole. Likewise, as noted in the district summary, although changes were significantly large ($ Passing in Math, Reading and Overall were increased), on the school summary level there were minimal jumps. Thus, the 9th grade data, although small, significantly skewed the school data itself to create a higher passing % but did not create a large enough ripple to affect performance on an overall school level.
