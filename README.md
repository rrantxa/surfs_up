# **Surf's Up: An Analysis on Temperature Trends**
## Overview of the analysis
### *Purpose of the analysis*
The purpose of this analysis was to determine the viability of opening a surf/ice cream shop in Oahu, Hawaii. Now, one of the key elements to determine if this sort of business would be sustainable or not is temperature, as trends in temperature are a crucial factor both for surfing and for ice cream sales. 

Thus, we decided to examine temperature trends to determine if this new venture can be successful. In order to complete this analysis, we used the following tools:
- Jupyter Notebook
- Python SQL toolkit and Object Relational Mapper
- Pandas library

## Results
The results of our investigation provided very interesting information regarding the temperature trends in Oahu, Hawaii. 
### *Key takeaways*
The following are the main temperature differences between the months of June and December:

- The average temperatures for June and December are very similar. While there's an average temperature of 74°F during June, December has an average temperature of 71°F. This lets us know that there's more or less a stable average temperature year round. 
- The above statement is also true for maximum temperatures, as June has a maximum temperature of 85°F, while December got a maximum temperature of 83°F. 
- Nevertheless, December could prove to be a less stable month when it comes to a minimum temperature. While June has a minumum temperature that is only ten degrees away from the average temperature (64°F), December has a minimum temperature 15 degrees colder from the average temperature (56°F). 

## Summary
Overall, the results show that the temperature trends for June and December are more or less similar. And, while the only problem might be minimum temperatures during December, the average and maximum temperatures show stable weather. 

Now, although this information could prove that it would be a good idea to open up a surf and ice cream shop in Oahu, more information would certainly help the decision-making process. The following are two proposed queries to gather more weather data for June and December:

- A query that examines the data regarding precipitation trends for both months. This would allow us to determine if there is a higher chance for precipitations, which could have a negative impact on the surf and ice cream shop, as rain and other types of difficult weather could scare potential clients. This query would be done using SQL Alchemy and the Extract module to get the precipitation data for each month. The data would then be converted to a Pandas DataFrame and examined with the describe() function.
- A query to examine precipitation data versus average temperature. This would help us examine the correlation between precipitation and temperature, allowing us to examine if the low temperatures during December might be caused by rain or by other factors. This would be done by using the same method described in the previous query, except that this time we would extract both the 'tobs' (temperature) and the 'prcp' data on one DataFrame.