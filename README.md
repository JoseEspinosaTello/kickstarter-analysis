# Kickstarting with Excel

## Overview of Project

### Purpose
	
Our client Louise has recently completed the fundraising campaign for her play ‘Fever’, and would like to know how well her fundraising campaign fared compared to other fundraising campaigns for theater events between 2009 and 2017. This project will examine the relation between fundraising campaigns based on launch dates and their fundraising goals. The analysis will allow Louise to determine how successful her campaign was and help Louise changes, allowing her maximize the success of future fundraising campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

To properly analyze the outcomes based on launch data we created a pivot chart. This pivot chart filters the data by category, which is set to theater as Louise’s play falls under the theater category and it is important that we analyze a relevant category. The chart displays the total count of successful, failed, and canceled fundraising campaigns by the months of the total years. To visualize the data, we selected a line graph as it would allow us to easily see and follow the trends of campaigns per month.

![Theater_Outcomes_vs_Launch_Pivot_Chart](https://github.com/JoseEspinosaTello/kickstarter-analysis/blob/main/Recources/Theater_Outcomes_vs_Launch_Pivot_Chart.png?raw=true)

![Theater_Outcomes_vs_Launch](https://github.com/JoseEspinosaTello/kickstarter-analysis/blob/main/Recources/Theater_Outcomes_vs_Launch.png?raw=true)

### Analysis of Outcomes Based on Goals

The outcomes based on goals was analyzed by counting and summing the number of successful, failed, and canceled plays based on the goal range they fall under. We used play as the category as we wanted to compare Louise’s play fever to the other plays in the dataset. After gathering the total counts, we determined the percentage of successful, failed, and canceled plays based on the same goal ranges. Once all the data was gathered, we used a line chart as it will allow us to easily visualize the increase and decrease of successful, failed, and canceled percentage rates per their goal range.

![outcomes_vs_Goals_Chart](https://github.com/JoseEspinosaTello/kickstarter-analysis/blob/main/Recources/outcomes_vs_Goals_Chart.png?raw=true)

![Outcomes_vs_Goals](https://github.com/JoseEspinosaTello/kickstarter-analysis/blob/main/Recources/Outcomes_vs_Goals.png?raw=true)

### Challenges and Difficulties Encountered

A challenge that was encountered during the outcomes by launch date was the fact that we were only working with totals numbers. This made the decision process a little difficult as a high number of totals does not necessarily mean the month was successful. To assist with the analysis, I added columns representing the percentage of successful, failed, and canceled campaigns. With percentages now visible we were able to further analyze each month. For example, August contains a higher total of successful campaigns compared to October; however, October has a higher success percentage, making it a favorable month to launch a campaign.  

![Theater_Outcomes_vs_Launch_Pivot_Percentages](https://github.com/JoseEspinosaTello/kickstarter-analysis/blob/main/Recources/Theater_Outcomes_vs_Launch_Pivot_Percentages.png?raw=true)


## Results

# What are two conclusions you can draw about the Outcomes based on Launch Date?

Analysis of the line cart shows us that the success totals, and failure totals between launch months follow very similar trends. The most successful launch months in total amount are May, June, and July. In comparison May, June, and July also had among the highest total failed campaigns. Overall, all 12 months had a higher total of successful launches compared to failed launches. December stands out as it has the lowest number of successful campaigns and an almost even number of failed campaigns. Based on the analysis one can conclude that the best months to launch a campaign would be between April and August, with May being the top choice. May contains the highest success rate and the months following May begin a downward trend as the number of successful campaigns while still high, steadily drops. Two conclusions can be made about the best and worst months to start a campaign, one can conclude that the worst month to launch a campaign would be the biggest Holiday month of all, December, as it has the lowest success totals and an almost equal total of failures compared to it successful campaigns. Louise’s play ‘Fever’ originally launched its fundraising campaign in June. While June has the second highest success rate Louise’s play did not reach its goal. Another conclusion to be made is that launching her fundraising campaign in May could have returned favorable results. 

# What can you conclude about the Outcomes based on Goals?

Analysis of the Outcomes based on Goals line graph tells us that campaigns with a goal of $19,999 or lower, and campaigns with a goal between $30,000 to $49,999 were the most successful as the campaigns all equaled or surpassed their fail rate. As campaigns began to ask for more money, the lower their success rates dropped. Campaigns with Goal ranges between $20,000 to $34,999, and campaigns with a range of $45,000 or higher had a fail rate equal to 55% or higher. The only example of successful campaigns with a high goal range are those between $30,000 to $49,999 as they had and average success rate of 67%. However, these goal ranges had a combined total of 9 campaigns making the possibility of success higher with fewer successful campaigns. As a result, these ranges could have outliers skewing the percentages. In conclusion the best option for Louise is to set a goal between $1,000 to $4,999 as this range accounts for 51% of the total fundraising campaigns and has a success rate of 73%.

# What are some limitations of this dataset?

Limitations of the dataset:

- Outliers: We don’t take outliers into account which leads to some misleading statics in the outcomes based on goals. Two of the large goal ranges do not follow the trend of the large goal ranges as they have a large success percentage. These two large goal ranges make up a small total of the campaigns, however their success percentages are among the highest leading us to believe they are outliers and their success is influence by unaccounted factors.

- The outcomes based on launch date does not take into account the total months the campaign ran. While the launch date is important, these campaigns did not run a single month. Several campaigns overlapped in months, which means that a successful campaign could be represented in multiple months.

- Percentages can be a misleading static when presented alone. While the percentage of success can be high, this does not tell the entire story of the data, and can lead us to draw the wrong conclusion.

- Unaccounted factors can affect potential pledges. Personal likes and dislikes, generous offers, and holidays are all examples of unaccounted major factors when determining if a pledger would like to commit to the pledge. 

# What are some other possible tables and/or graphs that we could create?
