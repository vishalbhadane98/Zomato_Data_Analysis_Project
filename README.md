# Zomato Data Analysis Project

## Overview
The **Zomato Data Analysis Project** involves exploring and analyzing the Zomato dataset using SQL Server. Zomato is an Indian multinational restaurant aggregator and food delivery company. This analysis aims to provide insights into the business operations of Zomato by examining a dataset consisting of over **9,000 rows** featuring columns such as **Restaurant_ID**, **Restaurant_Name**, **City**, **Location**, **Cuisines**, and more.

## Objectives
During the data exploration phase, I focused on the following tasks:
- **Schema Examination**: Reviewed table details, including column names, data types, and constraints.
- **Data Cleaning**: Checked for duplicate values in the **Restaurant_ID** column and removed unwanted columns.
- **Data Merging**: Merged two different tables, adding a new column for **Country_Name** using the primary key **CountryCode**.
- **Data Correction**: Identified and corrected misspelled city names.
- **Rolling Counts**: Utilized window functions to count the number of restaurants with rolling counts.
- **Statistical Analysis**: Analyzed minimum, maximum, and average values for votes, ratings, and currency columns.
- **Category Creation**: Created a new category column for ratings.

## Insights Gained
After thorough data exploration, I proceeded to analyze the data and uncovered several key insights:
- Approximately **90.67%** of the dataset pertains to restaurants in India, followed by the USA at **4.45%**.
- Among 15 countries represented in the dataset, only two offer online delivery options: India (28.01%) and UAE (46.67%).
- Focusing on Indian restaurants revealed that **Connaught Place** in New Delhi has the highest number of listed restaurants (**122**), followed by **Rajouri Garden** (**99**) and **Shahdara** (**87**).
- The most popular cuisine in Connaught Place is North Indian food.
- Of the 122 restaurants in Connaught Place, only **54** offer table booking facilities.
- Average ratings for restaurants with table booking facilities stand at **3.9/5**, compared to **3.7/5** for those without in Connaught Place.
- The best moderately priced restaurant (average cost for two < 1000, rating > 4, votes > 4) that provides both table booking and online delivery options is located in Kolkata, India, named "India Restaurant" (Restaurant ID - 20747).
