# stock-analysis 
## Purpose
Louise is a playwriter who has analyzed the crowdfunding method to raise funds for her future projects. We have a dataset of all of the crowdfunding projects from 2009 to 2017 extracted from the internet. Based on this information, I am going to analyze trends specifically in theater crowdfunding efforts. I will concentrate on the date launched, and the amount asked to help Louise have the best chance when launching a crowdfunding effort in the future. 

### Overview of the Project 
Crowdfunding has become a popular way to secure funds for projects; theater has benefited the most out of this, as it is the category that most projects have successfully funded their projects. This analysis will explore the outcomes of theater production success by supporting their project via crowdfunding. I will examine any trend on success or failure crowdfunding efforts had by date launched and by amount targeted.  The analysis will provide a clear view of long-term trends regarding crowdfunding theater productions. Analyzing will allow the reader to make a more informed decision on timing and crowdfunding goals to diminish the chance of failure. Based on the information compiled, I’ve come up with several conclusions that might be worthwhile projects and people engaging in this fundraising model for theater projects. 
## Analysis and Challenges

The analysis was performed based on a data set that compiled all of the crowdfunding projects from 2009 to 2017. There are 4114 projects from many parts of the world. After an initial phase of preparing the data, I extracted the projects that had successfully reached their goal and the ones that didn’t. I calculated the Mean, Median, and Standard Deviation of the intent of the project and the pledge. Based on these calculations, I have made the following conclusions:

<img width="200" alt="Screen Shot 2021-05-01 at 10 16 24 AM" src="https://user-images.githubusercontent.com/81016335/116785898-fe51e500-aa69-11eb-89f8-6831b50e9ea2.png">

1.	the data distribution is skewed to the right. 
2.	The interquartile range of goals of the successful projects is less than the IQR of the projects that failed.
3.	The Pledge distribution is also skewed to the right.
4.	The IQR of the amount pledge is greater on the successful projects than the failed projects.

Based on this data and examining the data in a Whisker plot, we can see many outliers on successful and failed projects. The high number of outliers results in the entire data set being skewed to the right. 
![Whisker](https://user-images.githubusercontent.com/81016335/116785956-4a9d2500-aa6a-11eb-8ece-cd541c00c07b.png)

The primary analysis was focused on two crucial factors to consider when launching a campaign:

1. Identifying any trends regarding the date the campaign launched and success 
2. Identifying any trends regarding the amount asked and the success of the campaign 

For point 1 I created a pivot table from the Sheet named “Kickstarter Data.” I made a table that gave me the outcomes of all campaigns based on the month they launched. I created a line graph that provided me with a visual aid to identify trends in the data. 

For point 2 I created a table that counted the number of projects by the outcome and separated them by the amount of money their goal was. The range started from >= 1000 and incremented by 4999,  ending at =<50000; in the table. Percentages for all three categories were calculated and inputted on the table.  

### Analysis of Outcome Based on Launched Date 
My first conclusion is examining the data and the graph I can conclude that there is a clear month that is clearly the best month to launch a theater campaign, May. According to the graph campaigns that start May is over three times more likely than the worst month to start a campaign, December. 

My second conclusion examining the general trend of the graph is that theater productions is that there is no month than there are more failures than success on the theater category. The average success rate is of 61% having the month of May as the month with the highest success rate with 67% of all campaigns launched that month being succesfull. The average fail rate is of 37% with December being the highest fail rate with 47%
![Theater_Outcomes_vs_Lauch](https://user-images.githubusercontent.com/81016335/116786485-e29c0e00-aa6c-11eb-8cae-7a54c30f536d.png)

### Analysis Based on Goal
here is a 76% chance of successfully funding a project if the goal funding is >=1000. The possibility of successfully funding a project dwindles as the goal increases reaching a 50% possibility when the goal value is between 15000 and 19999. The success rate is lower than 50% except between 35000 and 44999, which goes up to 67%. I would argue that after examining this data and considering the high number of outliers, this might be the result of some six outliers on the data set. Based on this information, I would argue a strong correlation between the amount asked and success. The smaller the amount, the greater the probability of successfully reaching the goal. 

It is crucial to consider the number of projects on each range on the table and the trends that the graph could provide. 92% of all projects concentrate on lower ranges between the ranges of >=1000 and 14999. Meaning is much more relevant to the data in these five ranges than the data that outliers might distort on graphs. Hence, I would argue with confidence that if I eliminate the outliers, the successful line will have a much more consistent negative slope, and the failed line would behave proportionally inverse. 
T![Outcomes_vs_Goals](https://user-images.githubusercontent.com/81016335/116786877-095b4400-aa6f-11eb-9ccd-47f5c9ae2fa6.png)

### Challenges and Difficulties Encountered
I did not have any real challenges working with this data or any of the equations or graphs I use. I could see someone struggling to create a whisker plot and changing the scale to portray it accurately. I could also see someone having difficulty working with the countifs formula. 

### Dataset and Analysis Limitations
The dataset does present some limitations dataset starting from the fact that its most recent data is from several years ago. This dataset only focuses on the initial funding of the project. It would not allow us to examine the success of the projects and if crowdfunding presents any benefit or disadvantage on the project's longevity. The dataset is also limited because there is a specification on the city the crowdfunding project was done; it only gives us the country. With the US having over 350 million people and over ten urban centers with over 1 million people living, this information is critical for any analysis to understand the local market. There is also minimal information about the people that fund this project, how the project was primarily shared and how long the campaign lasted, all crucial factors to consider before launching a crowdfunding campaign.

## Further Analysis Possibilites
Many additional graphs could help us understand better the crowdfunding model and how it has behaved. I do believe that with the dataset we have gotten, we could examine more the subcategory section on theater to understand the most and least popular genres in the US. We could also explore and compare the projects throughout the years. Given the dataset possibility for further analysis on other markets such as Great Britain, it should also be interesting to examine the crowdfunding model in multiple countries to understand their success and the type of project proposition most likely to succeed.
