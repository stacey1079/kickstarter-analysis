# Kickstarting with Excel

## Overview of Project
  In this Module 1 Challenge, I was to create two charts based on data pulled from the Kickstarter worksheet.  The first chart to create was Outcomes Based on Launch Date.  First, I needed to add a new column to Kickstarter to display just the Year from the Data Created Conversion column.  I did this by using the Year() function.  For this chart I created a pivot table with data from the Outcomes, Parent Category, Years, and Months columns in order to pull the appropriate data needed.  I added outcomes to columns to show 'successful', 'failed', or 'canceled'.  I added Months to rows so that it would list the data by month.  I added Parent Category and Years to the filters so that I could filter the Parent Category data to "theatre", and I filtered Years to be able to pull by month.  I then also added outcomes to Values so that the table would display how many Kickstarters existed for each month, in each category of successful, failed, or canceled.  I also filtered to sort the outcomes from Z to A so that successful would be in the first column.  From that data, I created a line chart to display to display the data.
  
  For the second chart, I needed to create a chart for the Outcomes Based on Goals.  First, I created a new worksheet with the columns for Goals, Number Successful, Number Failed, Number Canceled, Total Projects, and also Percentages for each; Successful, Failed, and Canceled.  This chart was to find these values for the 'Plays' Kickstarters. In the Goals column I created number labels to filter from Less than 1000, in ranges of 5000, up through 50,000 or More.  Then I needed to write a COUNTIF() function to create the values for the columns of Number Successful, Number Failed, and Number Canceled.  Then I found the totals by using the SUM() function for the appropriate rows, and columns.  I also calculated the percentages for successful, failed, and canceled campaigns. I then created a line chart to display the data for the Outcomes Based on Goals.
### Purpose
  This purpose of this challenge was to create charts for Louise to be able to visualize how well other campaigns did in relation to their launch date and fundraising goals.  I was to deliver two charts to Louise based on technical analyses drawn from the Kickstarter campaigns.  The first analysis was to visualize the relationship between the outcomes of the campaigns based on their launch dates.  The second analysis was to display the percentages of the outcomes of each campaign in relation to their funding goals.
## Analysis and Challenges
  Overall, the directions were very clear and easy to interpret into my work.  There were only small challenges I encountered such as figuring out the proper values to add into the pivot charts, and how to sort them appropriately.  
  
![image](https://user-images.githubusercontent.com/45715246/202884882-9bbd954a-d4f1-466e-bb39-c727672a7169.png)

  
### Analysis of Outcomes Based on Launch Date

### Analysis of Outcomes Based on Goals

### Challenges and Difficulties Encountered
  One of the challenges I faced for Outcomes Based on Goals was when writing the CountIFS function was finding the appropriate order to pull the data.  It took me a while to figure out that the formula would not work if I placed the 'greater than' or 'equal to' first values next to the 'less than' or 'equal to' larger value.  I still do not really know why it was necessary to put the data from column F in between the two, but the formula would not work otherwise for me.
  It also took me some time, along with many google searches, to figure out how to filter the Year by Months for the Outcomes Based on Launch Date chart. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?  
      **One conclusion** I can make about the Outcomes based on Launch Date is that the best months of the year to launch a campaign were May and June, as both months had over 100 successful campaigns.
      **Another conclusion** I can draw is that there were a very low amount of canceled campaigns for each month, and in October no campaigns were canceled.  This shows me that the majority of the campaigns were ran all the way through.

- What can you conclude about the Outcomes based on Goals?
    Because there were no Canceled campaigns, the percentages for the failed campaigns vs the successful campaigns were opposites.  The line chart displays this visually.
    
- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?
