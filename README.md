# kickstarter-analysis

## Overview of Project
I am helping an up-and-coming playwright, Louise, who wants to start a crowdfunding campaign to help fund her play. She is estimating a budget of over $10,000 and is understandably hesitant about jumping into her first fundraising campaign. She asked my help using Excel to organize, sort, and analyze crowdfunding data to determine whether there are specific factors that make a project's campaign successful.I will use the Using Excel to analyze current site data will help her better understand campaigns from start to finish, and I be able to set up her campaign to mirror other successful ones in the same category.

Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. I visualized campaign outcomes based on their launch dates and their funding goals

I have two analyses for her, one is “Theater Outcomes by Launch Date”, and another one is “Outcomes based on Goals”.

## Analysis and Challenges

### overview of the analysis
For the first analysis, “Theater Outcomes by Launch Date”, I did these steps to create organized pivotable and chart to make it more visual able

As the assignment required, I am using [Module 1 Challenge](https://courses.bootcampspot.com/courses/2638/assignments/45020?module_item_id=835330) as reference. I Create a pivot table from the KickStarter worksheet (the raw data), and place the pivot table in a new sheet.
Label the sheet "Theater Outcomes by Launch Date."
Filter the pivot table based on "Parent Category" and "Years."
Place the appropriate pivot table fields in the columns, rows, and values.
Filter the column labels to show only "successful," "failed," and "canceled."
Filter the "Parent Category" to show only the data for "theater."Sort the campaign outcomes in descending order so "successful" is first.
 
Create a line chart from the pivot table to visualize the relationship between outcomes and launch month.
![Theater Outcomes Based on Launch Date](https://github.com/YawenShao0902/kickstarter-analysis/blob/main/resources/Theater_Outcomes_vs_Launch.png)

For the second analysis, “Theater Outcomes by Launch Date”,I created a new form and grabbed some information out of the KickStarter sheet. 
In the new sheet, create the following columns to hold the data:“Goal”, ”Number Successful”, “Number Failed”, “Number Canceled”, “Total Projects”, ”Total Projects”, ”Percentage Successful”, ”Percentage Failed”, ”Percentage Canceled”.
In the “Goal” column, create the following dollar-amount ranges so projects can be grouped based on their goal amount.
 
Use COUNTIFS() functions to populate the "Number Successful," "Number Failed," and "Number Canceled" columns by filtering on the Kickstarter "outcome" column, on the "goal" amount column using the ranges created in Step 3, and on the "Subcategory" column using "plays" as the criteria.
Use the SUM() function to populate the "Total Projects" column with the number of successful, failed, and canceled projects for each row.
Calculate the percentage of successful, failed, and canceled projects for each row.
 
Create a line chart titled "Outcomes Based on Goal" to visualize the relationship between the goal-amount ranges on the x-axis and the percentage of successful, failed, or canceled projects on the y-axis.
![Outcomes_vs_Goals](https://github.com/YawenShao0902/kickstarter-analysis/blob/main/resources/Outcomes_vs_Goals.png)
 
### Challenges or difficulties 
First difficulty that I faced is my English. I am a Chinese and start to learn English three years ago, so it is hard for me to read all the instructions. I used google transaction function to translate all the unfamiliar words, I also asked my friend’s help. Eventually I understand them all, and made my assignment.
Second challenge was when I am doing all the “countifs” formulas. There are some many formulas in the form. But they are so similar with each other, just need to change some of the things in it. For the first few formulas I did it all by typing. And then I am getting tired of it. So I google how the other people will do. I find that I could use the replace function in the excel to replace one element in multiple formulas in one time. For example, I copy all the formulas in column B to column C. Then I could use the “replace” function to replace all the “successful” to “failed”. Then the data in column is what I need without type them all.

## Results

### Two conclusions are made about the Theater Outcomes by Launch Date 
May is the month that has the most successful outcomes. I would consider to start the   crowdfunding campaign in May.
Oct has the most failed outcomes and the successful outcomes are low at the same time. I am not recommending that to start the crowdfunding campaign in May in Oct. 

### One conclusion is made about the Outcomes based on Goals 
Set the goal less than 1000 has the best chance to be successful in the crowdfunding campaign.

## Summary of the limitations of the dataset and recommendation for additional tables or graphs 
The dataset did not show which Category and Subcategory has the best chance to be successful in which month and in which goal range. And it did not show which specific campaigns she should jump in to achieve the $10,000 budgeted goal. I think we could add Category and Subcategory “Outcomes Bases on Goals.” Do pivotable for new form. To find in each goal range which Category and Subcategory has the best chance to win. And find the TOP few categories in different goal range she could choose. At the same time to make sure all the goal is not below $10,000.  
