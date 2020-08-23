# PyBer_Analysis

### Overview of the analysis

The purpose of the analysis is to help PyBer with understanding the key metrics for the ride-sharing data by city type from Jan. 2019 to Apr. 2019 by creating DataFrames and to visualize the weekly fares total for each city type by using matplotlib. 

### Results
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types.

![PyBer summary](https://github.com/emmagao1/PyBer_Analysis/blob/master/Resources/DF.PNG)

Calculated total rides for each city types,total drivers for each city types,the total fares for each city types,the average fare per ride for each city types,the average fare per driver for each city types.To create the summary DataFrame, from the merged DataFrame got the total rides, total drivers, and total fares for each city type using the groupby() function on the city type.Calculated the average fare per ride and the average fare per driver for each city type.Deleted the index name pyber_ride summary_df.index.name. Created the summary DataFrame with the appropriate columns- Total fare,Average Fare per Ride,Average Fare per Driver formatted with currency dollar and rounded t 2 decimal place.

![PyBer fare summary](https://github.com/emmagao1/PyBer_Analysis/blob/master/PyBer_fare_summary.png)

The Total fare is shown by City Type. Rural,Subarban and Urban.The fare in Urban cities seems to be more than the rural and subarban is in the mid of the two. The trend seem to remain identical irrespective of the city.Sometimes between February and March sees the peak of the fare.


### Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types.

Additional analysis I
I will probably do a deep dive on Urban. Introduce some incentives such as earning reward point.That will increase the turnover in Urban areas
Technical Steps I will introduce a dataset rewards. add a filter to the cities and filter Urban to see the increase in the fare.
Additional Analysis II
I will dig deep into weekly analysis involving categories of riders. If we see the rides mainly to the downtown area during weekends or maybe at one particular time the riders are to a particular location where there is college I can come up with offers for those frequent riders.
The frequent riders can earn points and utilize that to purchase other stuff.
