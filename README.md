# PyBer_Analysis

# Overview

This analysis explores ride-sharing data by type of city to help inform strategic business decisions for PyBer.

## Results

Analyzing the data revealed several differences by city type:

* Total rides in Urban cities are 2.6x higher than the number of rides in Suburban and 13x higher than in Rural

* 93% of total fares are from Suburban and Urban cities
 
* The combination of high average fares and low number of drivers in Rural cities results in the highest average fare per driver
 
* Average fare per ride and average fare per driver are closest in Suburban cities
 
* Urban cities generate the highest total fares, however average fare per ride is the lowest
 
* In Urban cities, lower average fare per ride and high driver count result in the lowest average fare per driver

   ![City_Type_Summary](https://github.com/degitaccount/PyBer_Analysis/blob/main/Analysis/City_Type_Summary.png)


* Total fares drop during the last week of February for all city types

* Urban fares peak in late February and become highly volatile during March
 
* Suburban fares peak in late February, drop sharply during the lasty last week of February, then remain somewhat stable until early April when they start to rise again
 
* Fares in Rural cities are more volatile from Jan-Feb when compares to March-April


   ![Pyber_fare_Summary](https://github.com/degitaccount/PyBer_Analysis/blob/main/Analysis/PyBer_fare_summary.png)

## Summary

Based on my analysis of the fare data, I am recommending the actions listed below.  When reviewing the recommendations please consider that the fare data provides insights for where to dig deeper but may not be sufficient for a final decision.  My recommendations reflect where supplemental research and/or analysis should be considered.

1.	Consider offering customer incentives during the periods during which total fares tend to drop.

2.	Analyze the current and future demand for ride-sharing services for each city type to decide whether to expand or discontinue operations in certain areas.  For example, Urban cities make up only 7% of total fares with only 125 rides from Jan-April but deliver the highest average fares.  The key question is whether to exit or expand services in Urban cities.

3.	Analyze competitor rates to determine whether rate adjustments could help to improve total fares.  For example, higher rates in Rural cities will improve total and average fares.  If we take it a step further and reduce the number of drivers, the average fare per driver could improve significantly.

4. An additional consideration is to gather the number of hours each driver is working and calculate their average earnings per hour.  The average hourly rates should be checked for compliance with federal and local legislation regarding wages to ensure there are no pay-related legal risks for the company. _(Note: We could derive a reasonable estimate of hours worked with the current dataset by looking at the time of the first and last trip for each driver on each day.)_  


