# Bike_sales_project
![Bike Picture](https://github.com/babit25/bike_sales_project/assets/108529070/e75db2e1-8e8f-40d1-8edd-60461424e04c)

[Image Credit](https://www.motorbeam.com/150cc-bike-sales-august-2021-bajaj-pulsar-150-regains-top-spot/)

# Introduction:
This is a Data analysis and visualization project about a bike sales company, which sells bikes in 3 different regions. The Project is part of the learning process of Alex the Analyst Boot camp. The project was done using Excel. 
# Excel Skills:
•	Data Cleaning

•	Excel Formula and function

•	Pivot table

•	Data Visualization and Dashboard

•	Filters and slicers
# The Data 
The data was gotten from [Here](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx) and it contains just 1 table with 13 columns. The table contains the following information about the customers; ID, Marital Status, Gender, Income, Children (Number of Children), Education, Occupation, Home Owner (if they were homeowners), Cars (Number of cars), Commute Distance, Region, Age, Purchased Bike.         ![bike_sales_dataset](https://github.com/babit25/bike_sales_project/assets/108529070/bff87019-8252-4441-b3d8-56b2896e24e2)

# Data Cleaning:
The data did not contain many errors. There were no Null values I removed duplicates from the dataset. 26 duplicates were removed.

# Excel formula and functions:
The Gender and Marital Status columns contain "M" or "F" & "M" or "S" for both Columns respectively. 
The **Find and Replace tool** was used to replace 
"M" for "Male" & "F" for "Female" in the Gender Columns 
"S" for Single and "M" for Married in the Marital Status columns

The Age Column was grouped into 3 groups and the Excel function **IF** was used to group the ages into 3:
a. 0 – 35 Youth
b. 35 -54 Adult
c. 55+ Old

Below is the formula:

**=IF(L2>54,"Old",IF(L2>=35,"Adult",IF(L2<35,"Youth","Invalid")))**
![Bike_sales_project](https://github.com/babit25/bike_sales_project/assets/108529070/3a1530fd-fc02-4dc5-81b3-01db92d682be)

# Pivot Table:
1.	Average Income
A pivot table was created to analyze the average income per gender and how this influences their purchase of bikes.
![PT Avg  Income](https://github.com/babit25/bike_sales_project/assets/108529070/c0362b1d-b468-4619-82e5-af191c8feebf)


2.	Commute Distance
A pivot table was created to analyze the commute distance daily and how it affects their purchase of bikes. The option for 10 + miles was changed to more than 10 miles in order to sort it out accordingly.
![PT Distance Commuted](https://github.com/babit25/bike_sales_project/assets/108529070/01a103c9-e27a-4e88-8e1e-a836751e34df)


3.	Customer Age
A pivot table was created to analyze how the different age groups make purchases
![PT Age group](https://github.com/babit25/bike_sales_project/assets/108529070/cfaadad6-89ed-406b-a869-c29b606992cf) 

# Data visualization:
Charts to visualize the pivot table were created 

1.	Avg Income per purchase

![Average income per purchase](https://github.com/babit25/bike_sales_project/assets/108529070/ba176a97-fdf2-4188-b514-b0bc95019e12)




2.	Customer Commute
  
![Customer Commute](https://github.com/babit25/bike_sales_project/assets/108529070/f2a14ee4-7de8-4c73-b342-e84f5a659230)



   
3.	Customer Age Group

![Customer Age Group](https://github.com/babit25/bike_sales_project/assets/108529070/c803d841-ab33-4576-979b-85be5ab58d76)

# Dashboard:
A Dashboard was created that shows all the charts and slices for filters.
![Bike_sales_Dashboard](https://github.com/babit25/bike_sales_project/assets/108529070/8f609850-e8c1-4780-9e53-bcd8e00cf829)

# Slicers AND Filters:
3 Slicers were added to the dashboard to filter by
a.	Marital status
b.	Education
c.	Region


# Insights:
1.	Male Customers purchased more bikes than female
2.	The higher the income of customers, the more likely to purchase bikes
3.	The Distance commuted affects the decision to buy a bike as customers who have to commute less distance buy more bikes.
4.	Adults between 35 & 55 are likely to buy bikes.

# Conclusion:
This project is my first Excel project and was a learning process.


























