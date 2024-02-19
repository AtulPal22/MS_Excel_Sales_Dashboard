# MS Excel Sales Dashboard

### Dashboard File Link:  [SalesDashBoard-2.xlsx](https://github.com/AtulPal22/MS_Excel_Sales_Dashboard/files/14329785/SalesDashBoard-2.xlsx) 

### Dashboard PDF Link: [ExcelSalesDashboard2014-17.pdf](https://github.com/AtulPal22/MS_Excel_Sales_Dashboard/files/14329778/ExcelSalesDashboard2014-17.pdf)

## Problem Statement

There is a company that runs their business in the United States that is doing the sales of different product categories and segments and They want us to help them create an interactive Dashboard so, they can easily track, analyze, and compare their sales for the years 2016 and 2017. This dashboard helps them understand category-wise, segment-wise, or sub-category-wise sales and other Insights also.


### Steps followed 

- Step 1: Open the Excel file in  MS Excel that contains the data for preparing a report.

- Step 2: I did the Data Cleaning process to check whether the file contains correct data or is in the correct format like I've removed error values, blank cells and corrected the format of the headers organized the data, and corrected the data or records in the table.

- Step 3: I did Data Processing, It is used for doing additional calculations which helps in analyzing while creating a Dashboard.

- Step 4: I did a Data Analysis process, in this, I created Pivot Tables and Pivot Charts and Placed all the Pivot Charts into a separate worksheet.
  - I've created a pivot table that represents the total sales amount and total profit amount for the years 2016 and 2017. This pivot table is used to show sales and profit growth against the previous year. So, the formula used for this:  

        sales growth % = (sum of sales for 2017 / sum of sales for 2016) - 1  
        Profit growth % = (sum of profit for 2017 / sum of profit for 2016) - 1 
    
    After that, I created cards using the text box did some formatting, and showed the values in the cards of Sales Growth vs PY  and Profit Growth vs PY. 

  - I've created the cards using a text box that represents the sales and profit of the latest Year, and the previous year. Added slicers for filtering the data based on Category and Segments by connecting the Cards pivot table.  

  - I have created a pivot table 1 that shows the sum of sales for the years 2016 & 2017 based on sub-categories and pivot table 2 that shows the sum of sales based on city for the years 2016 & 2017. Added slicer based on category and connected it with the pivot table 1 and pivot table 2.  
  - I have created a pivot table 3 that shows the sum of sales for the years 2016 & 2017 based on sub-category and pivot table 4 that shows the sum of sales based on city for the years 2016 & 2017. Added slicer based on segment and connected it with the pivot table 3 and pivot table 4. After that, I used cell referencing to refer the cells for fetching the values from the pivot tables 1,2,3, and 4 where it is created, and showed it to the dashboard page.    
  
      
        formula used,  =IF(OR(WorkingTables!A14=0,WorkingTables!A14="-"),"",WorkingTables!A14)  
  
  - I've used custom formatting for showing the high and low icon. the custom format is used:  

      
        [Color10]0.0%▲;[Red](0.0%)▼  

  - I've created a pivot table named Data Chart 1 which shows the sum of sales and the sum of quantity quarterly for each given year and fetches the values from the pivot table to other cells for making the combo chart based on them.  

  - A combo chart was created which is a combination of Clustered columns and a line chart which shows quarter-wise sales for each year in the columns and a line chart shows the price for each quarter year-wise.  

  - I've created a pivot table named Data Chart 2 which shows the sum of sales as per states in the U.S. Added a Clustered column chart that shows the states with the highest sales of all time. after that, I added slicers for filtering the chart as per ship mode, category, and segment and made the connection between data chart 1 & 2 pivot table. 


## Cards Snapshot  

![card1](https://github.com/AtulPal22/MS_Excel_Sales_Dashboard/assets/87119559/8637308a-f03b-4da2-bae2-305aced3abb5)  
![card2](https://github.com/AtulPal22/MS_Excel_Sales_Dashboard/assets/87119559/c992f0c8-d9fe-48eb-af0f-be2a9356e6ca) 

![card3](https://github.com/AtulPal22/MS_Excel_Sales_Dashboard/assets/87119559/370b052d-b066-406e-a223-ca4222a6938b)

![card4](https://github.com/AtulPal22/MS_Excel_Sales_Dashboard/assets/87119559/f914cdf0-7d51-42b6-bb9e-2f28722cb3e4)

![card5](https://github.com/AtulPal22/MS_Excel_Sales_Dashboard/assets/87119559/3f0fddba-01bc-4436-8f59-a87546ce6663)

![card6](https://github.com/AtulPal22/MS_Excel_Sales_Dashboard/assets/87119559/c645c85d-99af-4a8f-9d87-0d2994939343)


## Dashboard Snapshot (MS Excel)

![ExcelSalesDasboard2](https://github.com/AtulPal22/MS_Excel_Sales_Dashboard/assets/87119559/8649f20b-f883-4468-959a-66c2aaf4d13b)


# Insights

A single-page Dashboard was created on MS Excel.

The following inferences can be drawn from the dashboard;

- California, New York, and Texas are the top 3 leading states among all states that have the overall highest sales of all time.  

- In quarter 4 of the year 2016 had the highest overall sales. 

- Sales increased by (~20.4%) in the year 2017 as compared to the previous year.

- Profit increased by (~14.2%) in the year 2017 as compared to the previous year.  



