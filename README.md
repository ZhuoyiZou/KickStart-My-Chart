# KickStart-My-Chart
Using the Excel table StarterBook.xlsx, to modify and analyze the data of four thousand past Kickstarter projects and uncover some of the market trends.

## Reading guide for StarterBook.xlsx: 

### In Sheet1:

1. Each cell in the state column with a different color, depending on whether the associated campaign was "successful," "failed," "cancelled," or is currently "live". Green represents "successful", red represents "failed", blue represents "cancelled" and yellow represents "live."
2. Cells in the percent funded column using a three-color scale. The scale starts at percent funded equals to 0 and gets darker shade of red when percent funded gets larger, transitions to green at percent funded equals to 100, and then moves towards to blue at percent funded equals to 200.
3. Category column at Q and sub-category column at R, are splited from the Category and Sub-Category column at N.

### In Sheet2:

1. A pivot table that can be filtered by country, counts how many campaigns were "successful," "failed," "cancelled," or are currently "live" per category.
2. A bar chart is generated based on the pivot table. 

### In Sheet3:

1. A pivot table that can be filtered by country and category, counts how many campaigns were "successful," "failed," "cancelled," or are currently "live" per sub-category.
2. A bar chart is generated based on the pivot table. 

### In Sheet4:

1. A pivot table that can be filtered by category and Years, counts how many campaigns were "successful," "failed," "cancelled," or are currently "live" per month.
2. A line graph is generated based on the pivot table. 

### In Sheet5:

1. Number Successful, Number Failed, and Number Canceled columns are calculated with COUNTIFS() regarding ranges. 
2. A line chart which graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.
