# kickstarter_analysis
Performing analysis on Kickstarter data to uncover trends 
## Overview of Project 
Louise is an aspiring play writer wanting to start a crowdfunding campaign for her play "Fever". The purpose of this analysis is to help her determine what factors contribute to crowdfunding campaign success. The first part of this analysis looks at the relationship between the campaign launch date and the outcomes. The second part analyzes the relationship between the fundraising goal and the outcomes.
## Analysis and Challenges 

### Launch Date vs Outcome
The first section of my analysis depicts the relationship between campaign start date and the possible outcomes of failed, canceled, and success. I started by creating a column utilizing the year function based on the Kickstarter creation date column. I then made a pivot table displaying the outcomes as columns and the creation dates as rows, and I filtered the pivot table to show only play campaigns. From this pivot table I made a line pivot chart to visualize the trends throughout the years. 

### Goal vs Outcome
The second section of my analysis examines the relationship between the fundraising goal of the campaign and the outcome. I started by creating groups of dollar amounts for the campaigns. I then used the count ifs function to find the number of campaigns for each outcome in the different goal groups. Next, I used the sum function to find the total number of campaign outcomes in each goal group. Based on this column I calculated the precent for of each outcome for the various campaign goals. Finally, I created a line graph to show the trend of outcome vs goal.

### Challenges
When doing this analysis, one challenge I encountered was using the count ifs function. I had not used this function before, so getting all the criteria correctly was difficult at first. However, I overcame this by carefully looking at example videos.  

## Results
The first conclusion I made about launch date vs outcome analysis is that both the success and failed out comes peak at similar times throughout the year. In the months of Feb, May and June both categories have a peak. The next conclusion is that successful campaigns consistently decline from May to September, however the total number of plays declines as well. From the outcomes based on goal analysis I conclude that campaigns are most likely to success with goals of less than 1000 however, there is high levels of success between 35,000 and 45,000.

### Next Steps
One limitation of this dataset is that the genre of plays is not available. Some analysis should be done to analyze the relationship between length of a campaign and its success rate and the launch date vs outcome should be done again using precents as the values rather than number of plays.
