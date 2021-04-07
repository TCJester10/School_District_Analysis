# School_District_Analysis
## Overview of the school district analysis

Due to suspected grade altering in the 9th grade of Thomas High school, our previous analysis of school district test scores
must be redone excluding the entirity of THS's 9th grade. This excluded 461 (by setting their test score values to NaN) students 
from the initial 39169 leaving 38709 to be analyzed. The effect excluding these students had was modest and small. 


## Results

# How is the district summary affected?
 * The district summary is affected by small amounts.
 * ![Initial Distric DF](https://github.com/TCJester10/School_District_Analysis/blob/main/screenshots/Initial%20District%20df.png)
 * This is the initial district data frame
 * ![Updated Distric DF](https://github.com/TCJester10/School_District_Analysis/blob/main/screenshots/Updated%20District%20df.png)
 * This is the updated district data frame. As can be seen, there is drop of .06 percent in the average math score, and a drop of .02 percent 
   in the average reading score. There is also a drop in the percentage of students passing, going form 75.00% passing math tests to 74.76%, 
   and from 85.81% passing reading tests to 85.66%. This translates to a drop in overall passing for both tests, going from 65.17% passing both math and reading tests, to 64.86%.
 
 # How is the school summary affected?
 * ![Initial School Summary](https://github.com/TCJester10/School_District_Analysis/blob/main/screenshots/Initial%20School%20Sumary.png)
 * This is the initial School Summary
 * ![Updated School Summary](https://github.com/TCJester10/School_District_Analysis/blob/main/screenshots/Updated%20School%20Summary.png)
 * This is the updated school summary. The overall affects are limited in this analysis, as only one schools data was changed.
   * As can be seen, Thomas High School saw slight changes in its test score averages, and the         percentage of students who passed. Their math scores fell from an average of 83.41, to an 83.35, 
reading scores actually raised from an 83.85 to an 85.89.
   * The percentage of students passing math fell from 93.87% to 93.19%, and the percentage passing reading fell from 97.31% to 97.09 despite the rise in the average reading score. The overall  percentage of students passing both tests fell from 90.95% to 90.63%. 
    # Replacing the 9th grade scores. 
 * As only 9th grade scores were changed, only 9th grade scores would be affected. The biggest change is that Thomas High School 9th grade scores are now NaN and will not be in the analysis.
    # Scores by school spending
 * ![School speding start](https://github.com/TCJester10/School_District_Analysis/blob/main/screenshots/Initial%20School%20Spending.png)
 * Initial spending scores
 * ![Updated spending](https://github.com/TCJester10/School_District_Analysis/blob/main/screenshots/Updated%20School%20Spending.png)
 * Updated spedning scores. As can be seen, there is no signifigant change in the spending scores. This is likely due to Thomas High School still maintaining high scores even with the 9th grade tests taken out. 
        Scores by school size
 * ![Initial School Size](https://github.com/TCJester10/School_District_Analysis/blob/main/screenshots/initial%20School%20size.png)
 * Initial scores by school size
 * ![Updated School Size](https://github.com/TCJester10/School_District_Analysis/blob/main/screenshots/Updated%20School%20size%20score.png)
 * Updated school size analysis. The small and Large schools see no affect as they're scores were not affected by the dropping of THS 9th grade scores. The Medium schools however saw a very small change in all scores. Average Math scores going from 83.37 to 83.36, average reading rising from 83.86 to 83.87, % Passing math lowering from 93.60 to 93.58, % Passing reading lowering from 96.79 to 96.73, and the % of students who passed both tests lowering from 90.62 to 90.56. 

Summary: Summarize four major changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs

The effect excluding these students had was modest and small. For Thomas High School specifically, The percent of students passing reading tests went down from 97.31 to 97.02, 
and percent of students passing math tests went from 90.95 to 90.30. So it would stand to think that the grades were artificially raised by small amounts, however with such small changes, it's hard to say for certain. One thing interesting was that average reading scores raised from an 83.85 to an 85.98! This could be because the academic dishonesty was suspected in the math scores, and thus reading scores would not be subject to the same affects that removing math scores would. It's interesting to note that despite the fact that average reading scores raised, the percentage of students passing still lowered. Perhaps some 9th graders really aced those tests, and some did not do so well. Overall, the affect from removing the scores was modest in the school analysis, and barely noticed in the overall district analysis. This is to be expected as we really only removed ~400 students from a dataset of over 39,000, the affect this could have was always limited. 

