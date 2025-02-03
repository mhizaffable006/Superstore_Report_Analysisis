# SUPERSTORE_ANALYSIS_USING_POWER BI

## Introduction

As part of assessment in the Data Analytics class organized by PSP_Analytics, one of the analytics projects I’ll be working on is the Superstore Dataset. This superstore is located in the United States of America and they sell Furniture, Office Supplies and Technology products. The superstore dataset contains the Order ID,	Order Date,	Ship Date,	Ship Mode,	Customer ID,	Customer Name and other data of the Super Store. The goal of this work is to analyze the Superstore’s performance and to uncover insights to be used for the business growth.

## Data Sourcing

This dataset used in this work is gotten from the Data Analytics Class announcement channel, which was posted by Mr. Kingsley Adisa.

## Data Preparation

We will load the Dataset in Excel format into Powerbi. If data is clean, we can just load it directly or transform it to clean it on PowerBi.

## Data Cleaning/Transformation

Here, we check if the format of each column is correct and correct it where necessary. We also address inconsistencies in the columns to ensure a more accurate dataset for analysis. 
  - Now, we format the Sales, Profit and Discount columns to display currency
  - Handle Missing Data.
  - Use the Filter button in column headers to remove irrelevant records.
  - Apply and Load the Cleaned Data.
  - 
## Data Exploration/Visualization

This is where we answered specific business questions for sale performance analysis by comparison using charts and tiles. Some of these questions include:
  1. Which Categories has the Highest Sales
  2. Sales Amount by Sub-Categories by Region
  3. Which Categories makes the higest Profit
  4. Which Year makes the most Sales
  5. Which Region purchased the most products by Categories
     
 ## KEY PERFORMANCE INDICATORS (KPI)
 
Before going ahead to answer the question, we first need to specify the KPI (Key Performance Indicators). The KPI include the Sales, Quantity, Profit and Discount. This is done by creating measures and using DAX to calculate the Total Sales, Profit, Quantity and to derive our Discount.
  - Sales: We use SUM function to get total sales
  - Quantity: SUM of quantity in the dataset
  - Profit: SUM of profit in the data set
  - Discount: SUM of total discount in the dataset
    
We then use the KPI tile to visualize our KPI. We could also use the Card tile.
  1. Which Categories has the Highest Sales?
      ![sales by categories](https://github.com/user-attachments/assets/f1a49c72-6406-405b-903b-d4c0921db3bc)

  2. In which Region make the most Sales?
       ![sales by region](https://github.com/user-attachments/assets/43b61d2d-4fcd-43d8-83d7-17ddc921d1c2)

  3. Which Categories makes the higest Profit?
       ![categories with highest profit](https://github.com/user-attachments/assets/29decb1e-02aa-4145-86cc-a5b7a0b5cfae)

  4. Which Year makes the most Sales?
       ![year with most sales](https://github.com/user-attachments/assets/7fcbab09-dec5-4bd0-ae70-1d0b49fca8ec)

  5. Which Region purchased the most products by Categories?
        ![image](https://github.com/user-attachments/assets/8d0f467d-aabe-41e3-bab4-06763d035b66)

     
## Conclusion
So far, we’ve been able to analyze the Superstore dataset and to draw valuable insights through the business questions. Based on these findings, we can be able to provide data-driven recommendations to help for business growth. The resulting dashboard built from powerbi is shown below:
![Superstore Dashboard](https://github.com/user-attachments/assets/9117f41a-8cdb-4500-b88a-48d65bf10dee)
