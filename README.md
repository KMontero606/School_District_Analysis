# School_District_Analysis

## Overview of the school district analysis:
#### There was evidence of academic dishonesty, specifically, reading and math grades for Thomas High School ninth graders which appears to have been altered. Although the full extent of the academic dishonesty is unknown, the school board want to uphold state-testing standards and have requested help to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact. Once the math and reading scores have been replaced, replicate the school district analysis and write up a report to describe how the changes affected the overall analysis.

## Results: Using bulleted lists and images of DataFrames as support, address the following questions.

- How is the district summary affected?
  
  After performing the school district analysis with the adjusted math and reading grade scores, the district summary report yield no significant change. At most, the difference between the initial and adjusted summaries is no more than 0.3%.
  
  Initial District Report:
  
  <img width="695" alt="Initial District Summary" src="https://user-images.githubusercontent.com/106962921/177086082-6ea71a66-65b1-4900-8f2a-ca418aec47f4.png">
  
  Adjusted District Report:
  
  <img width="694" alt="Adjusted District Summary" src="https://user-images.githubusercontent.com/106962921/177086272-04b206ae-5bf3-42ef-a718-1f74bbdb4e01.png">

- How is the school summary affected?

  The school summary analysis with the adjusted math and reading grade scores yield very significant change where the passing math and reading percentages are at 93% and 97% respectively from 67% and 70% repectively and overall passing percentage at 91% from 65%.
  
  Initial School Summary:
  
  <img width="723" alt="Initial School Summary" src="https://user-images.githubusercontent.com/106962921/177169889-63174137-ff98-4fae-b325-125226fb756b.png">

  Adjusted School Summary:
    
  <img width="721" alt="Adjusted School Summary" src="https://user-images.githubusercontent.com/106962921/177170097-eb8544ed-3ce3-4d36-a371-5ed66b7d9ff3.png">

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

  Replacing the ninth-grade scores for Thomson High school placed the school in the top five schools for high performing schools.
  
  <img width="722" alt="Adjusted Top 5 Schools" src="https://user-images.githubusercontent.com/106962921/177179528-80bcd01d-dafd-4e00-959f-49c2016e7326.png">

* How does replacing the ninth-grade scores affect the following:
  
  * Math and reading scores by grade

  <img width="225" alt="Math Scores by Grade" src="https://user-images.githubusercontent.com/106962921/177181766-ae6f7ddd-98f2-4c99-bd3d-854d403eff9e.png">

  <img width="225" alt="Reading Scores by Grade" src="https://user-images.githubusercontent.com/106962921/177181782-68e7e94e-5383-426e-b58a-e23750ac1fcd.png">

  * Scores by school spending

  <img width="724" alt="Scores by School Spending" src="https://user-images.githubusercontent.com/106962921/177181857-631379b5-e401-42b9-92ed-f072248d4af9.png">

  <img width="613" alt="Spending Summary" src="https://user-images.githubusercontent.com/106962921/177192246-8e5dd5c6-59af-46b2-8a00-1689e677154d.png">

  * Scores by school size

  <img width="722" alt="Scores by School Size" src="https://user-images.githubusercontent.com/106962921/177182060-92d1fc44-72e3-4822-b2c4-564fb4f59dba.png">

  <img width="565" alt="Size Summary" src="https://user-images.githubusercontent.com/106962921/177192290-49431631-04be-4662-869f-34f459725f10.png">

  * Scores by school type

  <img width="530" alt="Scores by School Type" src="https://user-images.githubusercontent.com/106962921/177181921-257befc9-d04a-4806-900a-ac8280874de5.png">

## Summary: 
  There are at least four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced 
  with NaNs:

1. The passing percentage for both subjects change from the 60% range to the 90% range.   
2. Thomson High School went from the bottom perfoming school to the top five performing schools.    
3. Since the 9th graders scores from Thomson High School were ommitted, the math and reading scores by grade average are at 80% range.
4. The overall passing percentage for Thomas High School students are at 63% by school spending, 91% by school size and 90% by school type.

## Resources:
  Anaconda (PythonData), Jupyter Notebook, Git Bash
  
  students_complete.csv & schools_complete.csv
