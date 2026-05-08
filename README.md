# Porter Delivery Data Analysis 

## Project Overview

This project focuses on analyzing delivery data to understand the key factors that impact delivery time and overall operational efficiency. The objective is to identify patterns in demand, workload, and delivery behavior so that better decisions can be made to improve delivery performance and customer satisfaction.

---

## Data Cleaning

- Missing values were handled to maintain data accuracy  
- Date-time columns were properly converted for analysis  
- A new column `delivery_time_minutes` was created  
- Invalid and negative values were removed to ensure reliable results  

---

## Feature Engineering

- Created `order_hour` to analyze hourly demand  
- Created `day_of_week` to study weekly trends  
- Calculated `delivery_time_minutes` for performance tracking  
- Created `within_30_min` flag to measure efficiency  
- Derived `partner_load` to understand workload distribution  

---

## Analysis Performed

- Orders by Hour (to identify peak demand)  
- Orders by Day of Week  
- Category vs Delivery Time  
- Market vs Number of Orders  
- Market vs Delivery Time  
- Partner Load vs Delivery Time  
- Number of Items vs Delivery Time  

---

## Dashboard

Two interactive Excel dashboards were created:

1. **Demand & Time Analysis Dashboard**  
   - Shows peak hours and demand patterns  
   - Highlights how delivery time varies over time  

2. **Delivery Performance Dashboard**  
   - Focuses on operational efficiency  
   - Analyzes the impact of category, market, and workload  

These dashboards are designed to be simple, clean, and easy to interpret, allowing quick understanding of key insights.

---

## Key Insights

- Peak hours have a significant impact on delivery performance  
- Higher partner load often leads to delays in delivery  
- Some categories consistently take longer to deliver  
- Larger orders (more items) increase delivery time  
- Certain markets perform better than others in terms of speed  

---

## Tools Used

- Microsoft Excel  
- Pivot Tables  
- Data Cleaning and Transformation Techniques  

---

## Files Included

- Excel file (analysis and dashboard)  
- Dashboard screenshots  

---

## Conclusion

Through this project, I gained practical experience in analyzing real-world delivery data and understanding how different operational factors affect performance. I learned how to clean raw data properly, which is one of the most important steps before any analysis. Even small inconsistencies in data can lead to incorrect insights, so ensuring data quality was a key learning.

By working with Pivot Tables and structured analysis, I was able to identify meaningful patterns such as peak demand hours, workload distribution, and delivery delays. This helped me understand how factors like order volume, number of items, and partner load directly influence delivery time.

Building the dashboards improved my ability to present data in a clear and structured way. I focused on making the dashboards simple, interactive, and visually balanced so that insights can be understood quickly without confusion.

Overall, this project strengthened my problem-solving approach and helped me think more analytically about operations and efficiency. It also improved my Excel and data visualization skills, giving me hands-on experience in turning raw data into useful business insights.

---

## Project File

You can access the Excel file here:  
https://docs.google.com/spreadsheets/d/1q73zs8iM57o--1nT6yLoLec9Fik5Xj4h/edit?usp=drivesdk&ouid=111528310984881362924&rtpof=true&sd=true
