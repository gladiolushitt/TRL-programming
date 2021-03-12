# Readme

This dataset was created for a Data Cutation course at the University of Washington's iSchool during Winter Quarter of 2021. The dataset breaks down the raw data of Timberland Regional Libraries' 2020 - 2021 programming alphabetically and by month and year. The intended audience of this dataset are researchers interested in the effect of the pandemic on TRL programming offerings and attendance. This dataset can also be used by policymakers to whant evidence of TRL's programming and outreach. 

The dataset is available in .csv and .xlxs format. Within the dataset there are twelve sheets that break down the original 1447 cells in the raw dataset pulled from https://catalog.data.gov/dataset/timberland-regional-library-programs. This was done to make browsing and finding specific content within the data easier. While the raw data was organized alphabetically and by year, it was not organized by month. Having multiple sheets ensured that there were no duplilcate variables. Most fields are filled in. Blank fields under Attendance have been left open as it probably correlates to an absence of data collected, rather than a default of zero as zero attendance is marked with the corresponding numerical value.  

## Table of Contents

- [Naming](#naming)
- [Data Dictionary](#datadictionary)
- [Contact](#contact)

## Naming

Naming convention follows the original convention of the raw dataset, Timberland_Regional_Library_Programs, with the addition of "Monthly" to denote the main organization difference: Monthly_Timberland_Regional_Library_Programs 

## Data Dictionary


| **Variable** | **Variable Name** | **Measurement Unit** | **Allowed Values** | **Definition** |
| --- | --- | --- | --- | --- |
| **Library** | **Library** | **Plain Text** | **Library names, including TRL branches, all locations, and online events** |
| **Event Year** | **Event Year** | **Numerical** | **Year in which the event occured** |
| **Event Month** | **Event Month** | **Numerical** | **Month in which the event occured** |
| **Category** | **Category** | **Plain Text** | **Type of event/program** |
| **Age Group** | **Age Group** | **Plain Text** | **Specific age group demographic of event's target audience**  |
| **Events** | **Events** | **Numerical** | **Number of events** |
| **Attendance** | **Attendance** | **Numerical** | **Number of people attending events** |


## Contact

Gladys Hitt at hittg@uw.edu

