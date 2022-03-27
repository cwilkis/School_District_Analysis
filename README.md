# School_District_Analysis

## Overview
The purpose of this analysis is to compare math and reading test scores across multiple high schools. This will be used by the school board to assess each school, and to determin if additional funding is needed for underperforming schools. After the initial analysis, I was asked to remove reading and math scores from Thomas High School 9th grade students due to suspicion of academic dishonesty. 

## Results

- The school and district summaries are not overly affected by removing the 9th grade math and reading scores from Thomas High Shool. Screenshots below show average test scores for math drop by less than 1/10% point, and the average reading score goes up 1/100th% point. 

![This is an image](https://github.com/cwilkis/School_District_Analysis/blob/main/Resources/School%20Summary%20original.png) 
![This is an image](https://github.com/cwilkis/School_District_Analysis/blob/main/Resources/School%20Summary%20final.png)

- Since only one set of test scores was replaced, the remaining categories were also not overly affected. Thomas High School ws still listed in the top 5 schools in the district. 


- Replacing ninth-grade scores from Thomas highschool to NaN from a number does affect the scores by school spending and size, but not by type. 
	- Math, reading, and overall % scores dropped in the $631-$645 spending range. 

![This is an image](https://github.com/cwilkis/School_District_Analysis/blob/main/Resources/District%20summary%20original.png)
![This is an image](https://github.com/cwilkis/School_District_Analysis/blob/main/Resources/District%20Summary%20final.png)

	- Math, reading, and overall % scores dropped in the medium size schools

![This is an image](https://github.com/cwilkis/School_District_Analysis/blob/main/Resources/school%20size%20original.png)
![This is an image](https://github.com/cwilkis/School_District_Analysis/blob/main/Resources/school%20size%20final.png)

	- Math, reading, and overall % scores had no discrenable change in the school type. 

![This is an image](https://github.com/cwilkis/School_District_Analysis/blob/main/Resources/school%20type%20original.png)
![This is an image](https://github.com/cwilkis/School_District_Analysis/blob/main/Resources/school%20type%20final.png)

## Summary
Based on the results above, there are some changes to the school district analysis once the 9th grade results from Thomas High School are removed. While it does not afect the school summary, there were drops in math, reading, and overall percentage scores for the district results by school spending, and size. The type of school (charter vs.district) was not affected the same as, most likely due to the remaining schools higher test scores. 
 