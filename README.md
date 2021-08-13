# An Analysis of Kickstarted Campaigns
Performing analysis on kickstarter data to uncover trends
## Purpose
Purpose of this project was to show outcomes for fundraising campaigns based on their launch date and their funding goals.
##Analysis and Challenges: 
Given the kick-starter spreadsheet, we then compared theater outcomes based on launch date and created a chart to help visualize the data. Then compared successful/failed outcomes based on campaign funding goals. Some challenges faced while attempting to better view the date included the filtering and formula writing for the outcome based on goals analysis.
##Analysis of Outcomes Based on Launch Date
To review outcomes based on launch date, I created a pivot table and filtered the outcomes by category and launch date. This allows us to see the total campaigns that were successful, failed, and canceled. I then created a line chart to help further visualize the data. I then wanted to analyze the data further and wanted to see the percentages of successful vs failed regarding launch dates. 

When reviewing the data and more specifically the chart, the better outcomes for the successful campaigns seem to be in the spring and then trend downward during the summer. The Failed campaigns did not have any significant increases or decreases when looking at the months launched. The number of total campaigns was 1369. The total successful was 839, failed 493, and canceled 37. The highest number of successful campaigns was in May, that number being 111 successful (67%) followed by Jun at 100 (65%). The highest number of failed campaigns was also in May at 52 (31%). But it also should be noted May and June also had the highest total number of campaigns launched at 166 and 153. Given the data, the average success rate was around 60% and failed 36% overall through the year. The Month with the highest percentage failed is December at a 47% failure rate.

![image](https://user-images.githubusercontent.com/88061345/129421156-9c7439d9-8547-47bd-8ec8-a5177d87727f.png)

![image](https://user-images.githubusercontent.com/88061345/129421164-5a7e692b-8586-41ae-b419-aad5d5297883.png)
![image](https://user-images.githubusercontent.com/88061345/129421254-f79e85c4-51b3-42c8-9bdf-424c9472831d.png)
## Analysis of Outcomes Based on Goals
To analyze the outcomes based on goals, a table was created and then filtered the data from the kick-starter spreadsheet to only show Theater and Plays. I used a COUNTIF formula with multiple criteria to show number of successful, failed and canceled campaigns based on goal range. I then calculated the percentages of successful, failed, and canceled to the total number of projects in each goal range.
The two highest percentage of successful campaigns at 74.9% and 72.66%, also had the lowest goals of <$1,000 and $1,000-$4,999. The Two highest failed campaigns, at 87.5% and 100% had the highest goals at $45,000-$49,999 and >$50,000. The data shows that you have a higher probability to meet your goal if the goal is lower. The higher the goal, the less likely you are to be successful.

![image](https://user-images.githubusercontent.com/88061345/129421287-1a1c8866-b111-427f-9790-8b0b85d1dd14.png)
![image](https://user-images.githubusercontent.com/88061345/129421295-551caf7b-da57-49db-963a-bda19d83be62.png)
## Challenges and Difficulties Encountered 
The main challenge I encountered was pulling the data from the kick-starter to the table for outcomes based on goals. I had filtered the kick-starter worksheet and thought that once that was completed, the data that populated with my COUNTIFS formula would only pull the filtered Category and subset. I did not consider it would pull all the data and I needed to specify the formula to only pull data from the parent and subcategory Theater and Plays.


## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date? 
There are more plays/fundraising campaigns during the spring and that is also the highest number of successful outcomes. May specifically had the highest number of launched campaigns and also the highest number/percentage of successful campaigns.  If launching a campaign for theater/plays, I would suggest doing so in May. And one might want to avoid the month of December for launching a theater/play campaign as that month had the highest failed percentage.

- What can you conclude about the Outcomes based on Goals? 
There is a better chance of being successful if there is a lower goal. Given the data and charts, a campaign with a higher goal is more likely to fail.

- What are some limitations of this dataset?
The limitations in this data set are insufficient data in the projects with higher initial goals. Also, I am unsure if the dataset may include incomplete data, we may be missing data that might not have been recorded.

- What are some other possible tables and/or graphs that we could create?
	Another thing to review possibly is average donation and or how many backers. And if that has an effect if the goal was met, failed, or surpassed. 




