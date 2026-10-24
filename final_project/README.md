# The Impact of Age, Nationality, and Race Location on Marathon Performance
Analysis and Visualization Data to support how age, nationality and race location affect one's marathon performance.

## Problem Statement
How do age, nationality, and race location influence marathon performance? Given a table of marathon times in order, analyze how other factors influence one's performance

## Dataset
-Source: [marathon.csv](https://www.kaggle.com/datasets/evgenyarbatov/marathon-running-times)

## Cleaning Log
1) Removed Missing Values
* Found 188 rows with missing values, but removed all of them since sample size was big enough and those missing values cannot be filled with median or mean values.
2) Type Conversions
* Converted the data types of 'Date of Birth' and 'Date' from str to datetime for better calculations and analysis.
* Converted the data type of 'Place' from str to int for better calculations and analysis.

## Key Findings
1) Based on the boxplot and the correlation, there isn't much relation between age and marathon time.

2) Based on the bar graph, Kenya and Ethiopia definitely have a high number of first-place finishes and both of their sample size is huge as well (5314 and 3967 respectively). Although it is incorrect to say that all marathon runners from Kenya and Ethiopia finish first place, it is very likely that runners from those two countries will win the race.

3) Based on the heatmap, mean and median values for the top 10 cities with the most runners, it is likely that runners would perform better at Seoul Marathon than they would at Osaka Marathon.

## Tech Stack
- python
- pandas
- matplotlib
- seaborn
