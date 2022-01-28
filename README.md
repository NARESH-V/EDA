# Exploratory Data Analysis

## Problem Statement

### To clean and study the ACT examination data for the year 2018 and 2019 and to visualize the data.

## Datasets Used

**act_2018.csv** - Gives ACT scores for the year 2018.

**act_2019.csv** - Gives ACT scores for the year 2019.


## Data Dictionary


|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|final_data|name of the state in USA| 
|participation_2018|float|Cleaned_Merged_data|ACT-2018 particiption rate| 
|participation_2019|float|Cleaned_Merged_data|ACT-2019 particiption rate| 
|composite_2018|float|Cleaned_Merged_data|ACT-2018 composite score| 
|composite_2019|float|Cleaned_Merged_data|ACT-2019 composite score| 


## Summary
The work starts with importing of the above mentioned datasets. The data cleaning is done, which includes null check, renaming of columns, merging of datasets. Then the cleaned dataset is exported as a CSV file.

The cleaned data is then analyzed and visualized. The observations are made, which are,

Maximum composite in 2018 : 25.6

Minimum composite in 2018 : 17.7

Maximum composite in 2019 : 25.5

Minimum composite in 2019 : 17.9

States with maximum participation in 2018 : 17

States with maximum participation in 2018 : 15

States with maximum participation for each year : 15

States with greater than 50% participation each year : 28

States with composite score greater than 19 in 2018 : 46

States with composite score greater than 19 in 2019 : 41


## Conclusion And Recommendation
The ACT examination data for the years 2018 and 2019 is studied and required observations and trends were analyzed. From the observation it is found that the trends of participation rate and composite score remain almost the same for each year. Where composite score shows inverse relation to participation rate. 

The cleaned data is ready to be an input to a machine learning model which can be used to predict the participation rate and composite score in future.


