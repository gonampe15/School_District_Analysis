# School_District_Analysis

## Overview

Maria has asked us for an analysis on the school district she works in. The main analysis focuses on comparing student results and all of the schools data to see how they are performing. However, after the school board reviewed the data, it was determined that the data from one of the schools was suspect of cheating. The school board asked for the data to be removed and analyzed again for a comparison.

## Results

1. How is the district summary affected?
   * When comparing both analysis, the difference is less than 1% and the numbers would still round to the same whole number.
     * Adjusted District Summary
       ![New Results](/Resources/new_summary_df.png)
     * Original District Summary
       ![Original Results](/Resources/old_summary_df.png)

2. How is the school summary affected?
   * Removing the 9th grade students results from the data set had a major impact by dropping the math, reading and overall passing rates.
     * Adjusted School Summary
       ![New Results](/Resources/new_school_df.png)
     * Original School Summary 
       ![Original Results](/Resources/old_school_df.png)

3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
   * After adjusting the 9th grade data, Thomas High School went from ranking at 2nd place to rank in the exact middle of 15 campuses at 8th place.

4. How does replacing the ninth-grade scores affect the following:
   * Math and reading scores by grade
     * In the original analysis, Thomas High School had 83.6 math average and 83.7 reading average for the 9th grade tests. Now the averages are no longer available since we replaced with null values.
     * Adjusted Math scores   
       ![New Math](/Resources/new_math_df.png)
     * Adjusted Reading scores  
       ![New Reading](/Resources/new_reading_df.png)
     
   * Scores by school spending
     * Replacing the 9th grade scores caused a very small impact in the scores by school spending.
      * Original Scores by School Spending
        ![Original Results](/Resources/old_spending_df.png)
      * Adjusted Scores by School Spending      
        ![New Results](/Resources/new_spending_df.png) 
   * Scores by school size
     * Replacing the 9th grade scores caused a very small impact in the scores by school size.
      * Original Scores by School Size
        ![Original Results](/Resources/old_size_df.png)
      * Adjusted Scores by School Size
        ![New Results](/Resources/new_size_df.png)
   * Scores by school type
     * Replacing the 9th grade scores caused a very small impact in the scores by school type.
      * Original Scores by School Type
        ![Original Results](/Resources/old_type_df.png)
      * Adjusted Scores by School Type
        ![New Results](/Resources/new_type_df.png)
## Summary
Four changes that occurred after updating the math and reading scores were:
1. The overall passing rate for Thomas High School dropped dramatically from 91% to 65%.
2. In addition to the overall passing rate, the school's math and reading averages also saw a major shift.
3. In the district rankings, Thomas High School's ranking dropped from 2nd to 8th.
4. Without the 9th graders math and reading scores, Thomas High School is not as competitive as the other charter schools.
