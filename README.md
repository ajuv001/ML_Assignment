# ML_Assignment

Recruit Restaurant Visitor Forecasting 

Problem Statement:

The aim is to predict the future numbers of restaurant visitors. The data was collected from Japanese restaurants.The data comes in the shape of 8 relational files which are derived from two separate Japanese websites that collect user information: “Hot Pepper Gourmet (hpg)” and “AirREGI / Restaurant Board (air)”. The restaurants need to know how many customers to expect each day to effectively purchase ingredients and schedule staff members to mange the visitors coming in.Using the data of reservation and number of visits done by customer we need to predict the total number of visitors to a restaurant for future dates. 
https://www.kaggle.com/c/recruit-restaurant-visitor-forecasting 

Project Pipeline

•	Read and analyzed the data (.csv) files

•	Analyzed relationship between Hot Pepper Gourmet and AirREGI site data

•	Identified unique identifier of data from data relation

•	Combined both reservation systems. Data structure is the same, hence need to match store_ids

•	Merged air_reserve.csv and hpg_reserve.csv data based on store_id_relation

•	Added seperate column for vistor date of visit into month year and date for air_reserve.csv and hpg_reserve.csv

•	Added weight to Date_info data

•	Added day of the week and holiday flag to date_info.csv

•	Dropped duplicate data while merging the datas 

•	Checked NaN in dataframes

•	Defined date weighted mean function

•	Checked NaN in final result

•	Filled NaN using store_id and day_of_week

•	Fitted the data using Linear regression

•	Tried predicting the result using prdict function

•	Stored final predication result in the ‘RestaurantVisitorsPredictionResult.csv’ file.
