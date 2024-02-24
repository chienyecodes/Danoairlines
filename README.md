# Danoairlines

## A Digitaley drive Project
lorem ipsum intro
**_Disclaimer_** : _All datasets and reports do not represent any comapney, Institution or country, but is a dummy dataset to demonstrate capabilities on Power BI._
![]()
This report consists a Dashboard Report (1 page)

## Problem Statement
This Data Analyst aims to provide insights for Dano Airlines, a Uk-based airline headquartered in London, United Kingdom whose latest passenger survey results show a dip in satisfaction rate to below 50% for the first time ever. By analysing various aspects of the survey results, I seek to analyze the data to find the key areas for the leadership team to focus on and give data driven recommendations and insights to get back on track. Some questions to be answered are:


## Data Sources
The primary dataset used for this analysis is the 'airline_data.xlsx' file, containing detailed information about each passenger, their flight, and type of travel, as well as their evaluation of different factors like cleanliness, comfort, service, and overall experience.

## Tools and Skills
### Tools
- PowerBI- Data Cleaning, Data Analysis & Creating Report
### Skills
The following Power BI skills were incorporated-
- DAX
- Calculated Columns
- Filters
- Slicers

## Data Cleaning
In the data cleaning phase, I performed the following tasks:
- Data loading and inspection
- Data cleaning and formatting
- 
Replacing with 0 in numerical columns, or removing null values where necessary
Formating relevant data. Some interesting formulas I worked with were IF statements to categorise the ages and flight length into manageable groups.

Age Group
= IF(airline_passenger_satisfaction[Age]<29,"Young",IF(airline_passenger_satisfaction[Age]<54,"Middle Aged","Elderly"))

Flight length
= IF(airline_passenger_satisfaction[Flight Distance]<1000,"Short",IF(airline_passenger_satisfaction[Flight Distance]<3999,"Medium","Long") )

## Exploratory Data Analysis
EDA involved exploring the survey results to answer key questions, such as:
- Which areas are passengers most unsatisfied with?
-  Does the passenger demographic indicate certain age groups or gender are more unsatisfied than the other?
-  Which key areas need improvement for each ticket class?
-  Which key areas are perceived differently under longer flight conditions?
-  Which key areas were first time travellers most unsatisfied with?
-  Does age group influence pre-flight factors? 

## Results/Findings
lorem ipsum

## Recommendations
lorem ipsum

## Limitations
I had to modify the age and flight distance columns in smaller groups for a meaningful analysis. For age groups, 0-29 years were grouped as adolescents, 30-54 years as middle age and 55+ as elderly. Flight distance, 4000+ km was grouped as a long distance flight, 1001-3999km as medium and 0-1000km as short distance fights.




