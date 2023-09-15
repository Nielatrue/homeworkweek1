# homeworkweek1
Use conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.
  Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
Use conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.
    Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.
    Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.

Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.

Create a new sheet with a pivot table that analyzes your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.
  Create a stacked-column pivot chart that can be filtered by country based on the table that you created.

Create a new sheet with a pivot table that analyzes your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.
Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that you created.
The dates in the deadline and launched_at columns use Unix timestamps
  Create a new column named Date Created Conversion
      using this formula =(((A1/60)/60)/24)+DATE(1970,1,1), press Enter key, then drag the auto fill handle to a range you need
      Then right click the cells used the formula, and select Format Cells from the context menu, then in the popping Format Cells dialog, under Number tab, click Date in the Category list, then select the date type in the right section convert the data contained in launched_at into Excel's date format.
  Create a new column named Date Ended Conversion
      using this formula   =(((A1/60)/60)/24)+DATE(1970,1,1), press Enter key, then drag the auto fill handle to a range you need
      Then right click the cells used the formula, and select Format Cells from the context menu, then in the popping Format Cells dialog, under Number tab, click Date in the Category list, then select the date type in the right section convert the data contained in deadline into Excel's date format.

Create a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.
  create a pivot-chart line graph that visualizes this new table
  
