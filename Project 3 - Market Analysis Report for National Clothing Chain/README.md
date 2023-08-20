# **Project Overview**
An online national clothing chain needs help in creating a targeted marketing campaign. Sales have been flat and they want to lure lost customers back. They want to advertise specific products to specific customers in specific locations, but they don’t know who to target. They have three products in mind:
  Shirt: $25,
  Sweater: $100,
  Leather Bag: $1,000

  The goal is to conduct an analysis to determine the best product to advertise to each customer.

# **Project Specifications**
## **Power Query**
- The joined data on the ‘Product Inventory’ table of the Customer List is split into 6 columns, each labeled with correct formatting and no resulting Power Query errors.
+ The ‘Purchase List’ table is un-pivoted, organized, and has a date column that is correctly formatted as a date.

## **DAX**
- The income categories are defined using a DAX formula. The DAX formula are aggregating the different predicted customer incomes into buckets which can be used to create a histogram
- The product recommendations are defined using a DAX formula

## **Visualization and Analysis**
- A formula is created that can be used to predict customer incomes based on linear regression of sales and income. Using y = mx + b, the m and b variables are replaced with the actual values and presented in the written summary
- The histogram shows the distribution and shape of predicted income by category. The histogram is created using a column chart and DAX formula (the calculated column created earlier) to define the ranges/bins of the columns
- The scatter plot with trendline and correlation coefficient quick measure (on a card) is used to perform a regression analysis of the relationship between average household income by state and average 6 months sales by state
- The heatmap is used to visualize income household income distribution across the US
- Cross-filter: The histogram columns can be used to update the heatmap. The scatterplot can be used to update the histogram. The scatterplot can be used to update the map
- The 1-2 page written report provides a detailed summary of the results, conclusions, and recommendations of the analysis. The document contains a well-written executive summary and includes the following: • All 5 of the analysis questions are addressed with 1-2 sentences

## **Summary Report**
The report answered all of the five questions that are given by the examiners:
1. What is the correlation (R2 value) between sales and income?
   [There is a strong positive relation between the sales and income with R = 0.88 and R^2 = 0.78. ](url)
2. What is the correlation (R2 value) between customer ratings and product return rate?
3. What are the linear regression formulas to predict customer income from customer sales?
4. Which customer do you predict has the highest income?
5. Which product will be advertised the most?





  
