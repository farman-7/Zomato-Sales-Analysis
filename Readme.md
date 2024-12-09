
# Zomato Sales Analysis 📊

## Overview
This project analyzes **Zomato's sales data** using **Power BI** to provide actionable insights into customer preferences, restaurant performance, and overall business growth. Leveraging data from multiple tables, the project demonstrates advanced visualization techniques, KPIs, and slicers to answer critical business questions.

---

## 📷 Screenshots

Include relevant screenshots here:
![image alt](https://github.com/farman-7/Zomato-Sales-Analysis/blob/main/Index.png)

---
![image alt](https://github.com/farman-7/Zomato-Sales-Analysis/blob/main/Overview.png)

---
![image alt](https://github.com/farman-7/Zomato-Sales-Analysis/blob/main/User%20Performance.png)

---
![image alt](https://github.com/farman-7/Zomato-Sales-Analysis/blob/main/City%20Performance.png)

---

## 📁 Data Sources

The following CSV files were imported into Power BI:  
1. **Food Table**: Contains food items and their categories.  
2. **Menu Table**: Details pricing and food availability.  
3. **Order Table**: Records orders placed, including quantities, prices, and timestamps.  
4. **Restaurant Table**: Information about restaurant locations, ratings, and cuisines.  
5. **User Table**: Customer profiles, including demographics and order preferences.

---

## 🚀 Key Business Questions Answered

1. **Which restaurants perform best based on revenue and ratings?**  
2. **What are the top-selling dishes and their contribution to overall sales?**  
3. **How does customer behavior vary across regions or time periods?**  
4. **Which days of the week and times of the day generate the most sales?**

---

## 💡 Measures and Calculations

The following measures were created to generate insights and visualizations:

| **Measure Name**           | **Description**                                                                 |
|-----------------------------|---------------------------------------------------------------------------------|
| **Total Revenue**           | `SUM(Order[Total_Price])`                                                      |
| **Total Orders**            | `COUNT(Order[Order_ID])`                                                       |
| **Average Order Value (AOV)**| `DIVIDE([Total Revenue], [Total Orders])`                                      |
| **Top Dish by Revenue**     | Identified using `TOPN` and `SUMX` functions.                                   |
| **Customer Retention Rate** | Percentage of repeat customers over a given time.                              |
| **Sales by Time of Day**    | Sales trends segmented into Morning, Afternoon, Evening, and Night.            |

---

## 📊 Dashboards and Visualizations

### Key Dashboards Created:
1. **Revenue Overview**:  
   - KPIs for **Total Revenue**, **Total Orders**, and **AOV**.  
   - Revenue trends by **week, month, or year**.  
   - Slicers for filtering by **restaurant, dish, or time period**.

2. **Top Performing Restaurants**:  
   - Revenue and order count by restaurant.  
   - Customer ratings plotted on a scatter chart.

3. **Customer Insights**:  
   - **Region-wise sales performance**.  
   - Demographics-based insights (e.g., age groups, location preferences).

4. **Order Trends**:  
   - Time-based analysis (day vs. night sales, weekdays vs. weekends).  
   - Popular dishes during peak hours.  

---

## 🎯 Tools and Techniques

- **Power BI**: For creating interactive dashboards and KPIs.  
- **DAX (Data Analysis Expressions)**: To define custom measures and calculated columns.  
- **Data Modeling**: Star schema to link tables effectively.  
- **Slicers and Filters**: For dynamic user interaction.  

---

## 🌟 Project Highlights

1. **Interactive Slicers**: Users can filter by **restaurant**, **time period**, or **customer region**.  
2. **Dynamic Visuals**: Top dishes and restaurants are updated dynamically based on filters.  
3. **Advanced KPIs**: AOV and Customer Retention Rate provide deep business insights.  
4. **Optimized Data Model**: Ensures faster loading and query performance.

---

## Sample Business Insights:
1. **Top-performing restaurants contribute 40% of total revenue, with the highest sales during weekends.**  
2. **"Cheese Burst Pizza" is the most popular dish, generating 12% of total revenue.**  
3. **Evening sales account for 50% of daily revenue, making it the most profitable time.**  
4. **Customers from urban areas have a 25% higher retention rate compared to suburban areas.**

---

## 📧 Contact Me

- **Email**: [Mail](mailto:md.farman.data@gmail.com)  
- **LinkedIn**: [Farman's Profile](https://www.linkedin.com/in/md-farman-2858a61ab/)  

