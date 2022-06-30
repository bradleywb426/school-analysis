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

### School Summary

- Given the dishonesty is believed to be localized to 9th Graders in Thomas High School, only the scores for that school have been affected by this updated analysis
- Thomas High School's *Average Math Score* decreased by less than a point
- Thomas High School's *Average Reading Score* increased by less than a point
  - This increase could be why the *Average Reading Score* remained constant in the district summary
- The *% Passing Math* decreased by less than a percent
- The *% Passing Reading* decreased by less than a percent
- The *% Passing Overall* decreased by less than a percent 

<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig2-1.png width="700">
<img src = https://github.com/bradleywb426/school-analysis/blob/main/Resources/fig2-2.png width="700">

### Thomas High School Performance

### Math and Reading Score by Grade

### Scores by School Spending

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

How does replacing the ninth-grade scores affect the following:

Math and reading scores by grade

Scores by school spending

Scores by school size

Scores by school type

Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.

-------------

Each section has a heading and subheading (3 pt).

Links to images are working, and code is formatted and displayed correctly (2 pt).

Analysis (18 points)

The written analysis has the following:

Overview of the school district analysis:

The purpose of this analysis is well defined (3 pt).

Results:

There is a bulleted list that addresses how each of the seven school district metrics was affected by the changes in the data (10 pt).

Summary:

There is a statement summarizing four changes to the school district analysis after reading and math scores have been replaced (5 pt).
