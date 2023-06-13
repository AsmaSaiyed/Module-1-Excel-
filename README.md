# excel
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.

To receive funding, the project must meet or exceed an initial goal, so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. 

The following file organizes and analyzes a database of 1,000 sample projects to uncover any hidden trends.

The following tasks were performed on the file:

1. Use conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.

2. Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
Use conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.

3. Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.

4. Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.

5. Create a new sheet with a pivot table that analyzes your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

6. Create a stacked-column pivot chart that can be filtered by country based on the table that you created.

7. Create a new sheet with a pivot table that analyzes your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

8. Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that you created.

9. The dates in the deadline and launched_at columns use Unix timestamps. Create a new column named Date Created Conversion to convert the data contained in launched_at into Excel's date format and a new column named Date Ended Conversion to convert the data contained in deadline into Excel's date format.
10. Create a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.Now, create a pivot-chart line graph that visualizes this new table.
11. Create a new sheet with 8 columns:
Goal
Number Successful
Number Failed
Number Canceled
Total Projects
Percentage Successful
Percentage Failed
Percentage Canceled

12. Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the Number Successful, Number Failed, and Number Canceled columns with these data points.

13. Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.

14. Create a line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.

15. For gaining an in-depth understanding of campaign backers, evaluate the number of backers of successful and unsuccessful campaigns by creating your own summary statistics table.Create a new worksheet in your workbook, and create one column for the number of backers of successful campaigns and one column for unsuccessful campaigns.

16. Use Excel to evaluate the following values for successful campaigns, and then do the same for unsuccessful campaigns:
The mean number of backers
The median number of backers
The minimum number of backers
The maximum number of backers
The variance of the number of backers
The standard deviation of the number of backers
Use your data to determine whether the mean or the media


The word file contains the analysis.

