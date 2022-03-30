# School_District_Analysis
#Overview of the school district analysis: 
The goal of the analysis is to use data obtained on student grades to observe trends that a school board may find useful in governing the school district.
There was a situation that required the original analysis to be adjusted, so the grades from the ninth grade of Thomas High School are disregarded.
This analysis addresses the potential change in the information after making these adjustments.

# Results: Using bulleted lists and images of DataFrames as support, address the following questions.

## How is the district summary affected?
![image](https://user-images.githubusercontent.com/99847046/160759351-2fff9313-8fca-4e59-a5a8-b5d54a402b3f.png)

The screen shot above is the summary from the Challenge.  The one below is from the module. 
![image](https://user-images.githubusercontent.com/99847046/160759689-e8b6b131-176f-44be-ad84-3eb6d078fff6.png)

- Average Reading score remains the same
- Minor inconsequencial decrease in all other metrics 


## How is the school summary affected?

![image](https://user-images.githubusercontent.com/99847046/160760159-05b1940b-dafc-43f7-830b-a821e0fa3b9e.png)
Challenge
![image](https://user-images.githubusercontent.com/99847046/160760180-83b82eef-2945-4b23-ba25-00960e2482c9.png)
Module

- Significant drop in pass rate for reading and math.
- Once adjustment is made to discount 9th grade results, the results become nearly identical having differences of tenths of a percentage.

## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

![image](https://user-images.githubusercontent.com/99847046/160762004-a8d3ee6e-5d74-46f0-89b4-787a7d98cf84.png)

![image](https://user-images.githubusercontent.com/99847046/160761870-9975ee46-a6b0-4dae-a93c-768b4a042a0b.png)

- Thomas High School was ranked 2nd in overall pass percentage
- When the Ninth Graders are removed they drop to the 8th position, becoming the median of the ranking.
- Thomas High School returns to 2nd in the rank once the ninth graders are omitted from the calculations.

## How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
- All things remain the same but for the 9th grade scores that are now empty

### Scores by school spending
- School spending remained exactly same

### Scores by school size
![image](https://user-images.githubusercontent.com/99847046/160764369-13e1149a-b7de-42df-a1f3-468d988c6297.png)
Challenge
![image](https://user-images.githubusercontent.com/99847046/160764408-d87f07a8-a097-49db-9664-1a5482293f92.png)
Module

-It's worth noting a very small decrease in the medium size category across all metrics.(very insignificant)

### Scores by school type
- No noticable change

# Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

Once the 9th graders are removed, Thomas High School sees a significant fall the Math and Reading pass percentages(by extension overall pass percentage).
These leads to being the second best performing school in overall pass rate, to being dropped to 8th.  It would no doubt decrease any grouping by spending or size that Thomas High School would fall under.  However, once the summary is adjusted to exclude the 9th grade from all calculations, there are mostly irrelvant changes to 
Thomas High School's performance.  Changes are mostly down to a decrease by a tenth of a percentage point as can be seen in the school summary and the medium category in the size comparison.  
