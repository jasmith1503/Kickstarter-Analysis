# Kickstarting with Excel

## Overview of Project
Using the Kickstarter dataset, visualize the campaign outcomes based on their launch dates and their funding goals. 

### Purpose and Background
A friend Louise’s play * *Fever* * came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals.

## Analysis and Challenges
I preformed my analysis using Excel and the dataset "Kickstarter". This information has a wide range of projects started along with the corresponding results from each project. There are multiple different categories beyond just theater plays and musicals. The data was analyzed using a variety of Excel functions and charts to understand the data provided.  

### Analysis of Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch](Resources/Theater_Outcomes_vs_Launch.png)
The conclusion for the worksheet "Theater Outcomes by Launch Date" implies there is a large number of new plays / musicals where the kickstarter is started in April, May and June of any given year. This could coincide with summer semesters or end of school year with graduations and in a increase of available staff to produce the play. 

### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](/Resources/Outcomes_vs_Goals.png)
Most smaller projects ($0.00 to $14,999) have a declining chance of success vs projects which have a smaller to larger goal have an increasing chance of failure. After goals of $15,000 fail more than the projects with the same amount. There were two notable groups ($35,000 to $39,999 & 40,000 to $44,999) where 66% of the projects were funded. 

### Challenges and Difficulties Encountered
A few limitations of the dataset are this is a snapshot of Kickstarter campaigns between 05/2009 and 03/2017. This data is not derived from an API, but a download of the data provided by Kickstar.com. For newer data this would need to be added to this current file or an API solution using Python, PHP, or another method would need to be implemented. 

The Excel file only looks at one datatype (theater) for the worksheet “Theater Outcomes by Launch Date” and additionally worksheet “Outcomes Based on Goals” is only looking at data in the sub-category of “plays”. This could be expanded to bring in Parent Category and Sub-Category as drop-down lists to allow the dataset to be more flexible for viewing. 
