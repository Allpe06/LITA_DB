# LITA_CLASS DOCUMENTATION

### PROJECT TITLE: CAPSTONE PROJECT

### Project Overview
This project is to analyze the sales performance of a retail store.By analyzing the various parameters in the data received we seek to gather insight to make reasonable decisions which will enable to create a compeling story

### Data Sources
The primary source of Data used here is Captone data.csv and sales data.csv

### Tools Used
Miscrosoft Excel for data analysis, 
SQL - Strutured Query Language 
Power BI for data visualization and preparation of dashboard

### Exploratory Data Analysis
EDa involved the exploring of the Data to answer some questions about the Data such as:
-what is the total sales by product, region and month
- what is the highest-selling prodcut by total sales value
- who are the top 5 customers by total purchase amount
- sales overview, top-performing products and regional breakdowns.

### Data Analysis
This is where we include some basic lines of codes or queries or even some of the DAX expressions used during the analysis;

```SQl
SELECT sum(total_sales) as total_sales
from salesdata
Group by product
