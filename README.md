# Kickstarting with Excel

## Overview of Project
### Purpose
This analysis was conducted to help **Louise** with her crowd funding campaign for her new play **Fever** to be more successful.


## Analysis and Challenges
### Overview of the Analysis
<img width="1413" alt="Screen_Shot_Overview" src="https://user-images.githubusercontent.com/110373282/187104889-ab271681-1e74-428e-a3b5-e871f9b5016f.png">

The data set that I used for the analysis has a data for over 4,000 kickstarter campains, that includes;

 - Campaign Goals
 - Based Country
 - Launch Dates
 - Category,

which I used to analyze how the launch dates and funding goals effect the outcomes of the campaign. I have color coded the **outcomes** and **Percentage Funded** column to make it easier to visualize the results. Also, I have separated the Category and Subcategory column to **Q** and **R** so that we could sort the table by either parent or sub category. And since the launched and deadline dates were in timestamps, I converted them on column **S** and **T**  to return month/day/year.

Through this analysis, I have created some charts for visualistion and statistics to increase the authenticity of my result.

### Analysis of Outcomes Based on Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/110373282/187107975-f7f1a39a-dc02-4832-90ba-8b648066c276.png)
This line chart is the relationship between the outcomes and launch month filtered by theater.
>From thel ook of this chart **May** and **June** seems to be the most successful months to launch the campain.
<img width="522" alt="Screen_Shot_Success Fail_Percentage " src="https://user-images.githubusercontent.com/110373282/187109489-62954cc0-2478-4b26-83ea-b82eaaba3673.png">

But as you can see from the above chart, every month except December has an success rate over than 55%. Although May and June has the highest success rate, since there are more competeters compared to the other months starting the campaign betwee **Feb and Apr** might give Louise a chance to stand out. 
>Nevertheless avoiding **Oct and Dec** seems to be safe.

### Analysis of Outcomes Based on Goals

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/110373282/187110850-c5a49819-f6ab-436f-8010-ce177275bb1e.png)
The line chart above is the relationship between the goal-amount ranges and the percentage of successful, failed, or canceled projects.
As you can see from the above chart, if the funding goal is less than $15,000 the Successful Percentage is higher than 50% and gets higher as the goal gets smaller. But at the same time if the funding goal is above $35,000 and below $45,000 the Successful Percentage is 66%.

### Challenges and Difficulties Encountered

During this analysis it was challenging for me to discuss the results for each findings, I made additional columns to add statistics to further my understanding of each graph and charts.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - Louise should avoid starting the campaign on **October** and **December**.
    - **May** and **June** has the most successful percentage to start the campaign.
    
- What can you conclude about the Outcomes based on Goals?
    - Considering to set the goal below **$15,000** and in between **$35,000 and $45,000** has a good successful percantage.
    
- What are some limitations of this dataset?
    - From this data set we are not able to tell the breakdown of the campaign goal, if the breakdown was categorized we might be able to find a trend with the number of backers that find it worth it or not. Also this data set does not include the duration of the successful out come, whether it is going to be a one time show or a continuous business.This also might be able to find a trend in what the backers are looking for.
    
- What are some other possible tables and/or graphs that we could create?
    - I personaly like to know if there were any relationship in between the **Months** and **Goals** in the successful outcomes. That might be something to look into to figure out why there was a spike in the relationship betwwen the Outcomes and Goals when the successful percentage is high in between #35,000 aand $45,000. We could also make a chart that shows the relationship between the staff_pick and outcomes, if there are a trend maybe we could find a further relationship in becoming the staff_pick to enhance the possibility of success in the campign.
    

