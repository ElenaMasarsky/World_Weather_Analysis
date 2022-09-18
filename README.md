# World_Weather_Analysis
In this project we've been helping the travel technology company that specializes in internet related services in the hotel and lodging indusry to collect and present data for customers via the search page, which they will then filter based on their preferrd travel criteria in order to find their ideal hotel anywhere.
To perfom this task, we are using a Jupiter notebook and the city API module to get the cities for more than 500 random latitudes and longitudes then we perform requests on the open weathe map API and retrieve the chase on weather data. From these cities, the weather data is added to a Panda's data frame,
where we use Matplotlib to create a series of scatter plots to show the relationship between the latitude and a variety of weather parameters for over 500 cities around the US.
To do this analysis, we need to perform statistical calculations on the data using linear regression on the weather parameters in the Northern and Southern hemispheres.
This data will help our team predict the best time of year for people to plan their vacation.
Finally, we export the data, clean it and use the weather data to choose the best cities for a vacation based on certain weather criteria.
And then we map these cities using Jupiter G map and the Google places API.
