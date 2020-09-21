# School_District_Analysis

## Project Overview
A chief data scientist for a city school system is responsible for preparing all standardized test data for analysis, reporting, and presentation in order to provide insights on student performance. We have been tasked to aid in this analysis specifically regarding student’s standardized test scores in reading and in math – which we will then assess the funding, and other respective variables in relation to these results. This will entail and extensive report that showcases several high schools, each of their grades, and respective student’s performances and the accompanying trends in funding. 


## Purpose
The analysis we will provide the chief data scientist Maria, will be constructed using Python programming language in addition to the Jupyter Notebook software. Employing these program languages and software’s will allow us to better inform Maria and the inquiring school board on making decision regarding student performance and budget plans. The purpose is to aid the school board in their financial planning and offer insight into analytical patterns given students performances on their standardized tests. After showing maria and her supervisor the report we created, there has been reason to believe that an act of academic dishonesty has been conducted against the ninth grade reading and math scores in Thomas High School. Therefore, we will proceed with our report taking out these grades and comparing the results to observe how this affects the overall analysis.  


## Results
### School District Analysis with Thomas High School Grade 9 Scores 
The School District Summary provide the school board with insight into the overall performance levels and budget for the fifteen schools we are analyzing. As can be observed in the image attached below, we are analyzing at several key factors; total school budget, per student budget, average math and reading scores, the percentage of students passing math and/or reading, as well as the overall percentage of students passing. 
Collectively these schools are receiving a total budget of $24,649,428.00 alongside a total number of 39,170 students respectively. Looking towards the academic performance markers it can be determined that the average math score is 79.0% and the average reading score is 81.9%. Given these markers 75% of students in the district are passing math, 86% of students are passing English, and 65% of students are passing overall. 

![district_summary_without:](./Resources/district_summary_without.png)


### School District Analysis without Thomas High School Grade 9 Scores 
However, upon removing Thomas High School’s grade nine reading and math results from the analysis we observe a slight difference:
Average math score: 78.9% (0.1% decrease) 
Average reading score: 81.9%
% Passing math: 74.8% (0.2% decrease)
% Passing reading: 85.7% (0.3% decrease)
% Overall Passing: 64.9 (0.1% decrease)

![district_summary:](./Resources/district_summary.png)


Therefore, we can make the general assumption that the overall results have only slightly decreased due to the exclusion of the grade nine math and reading grades however, in order to provide insight into the school’s performance without these grades and its effects towards the general statistics it is important to look at a school summary, of which offers more specific insight. 

### School Summary Analysis with Thomas High School Grade 9 Scores 

Average Math Score: 83.418349

Average Reading Score: 83.848930

% Passing Math: 93.272171

% Passing Reading: 97.308869

% Overall Passing: 90.948012

### School Summary Analysis without Thomas High School Grade 9 Scores 
Average Math Score: 83.350937

Average Reading Score: 83.896082

% Passing Math: 93.185690

% Passing Reading: 97.018739

% Overall Passing: 90.630324

By analysing the data provided above it can be determined that the removal of the grade nine grades did not significantly alter the data. The average math and reading scores stayed relatively the same before and after the grades were removed and the same followed for the percentage of students passing these subjects and overall. Therefore, it could be concluded that the grade 9 data did not present as a significant outlier to the analysis in this regard. 
Moreover, relative to other schools Thomas High School still performs as the second highest ranking school regardless of the grade 9 reading and math grades being removed. 

## Analysis
Math and reading scores by grade: Previous to removing the math and reading scores of the grade 9 class the result for both were close to the mean average and presented no significant outlier that would greatly affect the overall average and standing of the school -the grades 10-12 performed at a similar level. 
Scores by school spending: Excluding the ninth grade reading and math scores Thomas High School still performs as the highest school for percentage overall passing within its spending per student range. 
Scores by school size: This high schools is classified as a medium sized school which encapsulates between 1000-2000 students, relative to similarly populated schools Thomas High School performs at a similar rate yet receives the smallest amount of funding amongst other schools classified as medium sized. 
Scores by school type: Thomas High School is a Charter school, relative to other charter schools this high school performs significantly better than district schools, the data without the grade nine scores has not significantly affected this. 

## Summary

