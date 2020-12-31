# Module 1 Challenge

## Overview of Project

### The Purpose of the project is to help Louise Understand how Theatre and Play campaigns faired  in relation to their launch dates and their funding goals. This will help Louise better understand how these factors contribute to the success of a respective campaign.

### The Background here is that Louise's play Fever was unsuccessful to achieve its goal and hence she wants to understand what factors contribute to the success of a campaign, Therefore, putting her in a better position to achieve success for her next campaign.

## Analysis and Challenges

#### The task at hand is to help Louise understand the the impact of two factors, **Launch date ** and **Funding goals** to the success of a campaign.
 
#### For the first task of analyzing the effects of **Launch date** on the **outcome**, I used a pivot chart to plot a line diagram that represents the corelation. The line chart [Theatre_ouctome_vs_goals] (https://github.com/arjunkannawar/Kickstarter-Analysis/blob/main/resources/Theater_ouctome_vs_Launch.png) helps to analyze this scenario.

#### For the second task, I have coupled the goal amounts into ranges to see how each range of goal impacts the outcome of a play campaign. The Line chart [Outcome_vs_goals] (https://github.com/arjunkannawar/Kickstarter-Analysis/blob/main/resources/Outcome_vs_goals.png) exhibits the analysis.

## Challenges and Difficulties Encountered

### While using the **Countifs** function, the function does not consider a Filtered table as an input. This function will ignore the filters applied to a table while providing the results. The workaround is to not filter the table and provide the filtering criteria as the input to the function.

## Results

#### What are two conclusions you can draw about the Outcomes based on Launch Date?

#### The Line chart [Theatre_ouctome_vs_launch] (https://github.com/arjunkannawar/Kickstarter-Analysis/blob/main/resources/Theater_ouctome_vs_Launch.png) helps to deduce the following conclusions: 

#### The Month of May, June and July are the most favourable times of the year to run a theatre campaign. However, the limitation of this statement is that other factors may have contributed to the outcome of those campaigns in the months of May, June and July. Having said that, if time does permit, Data does suggest it is favourable to launch a campaign in the months of May to June. 

#### In any given month, the number of successful theatre campaigns are greater than the failed ones and at an average the number of failed theatre campaigns are consistent throughout the year. Hence we can conclude that the launch date is not a significant contributing factor to the success or failure of a campaign.

#### What can you conclude about the Outcomes based on Goals?

#### The line chart [Outcome_vs-goals](https://github.com/arjunkannawar/Kickstarter-Analysis/blob/main/resources/Outcome_vs_goals.png) helps provide a bird's eye view of this analysis to reach the following conclusions:

#### Plays with a goal less than 10000 have more than a 50% chance of success. Plays with a goal greater than 45000 have a zero to ten precent chance of being successful. The data does suggest that the lower and higher bracket of goal amounts is tightly coupled with the  outcome.

#### If the Play campaign goal is in between 10000 to 39999, the outcome does not seem to be influenced by the goal amount. Therefore, we can say that in this goal bracket factors then goal amount seem to be contributing to the outcome.

#### What are some limitations of this dataset? 

#### The limitations of the Analysis is that many factors are contributing to the success of the campaign. Arriving to results based on just one or two factors does have its limitations. 

#### What are some other possible tables and/or graphs that we could create?

#### We can create a table that shows the correlation between multiple variables using **CORREL** function that would show how multiple factors contribute to the outcome. 
