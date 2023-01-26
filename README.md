# Surfs-Up
Module-9

**Overview**

The purpose of this challenge is to find temperature trends for the months of June and December on Oahu, Hawaii in order to determine if a surf and ice cream shop buisness would be sustainable year round. Using Python, Pandas functions and methods, and SQLAlchemy, you’ll filter the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December and then convert that data to a list and then a DataFrame to generate the statistics. 

**Results**

Three key differences between weather in June and weather in December on Oahu is:
- That there is a 3.9 degree difference between the mean temperatures in June and December.
- June has a temperate range of about 21 degrees while December has a range of about 27 degrees. 
- The max temp is June is 85 and in December it is 83, showing there are hot days and a potential market for ice cream in the winter. 

**Summary**

The analysis shows that June had 1700 temperature points taken while December only had 1517. The data shows that June has a mean temperature of 74.9 and December of 71.0 showing only about 4 degrees of difference. While this weather data is helpful it does not provide any information on percipitation levels and where the surf/ice cream shop would be located. Knowing Oahu houses the largest city by population, Waikiki makes that a likely place to open shop but cost of living there is more. Moving over to the North Shore there is less people and less shops so a new shop might do well, plus in the winter months there are a lot of surf compeitions on that side of the Island so that potentially could bring in business. Two additional queries added were to look at the average December and June temps at each of the stations, and from that we can see that the averages are all the same across each station showing no variability across the Island, meaning that regarding temperature the Island relativly is the same in all places. However precipition levels would provide a better idea because in my experience no one wants to eat ice cream in the rain. 