# School_District_Analysis

## Overview of School District Analysis
The initial purpose of the school district analysis was to assist in providing important summary data about the performance of schools within a school district based upon results of standardized testing scores, i.e., math and reading scores. This analysis was completed and included several important key deliverables:
- School District Summary
- Individual School Summary
- Summary of the top 5 highest performing schools & the bottom 5 lowest performing schools
- Summary of average math scores and average reading scores for each grade level from each school
- Summary of scores by school spending per student
- Summary of scores by school size
- Summary of scores by school type

Due to the discovery of evidence pointing to academic dishonesty within the 9th grade class of Thomas High School, a new analysis plan was formulated to assist the school board by (1) replacing Thomas High School's 9th grade math and scores with "NaNs" (signifying a lack of data) and (2) repeating the above school district analysis to provide an updated version of the same key deliverables. 

## Resources
- Data Sources: schools_complete.csv & students_complete.csv
- Software: Python 3.7.10, Anaconda 1.7.2, Jupyter Notebook, Pandas, NumPy

## Results 
The following results depict how each of the above seven school district metrics were affected by the changes that were conducted to account for removal of Thomas High School's 9th grade math and reading scores.

- School District Summary 
  - The original district summary:
  ![image](https://user-images.githubusercontent.com/85533099/133024401-c24620f0-acec-4ba0-9ec6-7ecaa10d33bf.png)
  - The updated district summary where 9th graders' data for math and reading scores were replaced with "NaNs":
  ![image](https://user-images.githubusercontent.com/85533099/133024475-d9b034f3-8abb-48b5-9de8-71ea237f771b.png)
    - **No change observed
  
- Individual School Summary 
  - The original summary of each individual school:
  ![image](https://user-images.githubusercontent.com/85533099/133024700-eafdc3a2-730b-4599-b641-372c9320e725.png)
  - The summary of each individual school with 9th graders' scores replaced with "NaNs"
  ![image](https://user-images.githubusercontent.com/85533099/133024807-0d842abb-0908-4b4b-a461-93ccecd63eac.png)
  - The updated summary of each individual school with percentages based on only 10th-12th graders from Thomas High School
  ![image](https://user-images.githubusercontent.com/85533099/133024932-80be3357-f6c9-484e-8bd3-900fa0f6016d.png)
    - **Slight changes observed in average math and reading scores and percentages, but not significantly different*

- Summary of the top 5 highest performing schools & the bottom 5 lowest performing schools
  - Original top 5 highest performing schools summary
  ![image](https://user-images.githubusercontent.com/85533099/133025094-3c188894-d053-465b-aa27-4e5c8e0320a5.png)
  - The updated top 5 highest performing schools summary
  ![image](https://user-images.githubusercontent.com/85533099/133025134-fc5b1568-4249-42f1-8993-3645f1f82c6e.png)
    - **Slight changes observed in average math and reading scores and percentages but not significantly different*
    - **No changes observed for bottom 5 lowest performing schools as expected due to no changes in schools from original

- Summary of average math scores and average reading scores for each grade level from each school
  - Original math and reading scores by grade
  ![image](https://user-images.githubusercontent.com/85533099/133025593-475bb066-a972-4ee3-a8e6-39018f957d18.png)
  ![image](https://user-images.githubusercontent.com/85533099/133025694-ca639b9f-70d7-4a5f-a90c-750340678352.png)
  - Updated math and reading scores by grade
  ![image](https://user-images.githubusercontent.com/85533099/133025642-a24fd149-e965-4880-bbe2-73e15d8d644d.png)
  ![image](https://user-images.githubusercontent.com/85533099/133025720-123d63eb-6d47-4c70-af19-d4b5aa7d3569.png)
    - **Changes observed in for Thomas High School 9th graders where Nan appears in both summaries
  - 
  
- Summary of scores by school spending per student
- Summary of scores by school size
- Summary of scores by school type



