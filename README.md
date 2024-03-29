# Surfs_up

## Overview of the statistical analysis:
Before investing money into building a Surf and Ice Cream shop in Oahu, Hawaii, an investor (W.Avy) wants to learn more about the weather. The investor is concerned about the frequent closings caused by precipitation. Querying the SQLite database with SQLAlchemy allowed us to analyze the Hawaiian weather data. In order to determine if the surf and ice cream shop business is sustainable year-round, the investor requests temperature data for the months of June and December on Oahu.Using Python, Pandas functions and methods, and SQLAlchemy, filtered the date column of the Measurements table in Hawaii. SQLite database to retrieve all the temperatures for the month of June and December. Then converted those temperatures to a list, created a DataFrame from the list, and generate the summary statistics.


## Summary Statistics for June
Using Python, Pandas functions and methods, and SQLAlchemy, filtered the date column of the Measurements table in Hawaii. SQLite database to retrieve all the temperatures for the month of June.  Then converted those temperatures to a list, created a DataFrame from the list, and generate the summary statistics. 
* Mean 75 
* Total count 1700
* Maximum 85

## Results
![Capture](https://user-images.githubusercontent.com/58860105/137639413-ec562c43-5bfe-4f92-b7ba-68af770fe218.PNG)



## Summary Statistics for December
Using Python, Pandas functions and methods, and SQLAlchemy, filtered the date column of the Measurements table in Hawaii. SQLite database to retrieve all the temperatures for December.  Then converted those temperatures to a list, created a DataFrame from the list, and generate the summary statistics. 
* The total count 1517
* The mean 71
* The maximum 83

## Results
![2 2](https://user-images.githubusercontent.com/58860105/137639657-33ab5b9c-a8c2-4135-9abd-639b2d0b9cc7.PNG)


# Summary
Although our data tells us what our temperatures are, it also shows that we can run more queries that can help us decide whether customers can visit the shop since weather also includes certain attributes such as precipitation. The more data we collect about the area, the more likely we are to make educated decisions.
