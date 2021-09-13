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
  
  - ***Conclusion: No change observed***
  
- Individual School Summary 
  - The original summary of each individual school:
  ![image](https://user-images.githubusercontent.com/85533099/133024700-eafdc3a2-730b-4599-b641-372c9320e725.png)
  - The summary of each individual school with 9th graders' scores replaced with "NaNs"
  ![image](https://user-images.githubusercontent.com/85533099/133024807-0d842abb-0908-4b4b-a461-93ccecd63eac.png)
  - The updated summary of each individual school with percentages based on only 10th-12th graders from Thomas High School
  ![image](https://user-images.githubusercontent.com/85533099/133024932-80be3357-f6c9-484e-8bd3-900fa0f6016d.png)
  
  - ***Conclusion: Slight changes observed in average math and reading scores and percentages between the original and updated summaries, but not significantly different***
  - ***The middle summary does significantly differ from both the original and updated as these had calculations that included 9th graders in total student counts***

- Summary of the top 5 highest performing schools & the bottom 5 lowest performing schools
  - Original top 5 highest performing schools summary
  ![image](https://user-images.githubusercontent.com/85533099/133025094-3c188894-d053-465b-aa27-4e5c8e0320a5.png)
  - The updated top 5 highest performing schools summary
  ![image](https://user-images.githubusercontent.com/85533099/133025134-fc5b1568-4249-42f1-8993-3645f1f82c6e.png)
  
  - ***Conclusion: Slight changes observed in average math and reading scores and percentages but not significantly different***
  - ***No changes observed for bottom 5 lowest performing schools as expected due to no changes in schools from original analysis***

- Summary of average math scores and average reading scores for each grade level from each school
  - Original math and reading scores by grade
  
  ![image](https://user-images.githubusercontent.com/85533099/133027489-7ba48ac5-c1bb-46a3-ae22-5c8984b93623.png)
  ![image](https://user-images.githubusercontent.com/85533099/133027506-bf015622-0eae-4e0b-8921-b2eec9126aa2.png)


  - Updated math and reading scores by grade
  
  ![image](https://user-images.githubusercontent.com/85533099/133025642-a24fd149-e965-4880-bbe2-73e15d8d644d.png)
  ![image](https://user-images.githubusercontent.com/85533099/133025720-123d63eb-6d47-4c70-af19-d4b5aa7d3569.png)
  
  - ***Conclusion: Changes observed in updated summary where Nan appears in both updated summaries for 9th graders at Thomas High School***
  
- Summary of scores by school spending per student
  - Original scores by school spending per student -- exact numbers and rounded to nearest whole numbers
    ![image](https://user-images.githubusercontent.com/85533099/133026284-b830f80c-293d-4d87-b1b5-6b74af433a68.png)
    ![image](https://user-images.githubusercontent.com/85533099/133026269-10f3ccf9-56a2-484b-b65c-1bee01ca431d.png)
  - Updated scores by school spending per student -- exact numbers and rounded to nearest whole numbers
    ![image](https://user-images.githubusercontent.com/85533099/133026370-244a8ff1-0749-4925-9de1-e05e707e96b7.png)
    ![image](https://user-images.githubusercontent.com/85533099/133026380-9de05751-e8ef-4bd3-a780-a1d79d514f55.png)
    
  - ***Conclusion: Slight changes observed when comparing exact numbers obtained in the "$630-644" bin that includes Thomas High School***
  - ***No changes observed for other bins due to no changes in schools within these bins from original analysis***

- Summary of scores by school size
  - Original scores by school size -- exact numbers and rounded to nearest whole numbers
  
  ![image](https://user-images.githubusercontent.com/85533099/133026629-56eea832-b9f0-4910-8b59-2bc29a650ca5.png)
  ![image](https://user-images.githubusercontent.com/85533099/133026634-0b47aa7d-dd4a-4347-be08-ff7a93506eb5.png)
  
  - Updated scores by school size -- exact numbers and rounded to nearest whole numbers
  
  ![image](https://user-images.githubusercontent.com/85533099/133026657-2b9ac895-813f-479b-91f8-5af9af18e9c0.png)
  ![image](https://user-images.githubusercontent.com/85533099/133026664-23dad751-13d8-491c-8557-7f7a71bb81c4.png)
 
  - ***Conclusion: Slight changes observed when comparing exact numbers obtained in the "Medium" bin that includes Thomas High School***
  - ***No changes observed for other bins due to no changes in schools within these bins from original analysis***

- Summary of scores by school type
  - Original scores by school type -- exact numbers and rounded to nearest whole numbers
  ![image](https://user-images.githubusercontent.com/85533099/133026801-d6dcfb4e-23ba-43a0-97f1-2601a2b74e01.png)
  ![image](https://user-images.githubusercontent.com/85533099/133026808-fdc73cd8-50d4-4fcd-aa6d-ebe7ed0ef599.png)
  
  - Updated scores by school type -- exact numbers and rounded to nearest whole numbers
  ![image](https://user-images.githubusercontent.com/85533099/133026837-a777ccb7-949f-4eab-8458-5c38800e9dfa.png)
  ![image](https://user-images.githubusercontent.com/85533099/133026844-c11987d1-21ba-4b20-8262-1320478952dc.png)
  
  - ***Conclusion: Slight changes observed when comparing exact numbers obtained in the "Charter" bin that includes Thomas High School***
  - ***No changes observed for the "District" bin due to no changes in schools within this bin from original analysis***



