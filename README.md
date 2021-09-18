# Kickstarting with Excel

## Overview of Project

### Purpose
The purpose of this project is to help Louise develop a Kickstarter campaign strategy to fund her play in a local theater. Using data from past Kickstarter campaigns we hope to provide clarity to Louise on how other Kickstarter campaigns have fared based on their launch dates and funding goals. Recently, Louise was able to launch her Kickstarter campaign and come close to the goal funding in a short amount of time. This iteration of the analysis is to help predict the outcome based on dates and goal amounts.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

![Outcomes_Based_On_Launch_Date](http://kickstarter-analysis/assets/images/Theater_Outcomes_vs_Launch.png)

The data analyzed contains Kickstarter campaigns from 2007 through 2017, filtered to only contain a parent category of theater. The theater category is the most relevant category for Louise's play. The data shows the month of May has the highest count of successful Kickstarter campaigns, when compared to any other month. The count of failed and canceled campaigns in May do not show the dramatic increase that successful campaigns do. Based on this information, it is recommended that Louise launches her Kickstarter campaign in the month of May, if at all possible.

### Analysis of Outcomes Based on Goals

![Outcomes_Based_On_Goals](http://kickstarter-analysis/assets/images/Outcomes_vs_Goals.png)

Using Kickstarter campaign data from 2007 through 2017, filtered for the subcategory of plays, an analysis was performed to determine success rates of Kickstarter campaigns based on financial goals. Louise had originally thought the play would need roughly $12,000 generated through Kickstarter. While the anlaysis shows that plays in this financial range do have a higher percentage of success than failed, it is recommended to reduce the budget to roughly $5,000. Plays with a budget of $5,000 or lower have a much higher percent of success, and much lower precent of failure, when getting funded on Kickstarter. The higher funding goal will have a success rate of roughly 54%, and the lower goal will have a success rate of 73%.

### Challenges and Difficulties Encountered

When performing an analysis on a large data set it is important to make sure calculations do not have any errors. In this analysis Microsoft Excel was the tool used for calculations. Making sure formulas were correct, in detail, proved valuable. Paying attention to relative an absolute cell references had a large impact on the results produced, and eventually the conclusions drawn from those results. 
Conclusions drawn from the analysis were highly dependent on the initial data set that was used. Filtering out parent categories other than theater, and subcategories other than plays, had a significant impact on the data set. Measures of centeral tendency, and other caluclations changed wildly when unrelated data was removed from the data set. Taking time to consider what data is relevant, and correctly filtering anything unrelated is easy to gloss over because it is less time consuming than the large calculations, but it is no less important.
## Results

### Two conclusions drawn from Outcomes Based on Launch Date

The data shows the month of May has the highest count of successful Kickstarter campaigns, when compared to any other month. The count of failed and canceled campaigns in May do not show the dramatic increase that successful campaigns do. Based on this information, it is recommended that Louise launches her Kickstarter campaign in the month of May, if at all possible. If for some reason the month of May will not work; April through July seem to have the most successful campaigns when compared to the rest of the year.
Conversly, it is recommended that the month of December be avoided to start a Kickstarter campaign. The month of December has the least amount of successful campaigns and has nearly as many failed Kickstarter campaigns. 

### Conclusion drawn from Outcomes based on Goals

Louise had originally thought the play would need roughly $12,000 generated through Kickstarter. While the anlaysis shows that plays in this financial range do have a higher percentage of success than failed, it is recommended to reduce the budget to roughly $5,000. Plays with a budget of $5,000 or lower have a much higher percent of success, and much lower precent of failure, when getting funded on Kickstarter. The higher funding goal will have a success rate of roughly 54%, and the lower goal will have a success rate of 73%.

### Limitations of the dataset

### Possible tables or graphs to create
If Louise were to need addtional guidence, and wanted more data driven recommendations, I have a couple of ideas:
- A column filled with a formual would need to be added to calculate the length of time each Kickstarter campaign was open. This information could be compared to the the success rate of a campaign, and also to the amount of money raised.  
