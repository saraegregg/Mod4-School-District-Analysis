# School District Analysis



## Project Overview

Maria, the cheif data scientist for a city school district needs my help with preparing school budget and reading and math standardized test data for analysis, presentation and reporting to provide insight to the school board about performance trends and patterns. 


## Resources

**Data Source:** schools_complete.csv, students_complete.csv

**Software:** Python 3.9.7, Anaconda Navigator 1.9.0, Jupyter Notebook 6.4.5

    
## Challenge Overview

After completing the analysis, it came to Maria's attention that there was some academic dishonesty occuring at one of the local high schools. The data from that school that was affected by the students' actions needed to be removed and the following analysis repeated:

    -The district summary
	-The school summary
	-The top 5 and bottom 5 performing schools, based on the overall passing rate
	-The average math score for each grade level from each school
	-The average reading score for each grade level from each school
    -The scores by school spending per student, by school size, and by school type

Both math and reading scores were replaced with "NaN", which means a "Not-a-Number" value, for 461 student records at Thomas High School. Although this may seem like a significant number, you will see below that the overall summaries did not alter significantly.

## Challenge Results

### _How is the district summary affected?_
After the removal of the ninth-grade scores, one metric remains unchanged: the average reading score is still 81.9. However, the other 4 metrics have slightly lower numbers once the Thomas High School freshmen scores are omitted from analysis. The average math score dropped from 79.0 to 78.9, the percentage passing math from 75.0% to 74.8%, the percentage passing reading from 85.8% to 85.7%, and the percentage overall passing from 65.2% to 64.9%.

Old District Summary:
![Old_district_summary.png](https://github.com/saraegregg/Mod4-School-District-Analysis/blob/main/images/Old_district_summary.png)

New District Summary:
![New district_summary.png](https://github.com/saraegregg/Mod4-School-District-Analysis/blob/main/images/New_district_summary.png)

### _How is the school summary affected?_
Upon removing Thomas High School's ninth-grade reading and math scores, the average math and reading score changed slightly from the original calculations; however the percent of students passing math, reading, and both subjects declined markedly, to 66.9%, 69.7%, and 65,1%, respectively. Once the NaN scores were no longer used in the calculations, Thomas High School's statistics returned to similar scores, most slightly lower than the original analysis produced. In four of the five comparison categories, Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing, Thomas High School statistics decreased. The Average Reading Score increased slightly once the ninth graders' scores were removed.

School Summary:
![New_school_summary.png](https://github.com/saraegregg/Mod4-School-District-Analysis/blob/main/images/New_school_summary.png)

### _How does replacing the ninth graders' math and reading scores affect Thomas High School's performance relative to the other schools?_
After removing Thomas High School's ninth-grade reading and math scores, its ranking plummeted among the other schools in the city, since those rankings used the percent of overall students passing both subjects. Once the NaN scores were no longer used in these calculations and Thomas High School's statistics returned to similar percentages, it resumed its position as second in the top 5 highest performing high schools.

Top 5 High Schools:
![Top_schools.png](https://github.com/saraegregg/Mod4-School-District-Analysis/blob/main/images/New_top_schools.png)

### _How does replacing the ninth-grade scores affect:_
#### * _Math and reading scores by grade?_
Math and reading scores by grade were not affected beyond the 9th graders' scores at Thomas High School, which are now represented by NaNs.

#### * _Scores by school spending?_
The scores by school spending did not change once the 9th graders' test data were replaced by NaNs; the small changes in the averages and percentages at Thomas High School did not change how the numbers rounded when averaged with the other schools in its per student spending category.

![New_perstudent_spending](https://github.com/saraegregg/Mod4-School-District-Analysis/blob/main/images/New_perstudent_spending.png)

#### * _Scores by school size?_
The scores by school size did not change once the 9th graders' test data were replaced by NaNs; the small changes in the averages and percentages at Thomas High School did not impact the rounding of the numbers when averaged with the other medium-sized schools.

![New_average_basedon_size](https://github.com/saraegregg/Mod4-School-District-Analysis/blob/main/images/New_average_basedon_size.png)

#### * _Scores by school type?_
The scores by school type did not change once the 9th graders' test data were replaced by NaNs; the small changes in the averages and percentages at Thomas High School did not affect how the numbers rounded when averaged with the other charter schools.

![New_scores_by_type](https://github.com/saraegregg/Mod4-School-District-Analysis/blob/main/images/New_scores_by_type.png)

## Challenge Summary
While some changes to the district-wide analysis did take place once the academic dishonesty was discovered and the impacted scores removed, in such a large population, the exclusion of 461 students' test scores did not bring about dramatic new conclusions. The changes that we can see are found in the district average scores and percents passing: mostly in minimally lowered numbers. For example. an average math score of 78.9 instead of 79.0 across the district. Similarly, the school summary for Thomas High School has slightly lower scores once the frehsman class' test scores were not counted toward the calculations. The broad trends and relationships that the initial analysis found regarding school spending, school size and school type were still reflected in the second analysis.