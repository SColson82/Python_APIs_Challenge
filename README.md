# Python-API-Challenge

## WeatherPy

In this portion of the challenge we were to use Citipy to pull a random list of at least 500 cities and then run it through the OpenWeatherMap API to obtain information about the weather. We then took that information and analyzed it, creating visuals for maximum temperature, humidity, cloudiness, and wind speed according to latitude. Additionally, this data was loaded to a CSV file for further use on the next portion of the challenge. Then, we plotted each of these for both the northern and sounthern hemishperes and calculated the linear regression and variance (r). I observed the following from this data set:
* Temperature and latitude appear to have the greatest correlation with the maximum temperature appearing to be highest closest to the equator.
* There is no discernable correlation between wind speed and latitude.
* There appears to be a small correlation between latitude and both cloudiness and humidity however, I might would compare temperature to humidity and humidity to cloudiness to add to this analysis.

## VacationPy

Once the weather analysis was completed, the second portion of this challenge was to pull the data exported to CSV and use it to determine where our next vacation might be. First, all cities were run through Google Maps API to produce a heat map using the maximum humidity as the maximum "heat" on a heatmap.

![image](https://user-images.githubusercontent.com/83737584/127787857-11ef7413-350a-4006-8750-4942a748a585.png)

The information was then loaded into a dataframe and filtered based on the following (which are my personal preference for ideal vacation weather):
* Maximum temperature between 65-80 F
* Humidity less than 35%
* Cloudiness less than 20%
* Wind Speed less than 10mph

The resulting cities dataframe was then evaluated to find a hotel in the area of each of the coordinates listed and a map of the resulting hotels was produced:

![image](https://user-images.githubusercontent.com/83737584/127787925-2c38770b-80cb-4b9e-9a43-c5ed3388a230.png)

Then, finally, the map of hotels was overlaid onto the first heatmap:

![image](https://user-images.githubusercontent.com/83737584/127787974-59eb0340-4de8-4a47-9d09-bc039f662ae5.png)

## I've always wanted to visit Brazil!!

<hr>

Contact:

* https://www.linkedin.com/in/sharon-colson-515222210/
* sharon.colson@gmail.com



