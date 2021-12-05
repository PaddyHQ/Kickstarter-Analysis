# Kickstarting with Excel
## Overview of Project
### Explain Purpose
The goal of this analysis was to pull data about several thousand Kickstarter campaigns, clean and organize it, and then look for patterns. Our client, Louise is looking for reccomendations for her own Kickstarter based on our findings. Our data set includes Kickstarter campaigns from 21 different countries and includes information such as: size of goal, amount raised, how many people backed the campaign, and when the campaign started and finished. We filtered the data to show campaigns similar to Louise's, and looked for patterns that would suggest the best to start a new campaign and what sort of goal might be achievable for a campaign like Louise's.

## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
![Outcomes_Based_on_Launch_Date](./Resources/Theater_Outcomes_vs_Launch.pngresources\Theater_Outcomes_vs_Launch.png)

Across all years, our data set shows that campaigns for plays usually succeed most often in the spring time. Most play campaigns begin and succeed in the months of May and June. However, for most months, Kickstarters for plays are about 1.7 to 1.75 times as likely to succeed rather than fail across all years. Historically, August, October, and December are the worst months to start a Kickstarter for a theater project. December is by far the worst, with approximately one campaign failing for every successful one. August, October, and December coincide with the beginning of the school year and multiple major holidays. Generally, people have less disposable income for things like plays at these times of year and that might be one factor driving this trend.

### Analysis of Outcomes Based on Goals
![Outcomes_Based_on_Goals](./Resources/Outcomes_vs_Goals.pngresources\Outcomes_vs_Goals.png)

Most Kickstarter campaigns for plays had goals of less than $10,000. Campaigns that had goals of less than $5000 have a historical 75% success rate (roughly 2:1 odds of succeeding). The majority of Kickstarter campains for plays asked for between $1000-$5000. Historically, as goals approach $10,000 the percentage of successful campaigns goes down from approximately 70/30 (roughly twice as likely to succeed as fail) to a coin flip (55/45, or roughly equally likely to succeed as fail). Past $15,000 Kickstarter campaigns for theaters are more likely to fail than succeed. There are very few data points above $25,000. Therefore, the results above that threshold cannot be reliably interpreted.

### Challenges and Difficulties Encountered
On first look, the graph of goals versus outcomes looks to show no distinguishable trends. However, there were very few campaigns above $25,000. Each category above the $25,000 mark represents less than 20 campaigns. Only 42 total campaigns comprise the entire data set above $25,000. For example, campaigns between 35,000 and 45,000 seem to be a sweet spot (67% success rate), but this section only has 9 results. Given the small data set, this result is very likely to be a fluke. With that in mind, it is prudent to focus on the data below $25,000, and the data do show a strong pattern below the $25,000 threshold.

The month with the lowest success rate in Kickstarter campaigns (December) also happens to be the month where the fewest Kickstarter campaigns have been launched. This calls into question whether or not December is actually a bad month to launch a campaign or if the trend shown in other months would be preserved through December if more campaigns were launched then. Further, in our data analysis, the start date is included and analyzed, but not the length of campaign. Campaigns that last a full year might be more likely to succeed than those that only ran for a month for instance. Nevertheless, start date does seem to be strongly correlated with outcome in this data set.

## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
    - Based on our historical data, I would recommend Louise start her Kickstarter campaign in Spring. Around May and June is both when most campaigns are successful and when most start. 
    - Second, I would avoid starting her campaign (therefore asking for the bulk of your money) around "back to school" and major holidays like Halloween, and Christmas. Generally, people have less financial liquidity post-Christmas and into the first quarter year. Our data are consistent with that trend.

- What can you conclude about the Outcomes based on Goals?
    - Louise should limit her goal to around or below $5000 for best results. Campaigns under 5000 are generally safe (70% success rate) and there are many campaigns in this category, so this is a robust result.

- What are some limitations of this dataset?
    - Our data is limited in two key ways, both having to do with sample size. First, there are substantially less Kickstarter campaigns started in December than other months that have been historically more successful. This makes it less clear whether the success to failure ratio of December is the result of a smaller data set or if it truly is a worse month to start a Kickstarter campaign. 
    - Second, there are very few campaigns with goals above $10,000 and even less above $25,000. If Louise was looking to start a large campaign, we cannot say anything definitive about where to set the goal, only that our more robust data shows that the higher the goal, the less likely it is that the campaign succeeds.

- What are some other possible tables and/or graphs that we could create?
    - A box and whisker plot for the data concerning plays in United States akin to the one we were asked to generate for musicals in Great Britain would be great for showing how our goal and pledge data are distributed. 
    - I would like to filter the outcomes based on start date graph to look at only campaigns under $10,000 to see how that affects the result. 
    - I'd also like to know when the campaigns above $25,000 occurred, so filtering the pivot chart to show those dates would be interesting.