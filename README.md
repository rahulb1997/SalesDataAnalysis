# Sales Data Analysis Project

## Overview

This repository contains a comprehensive analysis of sales data from 19 different countries. The data has undergone cleaning in Excel, exploratory data analysis (EDA) in a Jupyter notebook using pandas, numpy, matplotlib, and seaborn, and the insights are visually represented using Power BI.

## Files

1. **sales_data.csv:** This file contains the cleaned sales data of 19 countries.

2. **Sales_Data_Cleaning.csv:** CSV file documenting the data cleaning process.

3. **Sales_Data_Exploration.ipynb:** Jupyter notebook file containing Python code for exploratory data analysis using pandas, numpy, matplotlib, and seaborn.

## Data Structure

### sales_data.csv

1. **ORDERNUMBER:**
   - *Description:* A unique identifier for each order.

2. **QUANTITYORDERED:**
   - *Description:* The quantity of products ordered in each order.

3. **PRICEEACH:**
   - *Description:* The unit price of each product in the order.

4. **ORDERLINENUMBER:**
   - *Description:* Line number associated with each item in the order.

5. **SALES:**
   - *Description:* The total sales amount for the order (QUANTITYORDERED * PRICEEACH).

6. **ORDERDATE:**
   - *Description:* The date when the order was placed.

7. **STATUS:**
   - *Description:* The status of the order (e.g., Shipped, In Process).

8. **QTR_ID:**
   - *Description:* The quarter in which the order was placed.

9. **MONTH_ID:**
   - *Description:* The month in which the order was placed.

10. **YEAR_ID:**
    - *Description:* The year in which the order was placed.

11. **PRODUCTLINE:**
    - *Description:* The product line to which the ordered product belongs.

12. **MSRP:**
    - *Description:* Manufacturer's Suggested Retail Price for the product.

13. **PRODUCTCODE:**
    - *Description:* Unique code associated with each product.

14. **CUSTOMERNAME:**
    - *Description:* The name of the customer placing the order.

15. **PHONE:**
    - *Description:* Contact phone number of the customer.

16. **ADDRESSLINE1:**
    - *Description:* The first line of the customer's address.

17. **CITY:**
    - *Description:* The city where the customer is located.

18. **COUNTRY:**
    - *Description:* The country where the customer is located.

19. **CONTACTLASTNAME:**
    - *Description:* Last name of the contact person associated with the order.

20. **CONTACTFIRSTNAME:**
    - *Description:* First name of the contact person associated with the order.

21. **DEALSIZE:**
    - *Description:* The size of the deal, categorized based on sales volume (e.g., Small, Medium, Large).

## Data Cleaning

The sales data has been cleaned and preprocessed using Excel. Detailed steps can be found in the `Sales_Data_Cleaning.xlsx` file.

## Data Exploration

Explore the sales data using the provided Jupyter notebook (`Sales_Data_Exploration.ipynb`). The notebook includes in-depth exploratory data analysis using popular Python libraries.

## Power BI Dashboard

- https://app.powerbi.com/groups/me/reports/1d64bc0e-e39e-41a2-a13a-ee15b038f290/ReportSection42cfb0cc8f214e3437fd?experience=power-bi

## Usage

1. Open the Jupyter notebook (`Sales_Data_Exploration.ipynb`) to understand the exploratory data analysis process.
2. Review the Excel file (`Sales_Data_Cleaning.xlsx`) for insights into the data cleaning steps.
3. Explore the Power BI Dashboard for interactive visualizations and comprehensive insights.

Feel free to use and adapt the code and visualizations for your specific needs. If you have any questions or need assistance, please don't hesitate to contact.

Happy analyzing!
