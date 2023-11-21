# Deforestation around the world

## Introduction

This is an SQL Project on Deforestation of diffferent countries around the world from year 1990-2016. We have three tables, the forest area table, the land area table and the region area.They all have four column each; The forest area table:country code,country name, year, forest area in sq/km, The land area table:country code,country name, year, land area in sq/mi, The region table: country code,country name,region(the region the countries are located),income group.
        
This analysis Project is to help  us reveal how deforestation rates have evolved in each country over successive years,Investigate the relationship between income groups and deforestation over time.

## Problem Statement

1. What are the total number of countries involved in deforestation? 
2. Show the income groups of countries having total area ranging from 75,000 to 150,000 square meter?
3. Calculate average area in square miles for countries in the 'upper middle income region'. Compare the result with the rest of the income categories.
4. Determine the total forest area in square km for countries in the 'high income' group. Compare result with the rest of the income categories.
5. Show countries from each region(continent) having the highest total forest areas
6. What is the percentage change in forest area compared to the total land area for each country in year 2016?
7. How does the forest area vary across each year?
8. Which countries have the highest and lowest forest area in the latest available year and show their income group?
9. Compare the average total land area of the two African region .
10. Show the income group of countries that have forest area more than 20,000,000sqkm

## Skill documented

These are some of the Sql Features used;
- Group By
- Where
- Cte
- Window Function
- Sub query
- Having

## Problem Solved

--Question 1: What are the total number of countries involved in deforestation? 

Select Distinct (country_name)  As No_of_country_involved_in_deforestation From [forest_area (1)]
Where country_name <> 'world';

![]()



