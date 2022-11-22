# Pyber_Analysis

## Project Overview
Pyber, a ridesharing app, neeeded me to analyze all of the ridesharing data from January to early May of 2019.  The goal of the anlysis was to understand the differences between ridesharing data from three different city types - urban, suburban and rural.       

## Resources
Analysis was done with the following resources:

* Data Source:
    * city_data.csv
    * ride_data.csv
* Software:
    * Python version 3.9.12
    * Jupyter Notebook 6.4.12

## Results
* In order to begin the analysis, I merged the two csv files I got from Pyber (city_data.csv and ride_data.csv) into a combined DataFrame (pyber_data_df).  I then performed some analysis on this DataFrame to produce a summary DataFrame.


![Summary_DataFrame](https://user-images.githubusercontent.com/115426070/203418487-62ccf17c-9085-4225-92f5-5e3f2033d7c9.png)


* It is clear from the summary DataFrame and the image below that the urban cities have a much higher volume of total rides and total drivers than the other two city types.  
* We can also see that the average fare per driver and average fare per rider were higher for the suburban and rural cities, with the highest averages belonging to the rural cities.  

![Fig1 ](https://user-images.githubusercontent.com/115426070/203422454-1b65ec06-d2d2-4b3e-a4f6-3bc4ebb70e3b.png)

* My analysis in the summary DataFrame and image below show that total fares are greatest in the urban cities and least in the rural cities.


![Pyber_fare_summary](https://user-images.githubusercontent.com/115426070/203422529-d7f24f4d-ff92-4f3b-94cb-7ab98d0b5de3.png)



## Summary
Based on the results of my analysis, I have  a few recommendations for the CEO of Pyber.

* Since the volume of riders in urban cities is much higher than in suburban and rural cities, it might be beneficial to allocate resources to the urban cities so they can hire more drivers in order to handle the load better.  I also suggest that Pyber analyze the data further to determine if most rideshare users are repeat Pyber customers or unique users.  This would help determine if a "frequent rider" membership program might be a good way to encourage more use in the Pyber ridesharing program. 
* The average fares per rider and driver are both higher for rural and suburban areas, presumable because the rides need to cover more distance in less populated areas.  One way to maximize profitabilities for these types of areas would be to use vanpools so more passengers could ride together to a common location.  The Pyber CEO could even organize with large employers in the area so commuters could organize into vanpool groups.     
* The number of drivers is the lowest in the rural cities.  I would recommend that the CEO investigate whether there is a lack of people with vehicles or if potential drivers do not understand the value of ridesharing.  I would also recommend that she conduct some research into what incentives rural drivers might find enticing.     


 





