# surf_up
Surf's Up with Advanced Data Storage and Retrieval

## Purpose
Explain the structures, interactions, and types of data of a provided dataset.
Differentiate between SQLite and PostgreSQL databases.
Use SQLAlchemy to connect to and query a SQLite database.
Use statistics like minimum, maximum, and average to analyze data.
Design a Flask application using data.
## Overview:
An investor wants to learn more about the weather before committing to build a Surf and Ice Cream shop in Oahu, Hawaii. The investor's main concern is the precipitation forcing the shop to close too frequently. To analyze Hawaii's weather data, SQLAlchemy was used to query the SQLite database.

## Results:
June Statistics for the Temperature and Precipitation

![ssjune](https://user-images.githubusercontent.com/111541268/196742624-c475526e-6c40-4ab0-9c92-658e68ecde62.png)

December Statistics for the Temperature and Precipitation

![ssdec](https://user-images.githubusercontent.com/111541268/196742737-dfd22b55-1e69-42d4-89fd-d0ac8c01d7b6.png)


 1. The mean temperature of 75°F for June is higher than the mean temperature of 71°F for December. However, the opposite is true for precipitation. December had the higher precipitation of .22 inches while June had .14 inches.
 ![ssj](https://user-images.githubusercontent.com/111541268/196973428-d823529c-d880-4db0-8a8c-4c48d6308a92.png)


 ![ssd](https://user-images.githubusercontent.com/111541268/196973469-01d025ce-0575-4946-a0a2-2fe8ae961a3f.png)

 2. Grouping the data into 15 bins, the histograms visually show how the frequency centers around the two different means. For consistency of the graphs, the ranges of the axes were generated as the same for easier comparison using the minimum and maximum numbers from the descriptive statistics. Using the same range for the temperatures, June appears to have a slight left skew, where December is more symmetrical.
 
 
 ![ssjuneee](https://user-images.githubusercontent.com/111541268/196973519-fe939328-25b5-422a-814e-27866e5d39a2.png)


![ssdeccc](https://user-images.githubusercontent.com/111541268/196973575-8a3bad5c-3249-4d20-a5b1-5f7e4e1b9166.png)

 3.As an additional query, the June and December months were filtered from the date. The temperature and precipitation data was then graphed as a scatterplot with a trendline. Reading the slopes of the trendline equations, June (slope = -.037) has a slightly steeper slope than December (slope = -.019), which means as the temperature increases, the precipitation decreases slightly more in June than in December. However, the difference is nominal. Reviewing both scatterplots, the precipitation mostly stays under 3 inches with a few outliers over 3 inches of precipitation.
 
 
## Summary:
The investor's main concern was getting rained out too frequently. Comparing the June and December weather patterns, the temperatures and precipitation means are reasonably close. The temperature data is not strongly skewed for either month. The ratio of the temperatures to the precipitation for the two months is also reasonably similar with few outliers over 3 inches of precipitation. The data supports opening a Surf and Ice Cream shop year-round.
