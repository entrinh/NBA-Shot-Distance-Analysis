# NBA-Shot-Distance-Analysis
## COGS 108 Final Project
### Overview
Throughout this project, we tested our data science question by splitting it up into three smaller questions. In our first analysis, we compared the average shot distance for the winning team of each season over the past two decades. In our second analysis, we followed the trend of shot distances for 2-pointers, mid-range, and 3-pointer shots over time. In our last analysis, we looked at the relationships between both the percentages and the raw number of three-pointers when compared to the amount of three-pointers attempted, made, and all shots attempted.
### Group Members
* Eric Yang: Background Research, Exploratory, Conclusions
* David Gallardo: Analysis: Part I, Data Wrangling, Conclusions
* Alvin Wong: Question & Hypothesis, Analysis - Part II, Conclusions
* Vincent Tran: Ethical Considerations, Analysis - Part III, Conclusions
* Eric Trinh: Dataset, Data Wrangling, Descriptive, Conclusions
### Research Question
How has the average NBA shot distance changed over the last two decades, specifically the percentage of three-point shots attempted and made, and how has this affected average shot distance?
### Background Research
One of the most popular sports in the United States is basketball. Within the game of basketball, the three-point shot has increased in popularity and has greatly impacted the game ever since the introduction of the three-point line. Many basketball players today have the three-point shot as part of their skillset and it is an important skill to have for guards. Even centers today, who traditionally are not known for shooting, are beginning to pick up the three-point shot. Additionally, college athletes today are shooting more three-point shots than ever before (1). However, the three-point line is a relatively new creation as it was added to basketball in 1979 while basketball was first invented in 1891 and the National Basketball Association (NBA) created in 1946 (2).

Looking at previous projects, students have looked into the impact of the three-point shot and also the practicality or effectiveness of the three-point shot. But, none have explored and analyzed the change in shot distance because of the three-point line. We believe that the amount of shots taken at longer distances have increased ever since the introduction of the three-point line, especially as teams place more and more weight on three-point shots in their game plans.

References:
1) https://bleacherreport.com/articles/2762158-the-3-point-revolution-has-taken-over-college-basketball-too
2) https://www.usab.com/youth/news/2011/06/the-history-of-the-3-pointer.aspx
### Hypothesis
The average NBA shot distance will have increased due to the addition of the three-point line.

With the introduction of the three-point line, as players become better shooters and more familiar with the three-point line, players will take their shots from a farther distance to have a chance at making three-point shots, as statistically, a three-point shot contributes more to a game victory than a two-point shot. Additionally, the average NBA shot distance is directly proportional to the distance of the three-point line from the hoop, so as more players begin to take more and more three-point shots, and the three-point line gets pushed further out, the average shot distance of the NBA will consequently increase.
### Data Set
https://www.basketball-reference.com/ will be our primary resource to gather data from. It has nearly everything one would want regarding basketball statistics from statistics for current and past players, teams, and coaches, meaning we are able to collect concise empirical data for absolutely any and all specific data points we would want to extrapolate from just this one resource. This website also allows us to export data through CSV files, which we can easily import into Python. This also means that data wrangling on the datasets coming from this website should be very simple and straightforward.
* Data Set Name: Basketball Reference
* Link to the Data Set: https://www.basketball-reference.com/
* Number of Observations: All basketball teams participating in the NBA from 2000 to 2018
### Procedure, Result, Conclusion
All of this is in NBA_Shot_Distance_Analysis.ipynb
