# Kickstarting with Excel

## Overview of Project

### This project was created to analyze Kickstarter data by using different tools available in Excel. The goal of this analysis is to know how different campaigns fared in relation to their launch dates and their funding goals to help Louise and her play *Fever*. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date 
This analysis was made in order to find out if launching a theater kickstarter campaign in a particular month can help it become successful. In order to do this, I analyzed the Kickstarter data by filtering all campaigns in the theater subcategory and creating a pivot table to see the outcomes based on month of campaign created. Here is the result:

![Theater Outcomes_Vs_Launch](https://raw.githubusercontent.com/ziye249235/Kickstarter-challenge/master/Resources/Theater_Outcomes_vs_Launch.png)

We can analyze based on the result chart that the month of May has historically had the most successful theater kickstarted campaigns. There is no month where there is a significant higher amount of failed or canceled campaigns. 

### Analysis of Outcomes Based on Goals
This analysis was made in order to find out whether setting a higher or lower goal for kickstarters with a play subcategory can affect the outocme of whether it will be successful. In order to do this, I analyzed the Kickstarter data by counting the outcomes of successful, failed and canceled campaigns based on a goal $ range for all play kickstarters. Here is the result:

![outcomes based on Goals](https://raw.githubusercontent.com/ziye249235/Kickstarter-challenge/master/Resources/Outcomes_vs_Goals.png)


### Challenges and Difficulties Encountered

There were no particular challenges encountered when analyzing the outcomes based on launch date, but one could potentially encounter challenges when performing this analysis by not correctly inputing the fields in the pivot table and by not grouping the Kickstarter campaign launch dated by month, which would make the line graph visualization much more clustered with data from every date and decrease its value. 

There were also no particular challenges encountered when analyzing the outcomes based on goals, but one could potentially encounter challenges when performing this analysis by not using the *countifs* function properly and therefore generating an underlying table to the the graph with an incorrect or incomplete population of all play campaigns or by counting a play campaign twice. 

## Results


Here are two conclusions drawn from the Outcomes based on Launch Date analysis:

1. The month of May has historically had the most successful theater kickstarted campaigns. 
2. There is no month where there is a significant higher amount of failed or canceled campaigns. 

We can conclude based on the Outcomes based on Goals analysis that generally, the higher the pledge goal, the lower the chances of the campaign being successful. 

The dataset includes the following limitations: 

1. It is limited to campaigns between 2009 and 2017
2. It is limited to english-speaking and certain European countries

The following are some other tables and/or graphs that we could create:

1. Outcome of Kickstarter campaigns based on country
2. Average pledge amount of all campaign categories, based on outcome (successful, failed) 
3. Percentage of caipaign outcomes based on average pledge

