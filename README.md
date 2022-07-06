# An Analysis of Kickstarter Campaigns
## Overview of Project
The purpose of this project was to analyze the theater outcomes based on the month they launched. I also analyzed the percentage of plays that succeeded, failed, and were cancelled during this time period. 
## Analysis and Challenges
### Theater Outcomes Analysis/Challenges
The first analysis I performed was comparing the outcomes of theater performances with their launch date. There was a high rate of success during the Months of May and June. This is preceded by a ramp up in successful theater outcomes from March to April. You can also see a steady decline from May to September for the rate of success. 
In this graph below, we compared the month of the launch and the success rate. You might encounter some challenges if you are trying to compare multiple parent categories and their success rates. You just have to make sure you are choosing the correct filters for your data, and if you would like to select multiple options use the drop down menu for "Parent Category" to select the values you would like to compare. I found that my biggest challenge was making sure the Row labels only reflected the month data. This was quickly fixed by removing unnecessary fields from the Rows area in the pivot table fields. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/108694898/177456997-8da76936-62b5-4c44-bf4f-497b0a6da9fd.png)
### Outcomes Based on Goal Analysis/Challenges
Next, I looked at the outcomes for plays based on their goal. I was able to extrapolate data points using the Countifs() function. This function was more challenging because I had to think about how the data was being manipulated by the formula I was using. I realized that I needed to include a formula for greater than/equal to or less than/equal to and I also needed to include whether the play was successful, failed, or canceled. At first I was getting much higher numbers, until I realized I needed to make sure it was only counting "plays". Once I made this correction the graph sorted itself out. 
![image](https://user-images.githubusercontent.com/108694898/177458612-e9801f51-973f-4368-ac47-94544bfd7cc6.png)
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/108694898/177458642-24d796a4-52eb-431a-8184-c205ee1fd534.png)

## Results
### Theater Outcomes Results
The count of theater outcomes that were successful steadily increased from March through May. After May, we saw a steady decrease in the number of successful outcomes through September. 
### Outcomes Based on Goal Results
There was a high percentage of successful projects that had a monetary goal less than $1000. However, most of the projects (534 projects) fell between the goal of $1000 to $4999 and had a high success rate as well. Therefore, it is safe to assume that there is a higher success rate for projects that have a lower goal amount. 
