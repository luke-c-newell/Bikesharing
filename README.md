# Bikesharing 
## Overview
This repository contains a business presentation for a new bikesharing company based in Des Moines, Iowa. Using data from the NYC CitiBike scheme, I have created a number of visualizations to better understand the bikesharing business model and to highlight the opportunity to invest in a similar scheme in Iowa. 

The analysis was completed using csv bikesharing data from NYC in the month of August 2019, as well as the software programs Tableau, Jupyter Notebook and the Pandas library. My [Tableau Story](https://public.tableau.com/profile/luke.newell#!/vizhome/NYCCitibikeAnalysis_16115378960730/BikesharingStory "Check out my Tableau Story here!") contains the interactive charts seen below. The presentation is publically accessible, so please do take the time to check it out!
## Results
### Dashboard
In the month of August, over 2.3 million rides were completed in NYC. The majority of customers using the service are regular subscribers (over 80%) with men being the primary user demographic (over 65%). Younger people tend to use the service more than older people, but there is strong demand across a wide variety of age groups. 

![dashboard](https://github.com/luke-c-newell/Bikesharing/blob/main/images/dashboard.png "dashboard.png")

### Checkout Times
This chart shows that the most popular length of time for a bike rental is 4-6 hours, with the fewest number of rides lasting less than an hour. The chart follows a positively skewed curve up to the maximum rental time of 24 hours. This informs us that users rent the bikes for long periods of the day, with some users renting the bikes for up to 24 hours.

![tripduration](https://github.com/luke-c-newell/Bikesharing/blob/main/images/tripduration.png "tripduration.png")

### Checkout Times by Gender
This chart shows the length of bike rental for each gender. Some users did not disclose their gender and they are marked as unknown. The most popular rental duration for male users is 4-5 hours while for female users, the most popular duration was for 5-6 hours. As the most common rental time is around 5 hours for both men and women, this suggests that there is strong demand for bicycle rentals over a long period of time. This information will allow us to forecast demand for users in Des Moines and plan the number of bicyles required to maintain an efficient service.

![tripbygender](https://github.com/luke-c-newell/Bikesharing/blob/main/images/tripbygender.png "tripbygender.png")

### Weekday Trips per Hour
CitiBike rentals were most popular during the hours of 8am-9am and 5pm-7pm on Monday-Friday. Weekend hours were a lot more spread out with a steady stream of rentals from 10am to 6pm. This suggests that commuters are the most regular users of the service. This will allow us to market the service to commuters in the Des Moines area, who may be looking for a more eco-friendly and healthy mode of transport.

![tripsperhour](https://github.com/luke-c-newell/Bikesharing/blob/main/images/tripsperhour.png "tripsperhour.png")

### Weekday Trips per Gender
This chart shows the most popular times that men and women use CitiBikes. For both men and women, the trends are similar and show that the heaviest usage is in the morning and late afternoon M-F and during daylight hours on the weekend. 

![tripsperhourbygender](https://github.com/luke-c-newell/Bikesharing/blob/main/images/tripsperhourbygender.png "tripsperhourbygender.png")

### User Trips by Weekday by Gender
Male subscribers are the heaviest users of the service, with female subscribers completing the second largest number of rides. Non-subscription customers are most likely to use the service on the weekends. This information will allow us to focus our marketing efforts on reaching people who will likely become heavy users of the service.

![weekdaytripsbygender](https://github.com/luke-c-newell/Bikesharing/blob/main/images/weekdaytripsbygender.png "weekdaytripsbygender.png")

### Peak Hours for Trip Commencement
This chart shows the most popular rental times for all users. The morning and afternoon rush hours have been highlighted for emphasis. The times with the lowest usage are between the hours of 1am-5am. With usage being low during those hours, this suggests that during the night would be prime time for maintenance and cycle relocation activities.

![peakhours](https://github.com/luke-c-newell/Bikesharing/blob/main/images/peakhours.png "peakhours.png")

### Top Starting and Ending Locations
These charts show the most popular starting and ending locations for rentals in NYC. The number of rides is proportional to the size and color of each spot. The highest density of rides occur in Central Manhattan, with the number of rides slowly decreasing as you move away from tourism and business centers. This means that for Des Moines, bike locations should be centered around business hubs and popular tourist spots for maximum revenue. Also, we can ensure that the bikes are located near transportation hubs where they will likely be used during commuter rush hours, Monday through Friday. 

#### Starting Locations
![startlocations](https://github.com/luke-c-newell/Bikesharing/blob/main/images/startlocations.png "startlocations.png")

#### Ending Locations
![endlocations](https://github.com/luke-c-newell/Bikesharing/blob/main/images/endlocations.png "endlocations.png")

### Number of Rides per Bike
Each mark in this chart represents an individual rental bike and the number of times it has been checked out during the month of August. The bikes highlighted in red have been used over 300 times in the month. This shows that usage varies greatly across the fleet of bikes and regular maintenance will be required to keep the vehicles in good condition.

![maintenance](https://github.com/luke-c-newell/Bikesharing/blob/main/images/maintenance.png "maintenance.png")

## Summary
Overall, this analysis has provided useful background information for setting up a bike rental scheme in Des Moines, Iowa. Using the infomation gathered from NYC, we now understand the demographics of users of a bike rental service, the most popular rental times, the most popular locations and the also the importance of regular subscribers to a successful bikeshare company. 

Users in NYC are most likely to use the service during commuter hours Monday-Friday and all day on Saturday and Sunday. The service is most regularly used by male customers who use the service between 4-6 hours at a time. Most popular locations are around business and tourist hubs and the most popular start and end locations are in similar areas. 

These findings can be used as the foundation for setting up a successful company in Iowa, as the city has a healthy business district which could attract a large population of regular subscribers.

### Additional Visualizations
To expand the analysis, there are a couple of additional charts that I could create.

1. A chart showing the distance between start and end locations. This would allow us to understand how far the bikes travel during usage and plan any operational requirements for moving bikes between locations.
2. A chart showing the average number of trips by customer type. This would allow us to plan sales and marketing campaigns to ensure that we offer price plans that best serve our long term subscribers and short term customers.