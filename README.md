# An Analysis of Standard Testing Results

Analyzing the results of state tests in Math and Reading for fifteen schools in a school district, reporting on results based on a variety of metrics, and adjusting results to account for academic dishonesty

## Resources

- Data:
  - schools_complete.csv
  - students_complete.csv
- Software: Jupyter Notebooks 6.4.8

## Overview

A School Board has asked for data from recent standardized state math and reading test for 9th to 12th graders in a district to be analyzed for any trends to assist the Board in making budgetary decisions. The Board then further asks for the same analysis of data, except excluding any results that may be related to cases of academic dishonesty. These reports of academic dishonesty were localized in the 9th grade of Thomas High School, and as such the entire 9th grade for Thomas High School as been expunged from the new analysis.

## Results

### District Summary

By accounting for the dishonesty:
- The *Average Math Score* decreases by less than a point
- The *Average Reading Score* remains constant
- The *% Passing Math* decreases by less than a percent
- The *% Passing Reading* decreases by less than a percent
- The *% Passing Overall* decreses by less than a percent

<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig1-1.png width="800">
<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig1-2.png width="800">

-----

### School Summary

Given the dishonesty is believed to be localized to 9th Graders in Thomas High School, only the scores for that school have been affected by this updated analysis.
- Thomas High School's *Average Math Score* decreased by less than a point
- Thomas High School's *Average Reading Score* increased by less than a point
  - This increase could be why the *Average Reading Score* remained constant in the district summary
- The *% Passing Math* decreased by less than a percent
- The *% Passing Reading* decreased by less than a percent
- The *% Passing Overall* decreased by less than a percent 

<p>
  <img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig2-1.png width="700">
  
  <em>The above graph displays the original scores by school.</em>
</p>

<p>
  <img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig2-2.png width="700">
  
  <em>The above graph displays the adjusted scores by school.</em>
</p>

-----

### Thomas High School Performance

- Given the slight changes to Thomas High School's scores, their ranking compared to other school's scores is unchanged

<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig7-1.png width="800">
<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig7-2.png width="800">

-----

### Math and Reading Score by Grade

- Since the entirity of 9th Grade scores for Thomas High School were removed, only those values change and go from low 80s to null values.

- The original Math and Reading scores are the first two data sets, while the updated Math and Reading Scores are the last two data sets

<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig3-1-1.png width="220"> <img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig3-1-2.png width="220"> <img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig3-2-1.png width="220"> <img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig3-2-2.png width="220">

-----

### Scores by School Spending

- The scores remain constant when viewed by school spending

<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig4-1.png width="800">
<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig4-2.png width="800">

-----

### Scores by School Size

- The scores remain constant when viewed by school size

<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig5-1.png width="800">
<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig5-2.png width="800">

-----

### Scores by School Type

- The scores remain constant when viewed by School Type

<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig6-1.png width="800">
<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig6-2.png width="800">

-----

## Summary

To summarize, removing the scores of the 9th Graders at Thomas High School to address the academic dishonesty in said grade level tended to result in small decreases in *Average Reading Scores* and *% Passing* values, and either small increases to or no change to *Average Reading Score* when the updated analysis is viewed at the district and school levels. When the updated analysis is viewed in other slices of data, such as by school size or type, there is no visible change in scores. When viewed by grade level, the only change is the null values for 9th grade scores in Thomas High School.
