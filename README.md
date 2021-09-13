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
  
  ![image](https://user-images.githubusercontent.com/85533099/133115610-3c8fee57-05e2-47af-9d44-b09b25966dc7.png)
  
  - The updated district summary where 9th graders' data for math and reading scores were replaced with "NaNs":
  
  ![image](https://user-images.githubusercontent.com/85533099/133024475-d9b034f3-8abb-48b5-9de8-71ea237f771b.png)
  
  - ***Conclusion: Slight changes observed in average math score and all percentages between the original and updated district summaries***
  - ***No observed change in average reading score between the original and district summaries***
  
- Individual School Summary 
  - The original summary of each individual school (1):
  ![image](https://user-images.githubusercontent.com/85533099/133024700-eafdc3a2-730b-4599-b641-372c9320e725.png)
  - The summary of each individual school with Thomas High School 9th graders' scores replaced with "NaNs" (2):
  ![image](https://user-images.githubusercontent.com/85533099/133024807-0d842abb-0908-4b4b-a461-93ccecd63eac.png)
  - The updated summary of each individual school with percentages based on only 10th-12th graders from Thomas High School (3):
  ![image](https://user-images.githubusercontent.com/85533099/133024932-80be3357-f6c9-484e-8bd3-900fa0f6016d.png)
  
  - ***Conclusion: Slight changes observed in average math and reading scores and percentages between the original (1st image) and updated (3rd image) summaries***
  - ***The 2nd summary does significantly differ from both the original (1st image) and updated (3rd image) summaries as the 2nd summary had calculations that included 9th graders in total student counts***

- Summary of the top 5 highest performing schools & the bottom 5 lowest performing schools
  - Original top 5 highest performing schools summary
  ![image](https://user-images.githubusercontent.com/85533099/133025094-3c188894-d053-465b-aa27-4e5c8e0320a5.png)
  - The updated top 5 highest performing schools summary
  ![image](https://user-images.githubusercontent.com/85533099/133025134-fc5b1568-4249-42f1-8993-3645f1f82c6e.png)
  
  - ***Conclusion: Slight changes observed in average math and reading scores and percentages***
  - ***No changes observed for bottom 5 lowest performing schools as expected due to no changes in schools from original analysis***

- Summary of average math scores and average reading scores for each grade level from each school
  - Original math and reading scores by grade
  
  ![image](https://user-images.githubusercontent.com/85533099/133027489-7ba48ac5-c1bb-46a3-ae22-5c8984b93623.png)
  ![image](https://user-images.githubusercontent.com/85533099/133027506-bf015622-0eae-4e0b-8921-b2eec9126aa2.png)


  - Updated math and reading scores by grade
  
  ![image](https://user-images.githubusercontent.com/85533099/133025642-a24fd149-e965-4880-bbe2-73e15d8d644d.png)
  ![image](https://user-images.githubusercontent.com/85533099/133025720-123d63eb-6d47-4c70-af19-d4b5aa7d3569.png)
  
  - ***Conclusion: Changes observed in updated summary, i.e., Nan appears in both updated summaries for 9th graders at Thomas High School***
  
- Summary of scores by school spending per student
  - Original scores by school spending per student -- exact numbers and rounded to nearest whole numbers
    ![image](https://user-images.githubusercontent.com/85533099/133026284-b830f80c-293d-4d87-b1b5-6b74af433a68.png)
    ![image](https://user-images.githubusercontent.com/85533099/133026269-10f3ccf9-56a2-484b-b65c-1bee01ca431d.png)
  - Updated scores by school spending per student -- exact numbers and rounded to nearest whole numbers
    ![image](https://user-images.githubusercontent.com/85533099/133026370-244a8ff1-0749-4925-9de1-e05e707e96b7.png)
    ![image](https://user-images.githubusercontent.com/85533099/133026380-9de05751-e8ef-4bd3-a780-a1d79d514f55.png)
    
  - ***Conclusion: Slight changes observed when comparing exact numbers obtained in the "$630-644" bin that includes Thomas High School***
  - ***No changes observed when numbers were rounded up to whole percentages***
  - ***No changes observed for other bins due to no changes in schools within these bins from original analysis***

- Summary of scores by school size
  - Original scores by school size -- exact numbers and rounded to nearest whole numbers
  
  ![image](https://user-images.githubusercontent.com/85533099/133026629-56eea832-b9f0-4910-8b59-2bc29a650ca5.png)
  ![image](https://user-images.githubusercontent.com/85533099/133026634-0b47aa7d-dd4a-4347-be08-ff7a93506eb5.png)
  
  - Updated scores by school size -- exact numbers and rounded to nearest whole numbers
  
  ![image](https://user-images.githubusercontent.com/85533099/133026657-2b9ac895-813f-479b-91f8-5af9af18e9c0.png)
  ![image](https://user-images.githubusercontent.com/85533099/133026664-23dad751-13d8-491c-8557-7f7a71bb81c4.png)
 
  - ***Conclusion: Slight changes observed when comparing exact numbers obtained in the "Medium" bin that includes Thomas High School***
  - ***No changes observed when numbers were rounded up to whole percentages***
  - ***No changes observed for other bins due to no changes in schools within these bins from original analysis***

- Summary of scores by school type
  - Original scores by school type -- exact numbers and rounded to nearest whole numbers
  ![image](https://user-images.githubusercontent.com/85533099/133026801-d6dcfb4e-23ba-43a0-97f1-2601a2b74e01.png)
  ![image](https://user-images.githubusercontent.com/85533099/133026808-fdc73cd8-50d4-4fcd-aa6d-ebe7ed0ef599.png)
  
  - Updated scores by school type -- exact numbers and rounded to nearest whole numbers
  ![image](https://user-images.githubusercontent.com/85533099/133026837-a777ccb7-949f-4eab-8458-5c38800e9dfa.png)
  ![image](https://user-images.githubusercontent.com/85533099/133026844-c11987d1-21ba-4b20-8262-1320478952dc.png)
  
  - ***Conclusion: Slight changes observed when comparing exact numbers obtained in the "Charter" bin that includes Thomas High School***
  - ***No changes observed when numbers were rounded up to whole percentages***
  - ***No changes observed for the "District" bin due to no changes in schools within this bin from original analysis***

## Analysis Summary
The results of the analysis revealed some changes when comparing exact numbers obtained in the original analysis summaries and the updated analysis summaries. Below are examples of these changes:
- The updated School District Summary showed a slight reduction from the original District Summary in the "Average Math Score" (79.0 to 78.9), "% Passing Math" (75.0% to 74.8%), "% Passing Reading (85.8% to 85.7%), and "Overall Passing" (65.2% to 64.9%)
- When 9th graders' math and reading scores were replaced with "NaNs", the "Average Math Score" and "Average Reading Score" slightly reduced from the original District summary. However, there was a dramatic reduction in the data showing percentages from the original District Summary, i.e., "% Passing Math" (93.27% to 66.91%), "% Passing Reading (97.31% to 69.66%), "% Overall Passing" (90.95% to 65.08%). 
  - This is why it was essential to then conduct a follow-up analysis to adjust the percentages to include a new total student count that eliminated the 9th graders (n = 461),  so that the results were not skewed in a negative direction. Once the calculations were adjusted to include only the 10th - 12th graders, the results revealed slight reductions in the updated District summary from the original District Summary for "Average Math Score" (83.42% to 83.35%), "% Passing Math" (93.27% to 93.19%), "% Passing Reading (97.31% to 97.02%), "% Overall Passing" (90.95% to 90.63%). Only one score, "Average Reading Score", revealed an increase from the original District Summary, i.e., 83.85% to 83.90%.
  - These same changes are apparent when viewing the top 5 highest performing schools because the data that is generated for that summary is the same as the above. However, because the change in numbers was slight, this did not change the outcome for Thomas High School as it still was observed to rank second in the top 5 highest performing schools.
- The updated summary for reading and math scores by grade demonstrate how the 9th graders from Thomas High School all were replaced with NaNs, whereas the original summary indicates an average math score of 83.6 and an average reading score of 83.7. 
- For the spending ranges summaries that included exact numbers, only the bin for "$630-644" changed since Thomas High School was grouped into that bin (for example, "Average Math score" reduced from 78.52 to 78.50; "Average Reading Score" increased from 81.62 to 81.64; and "% Passing Reading" reduced from 84.39% to 84.32%). However, when the summaries were formatted to round up to the nearest whole numbers for all scores and percentages, there was no change between the original and the updated summaries. 
- Similarly for the school size and school type summaries that included exact numbers, only the bins for "Medium (1000-2000)" and "Charter" changed because Thomas High School was grouped into that bin. For example, "% Overall Passing" reduced from 90.62% to 90.56% in the updated school size summary for the "Medium" bin and the "% Overall Passing" changed from 90.43% to 90.39% in the "Charter" school type. However, for the summaries that were formatted to round up to the nearest whole numbers for all scores and percentages, there was no change observed between the original and the updated summaries. 
- Therefore the school board can be reassured to know that the challenges brought on by the discovery of academic dishonesty did not affect their overall findings of their students' academic performance and that, for the most part, the original analyses did yield similar data as the updated analyses. 




