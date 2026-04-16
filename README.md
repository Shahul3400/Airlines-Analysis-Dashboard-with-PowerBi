✈️ Airlines Analysis Dashboard

📊 Project Overview

The Airlines Analysis Dashboard is a data analytics project designed to explore airline operations, performance, and passenger trends. It provides interactive visualizations and insights to help understand factors such as delays, flight frequency, and airline efficiency,Revenue.

This project demonstrates skills in data cleaning, exploratory data analysis (EDA), and dashboard visualization using tools like Power BI.

🎯 Objectives

Analyze airline performance across different routes and time periods

Identify patterns in flight delays and revenue

Compare performance between airlines

Provide actionable insights for improving operational efficiency

🛠️Tools & Technologies Used

Power BI – Data Visualization

Power Query – Data Cleaning and Transformation

DAX (Data Analysis Expressions) – Data Calculations

Kaggle Dataset – Airlines Analysis

Microsoft Excel – Data Preparation

📁 Dataset Information

The dataset contains Airlines Analysis information including:
1.	FlightID
2.	Date 
3.	Airline
4.	Source
5.	Destination
6.	Arrival_Time
7.	Departure_Time
8.	Durtion_Mintues
9.	Distance_Km
10.	Price
11.	Stop
12.	Class
13.	Booking_Channel
14.	Customer_age
15.	Customer_gender
16.	Bagging_Kg
17.	Route
18.	Profit

These attributes help analyze Airlines analysis and identify attrition trends.

Data Cleaning & Preparation

 Data cleaning was performed using Power Query Editor to ensure data quality.

Steps performed:

 Removed duplicate records

 Handled missing values

 Converted column data types

 Renamed columns for better readability

 Created calculated columns

 Removed unnecessary fields

This ensured the dataset was structured and ready for analysis.

Data Modeling

A structured data model was created using Fact and Dimension tables.

Fact_Table

Fact_Flights

 It contains the Airlines data which reuired for Fact Table 

Dimension Tables

Dim_Date

 Airlines Date such as Year,Day,Month,MonthName

Dim_Services

 In this contains the data Such as Class,Booking_Channel,Seat_Type.

Dim_Location 

 In this Contains the data Such as Route,Source,Destination

Dim_Customer

 In this contains the data such as Customer_age and Customer Gender

 Relationship will created by the fact table to Dimension table 

DAX Measures

Several DAX measures were created for analysis:

 Total Flights

 Total Profit

 Total Revenue

 Profit margin%

 Revenue per Flight

 Load Factor%

These measures helped calculate important Airlines analysis Dashboard.

Dashboard Pages

The Power BI dashboard contains Four analytical pages.

1. Executive Overview Dashboard

Key Visualizations:

  KPI Cards(Total Flights,Total Revenue,TotalProfit)

  Total Revenue by month 

  Total Flights by Class

  Total Revenue by Airline 

  Top 5 Revenue

This analysis will help the how much revenue are generated 

2. Time Intelligence Dashboard

  This Dashboard shows time anlysis of Flights

  Visualizations include:

  Total flights Arrival Time 

  Total Flights Booking_Channel

  Total Flights Departure Time

  Total Flights by Month 

This Analysis will help the Time intelligence Report

3. Route Analysis
   
  Sources and Destination

  Delay_Flights

  Total Revenue by Route

This Route analysis will help how the Filghts will travel 

4.Customer Insights

  Customer_Age

  Customer_Gender

  Seat_Type

This Customer insights help which seat_Type is booked 

📈 Key Insights

  Certain airlines consistently show higher delay rates

  Peak delays occur during specific months/seasons

  High-traffic routes tend to have more delays

  Some airlines maintain better on-time performance across all routes

Conclusion

  The Airlines Analysis Dashboard provides a comprehensive view of airline operations by transforming raw flight data into meaningful insights. Through this analysis, we identified key patterns in flight delays, cancellations, and overall airline performance.

Author

 Shahul

 Aspiring Data Analyst

Skills:

 Power BI

 Data Analytics

 SQL

 Excel

 Data Visualization














