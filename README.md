# PCMLAI Practical Application 1
 Required Assignment 5.1: Will the Customer Accept the Coupon?
 The dataset contains various attributes about the customers, their preferences, and the type of coupon offered. Our goal is to find the insights to see what factors influence acceptance of the coupon.


# Approach

## Dataset consists of 12,684 records with 26 columns, including categorical data such as destination, weather, coupon, and numerical data like temperature and some binary flags (Y, direction_same, etc.). Some columns also contain missing data, especially car, which has many null values.

## I applied what I’ve learned so far in class. I have strong MS SQL Server skills, so it was easy for me to create queries to get the desired results. I used both queries and DataFrame filters to apply my newly acquired skills.

## In MS SQL Server, there isn’t an easy way to create crosstabs like in MS Access and Crystal Reports. However, I found it straightforward to use.

## I frequently used the GROUP BY clause with SIZE to understand the data types in a column and set my filter conditions. Without this step, my queries could have been incorrect. For example, the age column had values like “below 21” and “above 50,” so any numeric filter like “below 21” would have returned ambiguous records.

## I also sorted the data by the age column. This was easy for me since I often use sorting algorithms to create dummy sort columns in SQL

## Summary outcomes
### At age 21, it shows the greater tendency to accept the coupons.
### It decreases by age and suddenly goes back up at 50plus.
### Single customers have the highest acceptance rate 60%. 
### Widows are less likely to accept coupons at about 47%.
### Healthcare Support occupation has the highest acceptance rate 69%.
### Retired customers accepts the least at 54%.
### In the morning time coffee house coupon acceptance is higher.
### Most coupons for coffee are accepted around 10AM and when temperature is in 80s.
### For both Bar and Coffee house, people accept more coupons when they are alone.


## Jupyter Notebook is uploaded at GITHUB 
https://github.com/vbudhiraja/PCMLAI-Practical-Application-1