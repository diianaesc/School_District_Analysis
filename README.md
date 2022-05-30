# School_District_Analysis

## Overview of Analysis

Assist Maria in replacing the math and reading scores for Thomas High School with NaNs due to academic dishonesty. Then repeat the school analysis and showcase trends in school performance based on school spending, school size and school types. Highlighting how the changes affected the overall analysis.

## Results

### District Summary
The district summary was not affected by the changes of the scores due to the high number of students included on the data. 
Only 461 scores were replaced with NaNs, which represents only 1% of the total number of students, which is not enough to drastically change the overall results. Below the before and after of the district summary: 

**Before**

<img width="934" alt="District Summary 1 0" src="https://user-images.githubusercontent.com/104380112/171048475-95302149-31d1-422c-be80-16787f7546e7.png">

**After**

<img width="934" alt="District Summary 2 0" src="https://user-images.githubusercontent.com/104380112/171048051-7cd04d7e-070e-4f6f-ae2e-299e1e398aea.png">


### School Summary

Thomas High School metrics were the only ones that changed on the school summary, all the other 14 schools stayed the same. 

### Thomas High School performance 

Number of students remained the same given that the names were not removed only the scores were replaced by NaNs. 
All other metrics (math and reading averages, and % passing scores) changed or decreased only by a few decimals which is not a drastic change from the original analysis. Even with the changes Thomas High School continues to be the second top school based on % Overall Passing. 

**Before**

<img width="982" alt="Screen Shot 2022-05-30 at 3 22 47 PM" src="https://user-images.githubusercontent.com/104380112/171050234-02b295a8-3fff-4651-9805-78019f0ea81c.png">

<img width="981" alt="Screen Shot 2022-05-30 at 3 34 46 PM" src="https://user-images.githubusercontent.com/104380112/171051301-62a2306a-e97c-44b2-97fa-eef4a4ee0dda.png">

**After**

<img width="970" alt="Screen Shot 2022-05-30 at 3 32 14 PM" src="https://user-images.githubusercontent.com/104380112/171051072-5f58956a-e4fe-4cd2-a42e-3f8b8272dc7a.png">

### Replacing ninth-graders scores
 - Scores math and reading by grade: Average for ninth graders at THS were replaced with NaNs. The rest of the grades and schools show no changes
 - Scores by school spending: THS falls under the third spending bin $631-$645 and no significant changes were recorded 
 - Scores by school size: THS falls under the medium size bin 1000-1999 and no significant changes were recorded 
 - Scores by school types: THS falls under the charter school type and no significant changes were recorded 

## Summary
- We calculated a new number of students at Thomas High School to calculate the % Passing values
- Math and Reading averages of ninth graders at Thomas High School were replaced with NaNs 
- The overall math and reading score averages at Thomas High School decreased by a few decimals 
- The % Passing values at Thomas High School decreased by a few decimals 

