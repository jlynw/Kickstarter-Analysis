# Kickstarter with Excel
## Overview of Project
### Purpose
The purpose of this to organize the data in a way that will allow us to observe trends and gain information. This will then enable us to have a better understanding of what makes a successful campaign. 
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date

The pivot table shows the outcomes of theater campaigns based on their launch date. "Parent Category" and "Years" were added to Filter to enable us to see theater campaigns only. "Outcomes" were added to Columns and Values to see the number of successful, failed, and canceled campaigns. "Date Created Conversion" was added to Rows to see the number of outcomes sorted by months.

![screenshot_outcomes_vs_date_pivot.png](https://github.com/jlynw/Kickstarter-Analysis/blob/main/Screenshots/screenshot_outcomes_vs_date_pivot.PNG)

This pivot table was then used to create a visualization of trends of outcomes based on launch date. We can see the three trends of outcomes based on date.
![Theater_Outcomes_vs_Launch.png](https://github.com/jlynw/Kickstarter-Analysis/blob/main/Resources/Theater_Outcomes_vs_Launch.png)


### Analysis of Outcomes Based on Goals

The table below shows an analysis of successful, failed, and canceled campaigns. This was created by using the "=COUNTIF ()" function to obtain the number of successful, failed, and canceled outcomes based on the campaign goal from the Kickstarter worksheet. The counts of outcomes were then used to calculate the percentages of outcomes based on the goal.
![screenshot_outcomes_vs_goals.png](https://github.com/jlynw/Kickstarter-Analysis/blob/main/Screenshots/screenshot_outcomes_vs_goals.PNG)

The calculations from the table pictured above was used to create a visualiztion of the three types of outcomes based on the twelve different goals.
![Outcomes_Based on Goals.png](https://github.com/jlynw/Kickstarter-Analysis/blob/main/Resources/Outcomes%20Based%20on%20Goals.png)


### Challenges and Difficulties Encountered

A difficulty I encountered was trying to create the pivot table. The pivot table I created included the "live" outcome in the column. I tried to delete the whole column, but I wasn't able to. I was able to remove the "live" column by clicking on the manual filter button to deselect "live."

## Results
- An observation I can conclude from Outcomes Based on Launch Date is that there are campaigns are more likely to succeed in when launched May. A second observation is that campaigns are more likely to fail when launched in December.

- An observation I can conclude from the Outcomes based on Goals is that campaigns arew more likely to succeed is the goal is less than $1000.

- A limitation of this dataset is that different factors such as country and backers aren't being observed. There could be a correlation to outcomes based on country and/or backers. We can have a more concrete conclusion of outcomes incorrelations to goal, launch date, donation, etc., if the data was further narrowed. This dataset only looks at two things: launch date and goals.

- A possible table or graph we can create and number of backers and outcomes. New inforamtion and uncovered trends from this table/graph may allow is to gain insights if there is a correation of outcomes based on the number of backers.
