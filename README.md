# Story-of-change in census data
The American Community Survey can be incredibly daunting when one tries to download individual tables. Here I demonstrate how to access a table using the Census API and Cenpy interface. This one is the [Travel Time to Work](https://censusreporter.org/tables/B08303/) table. I decied to focus on Massachusetts because I read recently how commuting has worsened over the years in the state. 
<br>
I limit my analysis and mapping to just the travel time betwen 5minutes and 44 minutes to see how they have changed over the last 10 years. So, my data is from the tables from the ACS 2015 and ACS 2020.
With cenpy I am able to query the two surveys and directly grab my target columns. See Annotation on the process in the notebook itself.
