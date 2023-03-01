# Surfs up in Hawaii

## Overview 
The client is opening a Surf & Shake shop for local tourist providing easy access to surfboards and ice cream in Oahu, HI. In this analysis the client wants the local weather trends throughout the year to get a better understanding of likely revenue of ice cream sales, rental, and purchases of surfboards. 

## Analysis and Results
The key details to this analysis were retrieving the trends throughout the year, we deep dived June and December using sqlalchemy and pandas to create a data frame to provide the low, high, and average tempatures
> ### June Results
We started by acquiring the temperature statistics for June by finding all the weather station results from the region. One the data frame was retrieved, we pulled out the summary statistics with describe method to get the below summary:

![image](https://user-images.githubusercontent.com/124399950/222091578-919be83f-f770-4c57-a2ba-21e5ebab5c59.png)

> ### December Results
Using the same code to apply to December findings, resulted in the below summary:

![image](https://user-images.githubusercontent.com/124399950/222091500-89c9ad6e-4fc0-4683-b381-dade58d17a7b.png)

## Results
With this analysis from June and December the peak tempatures in Oahu, HI seem to be almost indistinguishable. 
* The maximum tempature in June is on two degrees higher than December; both months having comparably close maximum tempature points
* The average temperature is relatively close with June being three degrees higher than December
* The minimum tempature for December is about eight degrees lower than June
Overall the trends on temperature between June and December may have small deifference, however it is relatively small, and the ability to generate revenue based soley on temperature should be the same throughout the entirity of the year. To further elevate inquires, I would suggest an additional queury on rainfall throughout the year to determine how much outdoor activity is done to factor into overall profitability. 
