# Amazon Sales Analysis & Performance Dashboard

## 1. Project Overview
This project provides a comprehensive analysis of Amazon sales data. The primary goal is to identify sales trends, evaluate product and category performance, and deliver actionable insights through a dynamic, interactive dashboard. The entire analysis was conducted using Microsoft Power BI, showcasing a complete workflow from data extraction to visualization.

## 2. Tools Used
Microsoft Power BI Desktop: The core tool used for data modeling, analysis, and creating the interactive dashboard.

Power Query: Utilized within Power BI for the Extract, Transform, and Load (ETL) process. It was instrumental in cleaning, shaping, and preparing the raw data for analysis.

DAX (Data Analysis Expressions): Employed to create custom calculations and key performance indicators (KPIs) that are central to the analysis.

## 3. Project Workflow
The analysis was executed following a structured business intelligence workflow:

Data Transformation (ETL): The initial dataset was loaded into Power BI's Power Query Editor. In this stage, data was cleaned to handle any inconsistencies, data types were corrected, and the dataset was optimized for performance.

Data Modeling: A simple but effective data model was created. It consists of the main Amazon_Data fact table and a Calender Table dimension, which allows for robust time intelligence analysis.

DAX Calculations: Several key measures were written using DAX to provide deep insights into sales performance over time. These include:

YTD Sales (Year-to-Date Sales)

QTD Sales (Quarter-to-Date Sales)

YTD Product Sold

YTD Reviews

Dashboard Visualization: A one-page summary dashboard was designed to present the findings. It includes interactive filters, KPI cards, and various visuals to tell a clear story about the sales performance.

## 4. Data Model
The data model connects the main sales data with a dedicated date table, which is a best practice in Power BI for time-based analysis. This enables easy filtering and slicing of data by year, quarter, and month.
![Model](/Images/Model.png)

## 5. Dashboard & Key Insights
The summary dashboard provides a high-level overview of key business metrics and trends.

![Dashboard](/Images/Summary.png)

## 6. Conclusion
This Power BI project successfully translates raw Amazon sales data into a powerful strategic asset. The dashboard reveals clear seasonal patterns, identifies top-performing product categories, and highlights key products. These insights can be used to make data-driven decisions regarding inventory management, marketing campaigns, and strategic focus for the upcoming year.
