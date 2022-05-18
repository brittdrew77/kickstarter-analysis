# Kickstarting with Excel
Performing analysis on Kickstarter data to uncover trends
## Overview of Project
     The purpose of this analysis was to visualize the campaign outcomes of plays based on the funding goal and based on the launch date. In other words, we want to figure out if the success of the play campaigns has to do with how much money can be raised by a certain date. 
### Purpose
## Analysis and Challenges
    In order to perform this analysis, I created two new sheets to focus on the outomes of plays. 
### Analysis of Outcomes Based on Launch Date
    I first made a pivot chart to filter the data by subcategory, plays, and launch date, by month. We can now see the outcome of plays by month. From there, I created a line graph based on this filtered data. By using a line graph we can look at trends by month and see that the month with the most successful plays was in May, while the month with the most failed was in October. A possible challenge could be filtering the launch date by month. In order to display the data this way I learned how the group function works and specified months. ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/105089651/168875151-8af5699b-5c23-49b5-a5dc-93211ee3987d.png)
 
### Analysis of Outcomes Based on Goals
    To start, I created a new sheet grouping the number of successful, failed, and canceled plays by a range of goal funding amount. Now, for each goal interval amount we can see the campaign outcomes. Next, to better view the data, I calculated total projects in each goal interval and the percentage of those that were successful and failed. We notice that none of the plays were canceled. I created a line graph to look at the percentages of the outcomes. It is clear that there is symmetry in the graph, since the percentages successful plus the percentages failed must add to 100%. A challenge I encountered with this data was filtering the subcategory by plays. I filtered it in the orignal sheet, but the countifs function was showing all subcategories still. To correct this I added another parameter to the countifs function to filter by plays. (insert code) ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/105089651/168875225-e90eefa0-5f07-402b-8807-46e4e91bcd1e.png)
### Challenges and Difficulties Encountered

## Results
    - What are two conclusions you can draw about the Outcomes based on Launch Date? 
    Based on the outcomes based on launch date data, we can conclude that most successful plays took place in late spring to early summer, more specifically in the months of May and June. Those months were also the months with the most play campaigns in general. It is also apparent that the number of failed plays each month doesn't vary by much. We can observe this in the line graph, since the failed line follows a generally straight pattern. So, we can conclude that if you want a play campaign to be successful, there is a better chance if the launch date is in May or June.
    - What can you conclude about the Outcomes based on Goals?
    According to the outcomes based on goals data, the lower goal intervals have more successful play campaigns and higher goal interval amounts have more failed plays. We can conclude that having a lower goal amount ultimately means a better chance of success and having too high of a goal amount leads to failure. 
    - What are some limitations of this dataset?
    Limitations of this data set are that we chose to focus on only two aspects of a play's outcome: goal funding and launch date. There are more factors to take into consideration that can affect success or failure. Another limitation regarding the outcomes based on launch date is that we chose to only look at months. Maybe years played a factor in outcome. 
    - What are some other possible tables and/or graphs that we could create?
    I would consider the amount of time the campaign lasted. I would look at the difference in days between the date created and the date ended. This could be compared to the goal funding amount. Longer campaigns may have more time to reach their goal amount, therefore would be successful. Also, the country may have an impact in outcomes. Certain countries could have higher success rates in plays than others.  
