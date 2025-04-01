# Project 1: Excel Coffee Shop Sales Dashboard

![Image Alt](https://github.com/cturner0206/coffee-shop-sales-dashboard/blob/dc89c4948c43132bb9b4bca6e2b8c6a14be9309f/Dashboard.png)


# Table of Contents 
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Data Preparation and Cleaning](#data-preparation-and-cleaning)
- [Building the Dashboard](#building-the-dashboard)
- [Findings](#findings)
- [Recommendations](#recommendations)

# Project Overview

The goal of this project was to develop a comprehensive Q1-Q2 sales dashboard for a coffee shop solely using Microsoft Excel. This dashboard aims to enable informed decision-making for business strategies, helping the coffee shop optimize operations and improve sales. 

### Objectives of the Dashboard:
**Sales Performance Insights:**  
- Analyze overall sales performance to identify trends and patterns.

**Customer Trends:**  
- Understand customer behavior and preferences.

**Product Popularity:**  
- Evaluate which products are performing well to inform inventory and marketing strategies.

# Data Source
The sales data used in this project is the `CoffeeShopSales.xlsx` file. 


# Data Preparation and Cleaning

The initial data preparation and cleaning phase involved the following steps:

- **Understanding the Dataset:**  
  Reviewed the different columns in the dataset to gain familiarity.

- **Inspecting Columns:**  
  Checked for any necessary changes or inconsistencies in the data.

- **Data Cleaning with Power Query:**  
  Performed the following cleansing steps:
  - Assigned column headers and renamed columns for clarity.
  - Changed data types. 
  - Split the product detail column to create a separate column for product size.
  - Removed duplicates and corrected spelling errors in product names.
     > **Note:** Some minor spelling errors were not caught at first and were later found when using slicers on the dashboard.

    

# Building the Dashboard

To create the dashboard visuals, pivot tables were utilized to organize and segment the sales data. Each visual on the dashboard is based on its own individual pivot table.

### Choosing Visuals:

To allow end users to gain valuable insights from this dashboard, I decided to incorporate:

- Cards to show an overview of total sales and transactions.
- Line charts to highlight trends over time to identify patterns relating to sales throughout the year and the day.
- Bar chart to allow for sales comparisons across the three locations, making it simple to spot performance variations on items.

### Interactivity Features:
- **Slicers and Timeline:**  
  Linked to the pivot tables, slicers and a timeline are used to enable interactivity and filtering options for end users. Users can dynamically filter visuals by:
  - Product type/details
  - Store locations
  - Time periods

This interactivity allows for tailored insights and more in-depth analysis.

### Additional Information:
- A notes page is included for clarifications on how to interact with the dashboard for users who may be inexperienced with Excel features.


### The different pivot tables used: 

   
 ![Image Alt](https://github.com/cturner0206/coffee-shop-sales-dashboard/blob/dc89c4948c43132bb9b4bca6e2b8c6a14be9309f/Table1.png) 
![Image Alt](https://github.com/cturner0206/coffee-shop-sales-dashboard/blob/dc89c4948c43132bb9b4bca6e2b8c6a14be9309f/Table2.png)
![Image Alt](https://github.com/cturner0206/coffee-shop-sales-dashboard/blob/dc89c4948c43132bb9b4bca6e2b8c6a14be9309f/Table3.png)
![Image Alt](https://github.com/cturner0206/coffee-shop-sales-dashboard/blob/dc89c4948c43132bb9b4bca6e2b8c6a14be9309f/Table4.png)
![Image Alt](https://github.com/cturner0206/coffee-shop-sales-dashboard/blob/dc89c4948c43132bb9b4bca6e2b8c6a14be9309f/Table5.png)



# Findings

### **Daily Sales Trends:**  
  - Daily sales peak between approximately **7 AM and 10 AM**, regardless of the month or store location.

### **Month-over-Month Sales:**  
  - Sales have been steadily **increasing month-over-month**, with February showing slightly lower sales than January, likely due to fewer days in the month.

### **Sales by Location:**  
  - Each of the three store locations has total sales of around **$230k**:
    - Hell's Kitchen: **$236.5k**
    - Astoria: **$232.2k**
    - Lower Manhattan: **$230k** 
  - All locations exhibit very similar top-selling product trends over both quarters.

### **Top 10 Products as a Percentage of Total Sales:**  
  - The percentage of total sales attributed to the top 10 selling products by location is as follows:
    - Astoria: **80.74%**
    - Lower Manhattan: **78.3%**
    - Hell's Kitchen: **77.7%**

### **Total Transactions:**  
  - Lower Manhattan has approximately **3,000 fewer total transactions** (47.7k) compared to the other two locations, which each have around **50.6k transactions**.

  
# Recommendations

**Evening Sales Initiatives:**
 - Explore opportunities to increase sales during slower hours (after 10 AM). Consider offering discounts or special events in the late afternoon or evening to attract customers.
   
**Morning Promotions:**
 - Capitalize on peak hours by offering morning specials (e.g., buy one, get one free, or discounts on certain drinks) to increase foot traffic.
   
**Diversify Menu:**
 - Given the reliance on the top 10 products, consider introducing seasonal items or limited-time offerings to attract customers and keep the menu fresh.

