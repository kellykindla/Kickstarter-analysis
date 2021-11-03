# Kickstarting with Excel- Module 1 Challenge 1

## Overview of Project 

#### For this project, we were presented data regarding kickstarter campaigns for fine arts productions in efforts to help our client, Louise, discover the trends for a successful campaign. We were presented with data for each productions goal versus what was actually pledged, along with the number of backers and demographics for the production (where it took place, when it took place, what type of production, etc.). From this, we were able to visualize if each campaign was successful and demonstrate trends for how successful it was based on percentages, average donations, or by when it took place.


## Purpose

### The purpose of this project was to tell a story based on data—in this case, visualize campaign outcomes based on their goals and launch date. 


## Analysis 

### Analysis of Outcomes Based on Launch Date

#### From the Kickstarter Data, we were challenged to compute the theater campaign outcomes based on their launch date and visualize potential trends. In order to begin this analysis, we had to create a pivot table to summarize the data. This pivot table, shown in the image below, only shows the campaign data we are curious about—theater— and can be further broken down into the year a campaign was launched if desired. The pivot table gives us a quantitive visualization of the number of successful, failed, and canceled theater productions by the month they were launched. This data is also summarized in the line chart shown below. From this visualization, we can gather that there is a peak in successful campaigns in the month of May with 111 successes; however, this should be taken lightly as there is also a peak in failures with 52 failed campaigns in May resulting in a 67% occurrence of successful campaigns in May. We can also see a decline in successful campaigns from October to December with a peak occurrence of failures in October where only 57% of campaigns are successful. 

#### ** Pivot Table: **

<img width="325" alt="LaunchDate_PivotTable" src="https://user-images.githubusercontent.com/92558842/138497040-9e92a611-3773-4a8f-a233-58dc68491867.png">

#### ** Line Chart: **

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92558842/138497115-46f96ac9-e3aa-41ff-a633-053d4af8b366.png)

### Analysis of Outcomes Based on Goals

#### We aimed to discover the percentage of successful, failed, and canceled plays based on their campaign goals. In order to accomplish this, we had to filter our Kickstarter Data using the excel “CountIfs” function to quantify the number of successful, failed, and canceled play productions in relation to the associated goal ranges. This data is shown in the table below where one find that the most successful campaigns had the lowest goals of less than $1000. We also find that 100% of the campaigns with a goal between $45000 and $49999 were failures; however, there was only one campaign in this category.  This data is further visualized in the line chart below, where we can see the general trends of the percentage of successes or failures versus the campaigns goal amount. From the graph, we can see a general decrease in successes, increase in failures from goals starting at $1000 going to $29999. There does happen to be a spike in successes at 66.67% successful in campaigns whose goals range from $35000 and go to $44999. 

#### ** Table: **  

<img width="723" alt="Outcomes_Basedon_Goals" src="https://user-images.githubusercontent.com/92558842/138497179-fb22be7d-be20-49b6-a0d3-f36ee1e674dd.png">

#### ** Line Chart: **

![Outcomes_vs_Goal](https://user-images.githubusercontent.com/92558842/138497209-593aa6e1-1ca1-4a14-bf50-7ae044d54453.png)


## Challenges and Difficulties Encountered

#### One of the most memorable challenges I faced in this assignment was getting practice with the “CountIfs” function in excel. It was my first time using this function, but once I further researched its use and practiced it on the first column of successes, it became a breeze and I can see it being useful in future projects to expedite filtering data. Another potential challenge with this project could be understanding pivot tables and their organization. Pivot Tables are incredibly useful in quickly summarizing data; however, if the columns and rows are not what you desire, the data can become confusing. To overcome this challenge, one could simply practice changing the contents of the pivot table to see how it changes in regards to what is in the columns, rows, filters, and values.


## Results 

#### From the data, we can see that most of the theater productions occur between May and June where there is a peak amount of successful campaigns in May; however since this is the busiest month for campaigns, we also see a peak in failures. There also appears to be a steady decline in successes from June to September; however, the amount of failures does not tend to increase in these months. Regarding outcomes based on goals, we can generally see a negative correlation between percentage of successful campaigns and an increase in goal amounts, where as the goal amount increases, the probability for success decreases. Looking at this data, we also see that at $15000, the number of failed campaigns becomes greater than the number of successes. Taking these results into consideration, I would suggest to Louise to host a campaign from April to June with a goal amount less than $14999. I would also highly suggest for Louise to avoid campaigns with a goal greater than $45000 during the holiday months (October- December) in order to avoid the possibility of failure. 


## Limitations

#### However, like any data set, there are limitations. For instance, we do not know if there were external factors effecting the outcome of campaigns- like holidays or a pandemic. We also do not know what type of advertisement went into the campaigns. It could be that all of the successful campaigns were only successful due to advertisement rather than when they took place. The sample size of the data could also be skewed since the theater category has the largest sample size compared to the others and it does not include all possible productions. 

## Other Possibiliteis

#### Based on the Kickstarter Data we have, I am curious to see the effect that the number of backers has on the outcome of a campaign- is it a positive correlation or does it not have one at all? A visualization of outcomes based on country could also be helpful to the client to see where the most successful campaigns take place and to see if a certain country tends to have the higher campaign goals- if so, why? Lastly, it would be interesting to see if the duration of a campaign has any correlation to its success. 
