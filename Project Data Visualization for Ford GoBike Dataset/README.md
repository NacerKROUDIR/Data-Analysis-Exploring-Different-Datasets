# Ford GoBike Trip Data Exploration
## by Nacer KROUDIR


## Dataset
This data set includes information about individual rides made by **Ford GoBike system**. This data file corresponds to February 2019 in San Francisco Bay area. The various features included in the dataset are:
- Trip Duration (seconds)
- Start Time along with date
- End Time along with date
- Start Station ID
- Start Station Name
- Start Station Latitude
- Start Station Longitude 
- End Station ID
- End Station Name
- End Station Latitude
- End Station Longitude
- Bike ID
- User Type (Subscriber or Customer)
- Member birth year.
- Member gender.
- bike_share_for_all_trip.

You can find the dataset on this [link](https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv)


## Summary of Findings
In the exploration, the Ford GoBike sharing system in the San Francisco Bay Area has shown to be a popular mode of transportation with a majority of trips taking less than 30 minutes. This fast and convenient mode of transportation is primarily utilized by subscribers, who make up the majority of the user base, with 75% of users being male. The San Francisco Bay Area is known for its bustling cities, and the popularity of bike sharing reflects this with three main areas of activity identified as San Francisco, Oakland, and San Jose. These cities are home to the three most active bike stations: San Francisco Caltrain Station 2, Market St at 10th St, and Montgomery St BART Station.

When it comes to trip duration, it has been noted that male riders tend to have shorter trip durations compared to female riders, and the same trend can be seen with subscribers having shorter trip durations compared to customers. Despite the differences in trip duration, the distributions of age with respect to user type are similar, leading to the conclusion that there is no relationship between age and user type. However, it is worth mentioning that female riders have a younger median age of 31 years old compared to male riders, who have a median age of 32 years old.

## Key Insights for Presentation

For the presentation, I focus on the duration as a primary variable of interest and I made it in two plots. Also, my analysis was concentrated on the geographical aspect by making a bar chart of the most active bike stations and by using the four columns representing the coordinates of start and end stations to visualze a heatmap on San Fransisco Bay area.
Before that, I made a pie chart to represent the demographic population, the pie chart shows the distribution of bike users' gender. At last, I added a scatter plot of the trip duration vs age grouped by user type to point out the relationship between the three variables.
