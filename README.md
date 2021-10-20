# School District Analysis 
Performing an analysis using school and student data to inform a school district on the status of their Key Performance Indiators, in order to help them determine their future budget and priorities.

---------

# Challenge
The school district discovered that the standardized test scores for ninth grade students at Thomas High School were incorrect (potentially altered), and they requested updated data summaries. On reviewing the options for managing the data within the set, it was determined that the best option was to replace the scores for reading and math of Thomas High School 9th graders with "NaN" - which represents a "Not-a-Number" value. This affected 461 student records from Thomas High School, while keeping all other data associated with this student group intact. 


## Analysis Results 
A thorough analysis of scores was done after replacing the Thomas High School 9th Grade scores with NaN. As all of the ninth graders from Thomas High School had their scores replaced, the particular focus of the analysis was to determine how the adjustment affected the school district analysis scores. 

Key areas of focus were:
- District Summary
- School Summary
- Top Five Performing Schools
- Bottom Five Performing Schools
- Average Math Score for Each Grade Level
- Average Reading Score for Each Grade Level
- Scores by School Spending
- Scores by School Size
- Scores by School Type


### I. District Summary
Using the original formatting provided by Maria* (grade percentages to the nearest whole number percent), the district summary was unaffected by the removal of the Thomas High School 9th grade scores. 

Original:
<img width="930" alt="District_Before" src="https://user-images.githubusercontent.com/87709841/138018738-72a1f7da-da40-4783-93f8-202cb626abe3.png">    
THS 9th Grade Scores Removed:
<img width="930" alt="District_After_Consistent_Format" src="https://user-images.githubusercontent.com/87709841/138018803-b965111f-603d-45ec-9e30-30c8282cf41c.png">


### II. School Summary
From a school summary perspective, all schools aside from Thomas High School retained the same data, therefore were not impacted by the analysis.  
Overall School Summary:
<img width="1024" alt="SchoolSummary_AfterNaN" src="https://user-images.githubusercontent.com/87709841/138019784-adbe3cce-ea4c-4174-bb1c-88eb262419c8.png">

A deeper dive into Thomas High School shows minimal change in their overall scores once the 9th grade scores had been removed and the remaining 10th-12th grade scores were calculated. Relative to other schools, there was minimal change to their scoring.   
THS Original Analysis:
<img width="890" alt="THS_BeforeNaN_1" src="https://user-images.githubusercontent.com/87709841/138020408-f83a7969-c6ae-4eea-adef-42deaf55f100.png">   
THS 9th Grade Scores Removed:  
<img width="990" alt="THS_AfterNaN" src="https://user-images.githubusercontent.com/87709841/138020501-fb4475a7-5534-416a-a3dc-eac59e8754cb.png">


### III. Top Five Performing Schools
<img width="1024" alt="IMG3_TopFiveSchools" src="https://user-images.githubusercontent.com/87709841/138000925-6be812ae-7457-4e9a-8edd-afb5a4e4e3bf.png">


### IV. Bottom Five Performing Schools
<img width="1024" alt="IMG4_BottomFiveSchools" src="https://user-images.githubusercontent.com/87709841/138000957-144aec61-274a-4900-9e20-73aeaeabd396.png">


### V. Average Math and Average Reading Scores by Grade and School
**Math** <img width="322" alt="IMG5_MathBySchool_Grade" src="https://user-images.githubusercontent.com/87709841/138000996-a8ccc669-0989-4191-8b99-bd47dbe48bd4.png"> **Reading** <img width="322" alt="IMG6_ReadingBySchool_Grade" src="https://user-images.githubusercontent.com/87709841/138001006-917835d5-6b0c-45eb-ae05-dce73fbdf83c.png">


### VI. School Spending Summary
A look at the school spending summary shows that the more spent per capita does not equate to higher scores. 
<img width="856" alt="IMG7_ScoresBySchoolSpending" src="https://user-images.githubusercontent.com/87709841/138001015-c59a6f14-a29a-4cb0-9d75-a3252262b989.png">


### VII. School Size Summary
Students at smaller to medium size schooled tended to score higher than their peers at large schools.
<img width="782" alt="IMG8_ScoresBySchoolSize" src="https://user-images.githubusercontent.com/87709841/138001023-037c853a-46ec-4d43-ad01-6bf52811111d.png">


### VIII. School Type Summary
Charter schools showed a much higher overall passing rate than district schools.
<img width="720" alt="IMG9_ScoresBySchoolType" src="https://user-images.githubusercontent.com/87709841/138001030-5c8d97ee-78ba-4c30-9acb-e447ab3fd603.png">


## Summary
Reviewing the analysis of the school district metrics after replacing the Thomas High School ninth-graders' scores with the value "NaN" **AND** retaining the starter code provided, showed four noted changes to the district metrics as compared to the original:

1. The average math exam score for the district was one-tenth of a percentage point lower while the readiing score remained the same.
2. The percentage of students passing math was lowered by two-tenths of a percentage point.
3. The percentage of students passing reading was lowered by three-tenths of a percentage point.
4. The percentage of students passing both math and reading for the districts was lowered by one-tenth of a percentage point.
<img width="930" alt="District_Before" src="https://user-images.githubusercontent.com/87709841/138022465-cb5b2591-c0d3-44de-8cff-aa1dfb3f0406.png">  
<img width="935" alt="District_After_Challenge" src="https://user-images.githubusercontent.com/87709841/138022346-ea2a7e9e-10fa-4f70-aa73-3cd037c7261b.png">

A review of the Thomas High School score differences showed less than 1% difference between each of the KPI before 9th grade score removal and after removal metrics, with the overall trend toward decreasing scores.

- 0.08% difference in math scores (decrease)
- 0.06% difference in reading scores (increase)
- 0.09% difference in percentage passing math (decrease)
- 0.30% difference in percentage passing reading (decrease)
- 0.35% difference in percentaget passing, overall (decrease)


Reference: [4.7.8 Format Columns](https://courses.bootcampspot.com/courses/811/pages/4-dot-7-8-format-columns?module_item_id=301047)
