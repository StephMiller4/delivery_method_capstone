## DELIVERY METHOD CAPSTONE
The goal of Capstone project is to look at various demographic to try to understand why the cesarean section rate in the US is 2-3 times what the World Health Organization recommends.

### EXECUTIVE SUMMARY
For my capstone project I would like to look at caesarean sections. The World Health Organization recommends countries not exceed 10 to 15 percent but the US was at 32.1% in 2021; up from 20.7 in 1996. I’m curious to investigate how this compares with other developed countries, a breakdown by race in the US and by geographical area. I would like to spend most of my time focused on the US so I will briefly show how the US compares to the world. In addition to my presentation, I am hoping to create an infographic that will clearly tell the story of my data.

### MOTIVATION
This is a topic I became interested in after watching the documentary “The Business of Being Born” and about learning how the US c-section rate is 2-3 times higher than what the WHO recommends but after doing a bit of research I found a map with percentages by state and found that Louisiana, Mississippi, and Florida have the highest percentage of c sections year after year.

### DATA QUESTION
I want to try to understand if there is a correlation to high c-section rates and race and also to income levels. If there is no correlation, I want to do further analysis into why Louisiana, Mississippi, and Florida are always in the top for highest c-section rates.

### CONSIDERATIONS
Using the CDC's WONDER data system I am only able to get up to five variables at a time and because there isn't a unique identifier I have to work with the tables individually instead of merging them to drop columns or rows and then being able to pull out the information I need, I have to drop and rename columns in each table. I also had to do webscraping to get the median income data.

### YEARS EXAMINED: 2016-2019
The CDC's expanded Birth dataset only includes 2016-2019 and this is the dataset with more demographics and information. I made sure all of of my other data was for the same years for an even comparison.  
(This does not include cesarean sections by country as the data from the World Health Organization had various dates for each country. This data was not used in analysis beyond looking at the global rates as a whole.)

### TECHNOLOGIES USED:
##### Python

  - Jupyter Python
  - Pandas
  - Numpy
  - Webscraping and Beautiful Soup
  - Data Cleaning
  - Analysis

##### Excel
  - Pivot Tables
  - Converting .txt file to .csv
  - Offset Function

##### Tableau
  - Graph and Chart creation
  - Dashboard
  - Tableau Story

### FOR FURTHER EXAMINATION:
It would be interesting to take a deeper dive into top and three bottom states individually and also start looking at some of the medical factors such as hypertension and diabetes, especially in the top and bottom states.

### SOURCES:
Centers for Disease Control and Prevention. (2022, February 25). Stats of the states - cesarean delivery rates.
    Centers for Disease Control and Prevention. Retrieved December 1, 2022, from
    https://www.cdc.gov/nchs/pressroom/sosmap/cesarean_births/cesareans.htm

Population distribution by race/ethnicity. KFF. (2022, October 28). Retrieved December 1, 2022, from
    https://www.kff.org/other/state-indicator/distribution-by-raceethnicity/?
    activeTab=graph¤tTimeframe=0&amp;startTimeframe=12&amp;sortModel=%7B%22colId%22%3A%22Location%22
    %2C%22sort%22%3A%22asc%22%7D

Wikimedia Foundation. (2022, May 13). List of U.S. states and territories by income. Wikipedia. Retrieved
    December 3, 2022, from https://en.wikipedia.org/wiki/List_of_U.S._states_and_territories_by_income

World Health Organization. (n.d.). Gho | by category | births by caesarean section - data by country. World Health
    Organization. Retrieved December 3, 2022, from
    https://apps.who.int/gho/data/node.main.BIRTHSBYCAESAREAN?lang=en
