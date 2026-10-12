# Restaurant Sales Dashboard – Excel

## Project Overview

This project is a restaurant sales analysis and dashboard created in Microsoft Excel.

The project started with raw restaurant order data and was cleaned and prepared for analysis using Power Query. I then used Pivot Tables, Pivot Charts, Slicers and a Timeline to analyze sales performance and build an interactive dashboard.

The Excel workbook contains the complete project, including the data preparation, analysis and final dashboard.

## Objective

• Analyze restaurant sales performance
• Understand revenue performance across categories and menu items
• Identify top-performing items
• Analyze sales by month and hour
• Compare item sales across categories
• Build an interactive Excel dashboard

## Tools Used

• Microsoft Excel
• Power Query
• Pivot Tables
• Pivot Charts
• Slicers
• Timeline
• Excel Formulas

## Data Preparation

The raw data was prepared before creating the dashboard.

The main steps included:

• Checking the structure and data types
• Cleaning text fields
• Converting date and time fields into usable formats
• Creating Month Name and Start of Month fields
• Creating Week of Year and Hour fields
• Merging order data with menu data using Item ID
• Checking missing Item IDs and unmatched values
• Preparing the final data for Pivot Table analysis

Rows with missing Item IDs were not manually assigned or deleted during the cleaning process.

## Analysis

The analysis includes:

• Overall revenue
• Revenue by category
• Revenue by menu item
• Monthly revenue
• Weekly revenue
• Hourly revenue
• Number of items sold
• Item sales by category
• Top 10 items by revenue

## Dashboard

The final dashboard includes:

• Total Revenue KPI
• Total Items Sold KPI
• Monthly Revenue Trend
• Weekly Revenue Analysis
• Revenue by Category
• Top 10 Items by Revenue
• Hourly Revenue Trend
• Order Items by Category
• Category Slicer
• Order Date Timeline

The dashboard allows the user to filter the analysis by category and date.

## Key Insights

• Italian category generated the highest revenue.
• Korean Beef Bowl was the top revenue-generating item.
• Revenue peaked around 12 PM.
• February had the lowest monthly revenue.
• American category generated the lowest revenue.
• Asian category had the highest number of items sold.

## Revenue Calculation

For this project, the Price field was used to calculate the sales amount because each order-detail row represents an item sold.

Revenue = SUM(Price)

This calculation is based on the structure and assumptions of the available dataset.

## What I Learned

Through this project, I practiced:

• Data cleaning using Power Query
• Working with date and time data
• Merging tables using common IDs
• Creating helper columns
• Building Pivot Tables and Pivot Charts
• Using Slicers and Timelines
• Creating KPI cards
• Analyzing sales data
• Presenting business insights through an Excel dashboard

## Dashboard Preview

![Restaurant Sales Dashboard](Dashboard_Screenshot.png)

## Project Files

• Restaurant_Sales_Dashboard.xlsx – Complete Excel project including data preparation, analysis and dashboard
• Dashboard.png – Final dashboard preview
• Insights.md – Key findings from the analysis
