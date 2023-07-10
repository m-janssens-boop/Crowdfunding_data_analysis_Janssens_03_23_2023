# Crowdfunding_data_analysis_Janssens_03_23_2023

Background
-----------
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. 
From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.
To receive funding, the project must meet or exceed an initial goal, 
so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success.

## Objective ##
Organize and analyze a database of 1,000 sample crowdfunding projects to uncover any hidden trends.
This is done through:
* Conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.
  * Creating a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
* Conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale starts at 0 with a dark shade of red, and transitions to green at 100 and blue at 200.
   * Creating a new column called Average Donation that uses a formula to find how much each project backer paid on average.
   * Creating two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.
   * Creating a new sheet with a pivot table that analyzes the initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.
* Creating a stacked-column pivot chart that can be filtered by country based on the table that was created.
* Creating a new column named Date Created Conversion that converts the data contained in launched_at into Excel's date format.
* Creating a new column named Date Ended Conversion that converts the data contained in deadline into Excel's date format.


