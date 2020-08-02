# Kickstarting with Excel

## Overview of Project

### Purpose 
The purpose of this analysis is to provide client Louise with an overview and insight of other campaigns and their outcome based on their launch date and funding goals so that she may compare to her own campaign.
## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
![image](https://github.com/myljacobo/kickstarter-analysis/blob/master/resources/Theater_Outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
![image](https://github.com/myljacobo/kickstarter-analysis/blob/master/resources/Outcomes%20vs%20Goals.png)
### Challenges and Difficulties Encountered
When working on Deliverable 1, I made the mistake of dragging down the field name launched_at to the Rows category and the numbers presented were not useful at all in making the table functional. I began to assume that I would have to convert the Unix time to a short date, but then realized we had previously done so and then inserted the Date Created Converstion field name to the Rows category. After this, I was able to group the Row Labels by month only as instructed. 

For Deliverable 2, I did encounter a few challenges as well. When I entered the first COUNTIFS function for the Number Successful column, it seemed to be a correct formula. I then copied the formula for the remaining rows below and a message with a yield sign appeared that notified of an Inconsisent Formula. I had the impression that my original formula was incorrect so I went over the formula several times. It seemed to be correct and I then decided to attend office hours to address the issue. I was informed that sometimes Excel will notify of inconsistencies as such but to continue working through. I did find that if I were to continue on the row below and change the criteria, the formula is still correct and just needed to be adjusted for each cell and the yield sign no longer appeared. After my first column was complete, I then attempted the next column for Number Failed. I was careful to follow what I had learned from the previous column and after entering each formula for all cells, I noticed the amount stayed at zero for each. I knew this was incorrect as I referred back to the Kickstarter sheet, applied filters and found there to be a number of failed campaigns with several different goal amounts. I then went back to each cell and compared it even closer to the previous column. Lo and behold, I noticed I entered the range as play instead of plays so after this was changed in each cell, different amounts then appeared. My line chart did not match the chart listed in the challenge although I believe the data to be correct as I referenced the filtered criteria in the original Kickstarter sheet. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - One conclusion I can draw about the Outcomes based on Launch Date is that regardless of the number of campaigns launched for the theater subcategory, the number of successful launches always outnumbers the number of failed launches. I can also suggest that the number appears closer towards the end of the year in December and would advise to refrain from launching at this time. I can further conclude that between May and June, the successful campaigns are highest than at any other time of the year. This time would be ideal if launching a campaign for theater.
- What can you conclude about the Outcomes based on Goals?
  - From the Outcomes based on Goals, I can conclude that the majority of campaigns have a goal of 1000 to 14999 and the most successful campaigns had a goal of 5000 to 9999. Goals that were less than 1000 also failed at a rate of 100%.
- What are some limitations of this dataset?
  - This dataset seems to have limitations such as not providing the timeframe of each campaign. A better insight may be delivered with how long the campaign was live as this can also attribute the success. The number of backers may also provide a more thorough conclusion to the success or failure of a campaign.
- What are some other possible tables and/or graphs that we could create?
  - Other possible tables and/or graphs that could be created to assist Louise would be ones that display more in depth information about successful campaigns. Comparing successful campaigns from each country may also help if they were shown with the time frame that was used along with the number of backers and filtered to a specific category she would be interested in launching.
