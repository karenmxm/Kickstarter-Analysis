# Kickstarter-Analysis
Performing analysis on Kickstarter data to uncover trends.
The purpose of the project is to help Louise find out factors that make her fundraising campaign for her play “Fever” successful by Crowdfunding. The goal of her campaign is $10,000. We use Kickstarter dataset to mirror other successful ones in her category. Kickstarter dataset contains 4114 campaigns’ information (14 variables) including campaign goals, pledged amount, outcomes, which country the campaign took place, launch date, number of backers and categories etc.. The following sections show findings from Kickstarter dataset.
1. Findings from Kickstarter dataset
* Parent category outcomes show that “Theater” has most successful outcomes and “Journalism” has least successful outcomes.
* Subcategory outcomes show that the “plays” category is the most successful Kickstarter campaigns for plays in Great Britain.
* Outcomes based on launch time show that the most successful Kickstarter theater campaigns were started in May. December has the lowest successful outcomes which means it is not a good time to launch a campaign.
* The average donation and number of backers of the five plays at the Edinburgh Festival Fringe Louise enjoyed: Be Prepared, £51.79, 39; Checkpoint 22, £36.07, 56; Cutting Off Kate Bush, £33.03, 78; Jestia and Raedon, £44.92, 26. There is no information about The Hitchhiker’s Guide to the Family. 
* Based on these statistics, we can determine the following: 
The mean of each goal’s distribution is around the 3rd quartile and the standard deviation is larger than the mean. Moreover, for both goal successful and failed subsets, because median minus lower quartile is less than upper quartile minus median. So in each subset, the data follows similar distributions and right skewed, meaning large values are driving these distributions. But the failed goal subset is skewed more, meaning failed campaigns have a larger percentage of high goals.
###
2. Challenge:
More findings and suggestions
*Conclusions: Based on Kickstarter dataset, we found that Amount of goal, timing of fundraising, the incentive for pledge amount (average donation amount) are the important factors can affect successful rate of a crowdfunding.
 *Amount of goal
  *Findings: Goals between $5,000-$9,999, percentage of successful is 55.03%, Between $10,000 - $14,999, percentage of successful is 54.17%. Successful percentages are very close in these two scales. But between $ 1,000 - $ 4,000, percentage of successful campaigns is dramatically higher (72.66%). This means when goal decreases by $1,000, successful percentage increases by 3.52%. 
  *Recommendations: Set $9,999 as her goal or slightly less.
 *Timing of fund raising
  *Findings: Outcomes based on launch date show that May has the most number of successful campaigns. The trend dramatically decreases each month after May. December is the worst time for crowdfunding.
  *Recommendations: Start from May and raise during summer (May- August).
 *“Kickstarter, like other crowdfunding platforms, allows project creators to add incentives for different pledge amounts”. Louise also need to set up her incentives by how much money people need pledge by investigating campaigns historically in her category. She shows strong interests in five plays in Edinburg. So we have some findings and suggestions based on her interests.
  *Findings: We have data for four of Louise interested shows. The goal values of them are between £1,000- £2,000, and all of them are successful campaigns. The average donations are between £33.03 - £51.79. When the average donation is above £45, the number of backers is dramatically lower. 
  *Recommendations: Set the incentive for pledge amount below £45.
*Limitations and suggestions for additional tables and graphs.
 *Limitations
Based on Louise’s fundraising goal and her category, there is a limitation for a better analysis. She showed strong interest in Edinburg plays which implies this may be the place she wants to perform. Location is very important for the success of the fundraising for a performance since the audience are more likely to fund her play. But Kickstarter dataset contains very few Edinburg plays campaigns (55). And only three of them have goal close to Louise’s $10,000. The incentive for pledge amount below £45 we made is based on plays she interested with goals below £2,000. That is far from her goal, so it may not help her succeed. We need more information on Edinburg plays.
 *Suggestions
We noticed campaigns missed their goal amount by different margins. We can look into the deficit and statistics of the deficit to investigate the reasons cause the difference of the margins. This can help to improve Louise’s decision on goal, timing and average donation request, etc..  
