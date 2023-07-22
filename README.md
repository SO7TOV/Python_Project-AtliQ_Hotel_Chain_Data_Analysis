# Python_Project-AtliQ_Hotel_Chain_Data_Analysis

## Problem Statement:

AtliQ Grands a hotel chain company which runs many 5 star hotels in different cities of india. They have been in this industry for around 20 years. AtliQ Grands are facing a major challenge from their competitors, they are losing their revenue and marketshare.So, AtliQ management has decided to onboard data analytics and they want to inculde data informed decision making to improve their revenue and marketshare

The dataset which AtliQ has provided have information about their day to day bookings from various hotels like (AtliQ seasons, AtliQ palace, etc.), different types of rooms ranging from standard to presidential. Also, not only they accept booking from their website but also from third party websites, offline bookings, etc. All this information is gathered in one database which contains many csv files like:

1.dim_date.csv
2.dim_hotels.csv
3.dim_rooms.csv
4.fact_bookings.csv
5.new_data_august.csv
6.fact_aggregated_bookings.csv

## Data Analytics Pipeline:

###  Understand Business problems >>>> Data collection and understanding >>>> Data cleaning and exploration >>>> Data transformation >>>> Collect insights

#### We will be using Jupyter Notebook and conduct an analysis through pandas 

#### 1. Understanding business problems 

#### 2. Data collection and understanding 
-    Reading files 
        
#### 3. Data cleaning and Exploration 
-    Clean invalid guests
-    Outlier removal in revenue generated
  
#### 4. Data transformation 
-    Changing data type of date column from different dataframes
-    Create occupancy percentage column
  
#### 5. Collect insights 
-    Average occupancy rate in each of the room categories
-    Print average occupancy rate per city
-    When was the occupancy better? Weekday or Weekend?
-    In the month of June, what is the occupancy for different cities?
-    We got new data for the month of august. Append that to existing data
-    Print revenue realized per city
-    Print month by month revenue
-    Print revenue realized per hotel type
-    Print average rating per city
-    Print a pie chart of revenue realized per booking platform
