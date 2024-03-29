# COMP4254 Advanced Topics in Data Analytics FinalProject
Final Course Project for COMP4254 - Advanced Topics in Data Analytics

Objective
- We want to study if there is a relationship between temperature and sales of software in colder area of the world.
- We also want to do a time series forecast on the temperature and sales as a practice

Data Sources
1) 1C Company sales, provided on Kaggle. 
- It is an independent software developer, distributor and publisher with HQ in Moscow. 
- Data set covers shops in multiple cities, different categories, online and offline, from 2013 to 2015.

2) Moscow Airport METAR (Meteorological Aerodrome Report) data, provided by rp5.ru  


Project Platform: Databricks Community Edition  


Data Preparation & Manipulation  

- Sales data were filtered for Moscow, then aggregated, resulted in daily and monthly items sold and revenue
- Temperature (in oC) data were aggregated to get average by day and month as well
- The sales data and temperature were joint by having the same date for daily set, and by same month-year for monthly set

More details please check the ipynotebook.  

There are 2 parts of this project, the first is for data preparation, and the second is for machine learning for the daily & monthly data set, which has linear regression and time series analysis. The focus will be on the monthly one, because it provides better linearity and more stationary comparing to the daily ones. 

