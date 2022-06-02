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
   * Scores by school spending
   * Scores by school size
   * Scores by school type
