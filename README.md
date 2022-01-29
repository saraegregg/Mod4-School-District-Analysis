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
After the removal of the ninth-grade scores, in four of the five comparison categories, Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing, Thomas High School statistics decreased. The Average Reading Score increased slightly once the ninth graders' scores were removed.

New District Summary:
![New district_summary.png](https://github.com/saraegregg/Mod4-School-District-Analysis/blob/main/images/New_district_summary.png)

### _How is the school summary affected?_
Upon removing Thomas High School's ninth-grade reading and math scores, the average math and reading score changed slightly from the original calculations; however the percent of students passing math, reading, and both subjects declined markedly, to 66.9%, 69.7%, and 65,1%, respectively. Once the NaN scores were no longer used in the calculations, Thomas High School's statistics returned to similar scores, most slightly lower than the original analysis produced.

School Summary:
![New_school_summary.png](

### _How does replacing the ninth graders' math and reading schores affect Thomas High School's performance relative to the other schools?

### _How does replacing the ninth-grade scores affect:
### * _Math and reading scores by grade?_
### * _Scores by school spending?_
### * _Scores by school size?_
### * _Scores by school type?_


## Challenge Summary
	
This is a statement summmarizing 4 changes to the school district Analysis after the math and reading scores were replaced
