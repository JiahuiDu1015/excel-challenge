# Using the Excel workbook, modify and analyse the sample-project data and try to uncover market trends.

  Use conditional formatting to fill each cell in the outcome column with a different colour, depending on whether the associated campaign was successful, failed, cancelled, or is 
  currently live.
    
      Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
    
  Use conditional formatting to fill each cell in the Percent Funded column according to a three-colour scale. 
      
      Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.
    
      Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate 
      columns.
      
      Create a new sheet with a pivot table that analyses your initial worksheet to count how many campaigns were successful, failed, cancelled, or are currently live per category.
  
  Create a stacked-column pivot chart that can be filtered by country based on the table that you created.
  
  Create a new sheet with a pivot table that analyses your initial sheet to count how many campaigns were successful, failed, or cancelled, or are currently live per sub-category.
  
  Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that you created.
  
  The dates in the deadline and launched_at columns use Unix timestamps. Fortunately for us, this [formulaLinks](https://www.extendoffice.com/documents/excel/2473-excel-timestamp-to-date.html) to an external site. that can be used to convert these timestamps to a normal date.
    
    Create a new column named Date Created Conversion that will use above formulaLinks to an external site. to convert the data contained in launched_at into Excel's date format.
    
    Create a new column named Date Ended Conversion that will use above formulaLinks to an external site. to convert the data contained in deadline into Excel's date format.
    
    Create a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and   
    Years.
    
    Create a pivot-chart line graph that visualises this new table.
  
  Create a report in Microsoft Word, and answer the following questions:
    
    1. Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?
    
    2. What are some limitations of this dataset?
    
    3. What are some other possible tables and/or graphs that we could create, and what additional value would they provide?
  Create a new sheet with 8 columns:
    
    Goal
    
    Number Successful
    
    Number Failed
   
    Number Cancelled
   
    Total Projects
    
    Percentage Successful
    
    Percentage Failed
    
    Percentage Cancelled
  
  In the Goal column, create 12 rows with the following headers:
    
    Less than 1000
    
    1000 to 4999
   
    5000 to 9999
   
    10000 to 14999
   
    15000 to 19999
   
    20000 to 24999
    
    25000 to 29999
   
    30000 to 34999
   
    35000 to 39999
   
    40000 to 44999
   
    45000 to 49999
    
    Greater than or equal to 50000

Statistical Analysis
    
    Creating a summary statistics table is one of the most efficient ways that data scientists can characterise quantitative metrics, such as the number of campaign backers.
    Ev
    Ealuate the number of backers of successful and unsuccessful campaigns by creating your own summary statistics table.
       
       Create a new worksheet in your workbook, and create one column for the number of backers of successful campaigns and one column for unsuccessful campaigns.A table containing a 
       column for the number of backers of successful campaigns and a column for unsuccessful campaigns.
       
       Use Excel to evaluate the following values for successful campaigns, and then do the same for unsuccessful campaigns:
           
           The mean number of backers
           
           The median number of backers
           
           The minimum number of backers
           
           The maximum number of backers
           
           The variance of the number of backers
           
           The standard deviation of the number of backers
       
       Use the data to determine whether the mean or the median better summarises the data.
       
       Use the data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?
