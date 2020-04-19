# 2019 Bay Wheels Ride Data Exploration

## Dataset

The data consists of information about the Bay Wheels (previously known as Ford GoBike) that is a regional public bicycle sharing system in the San Francisco Bay Area, California. Beginning operation in August 2013 as Bay Area Bike Share, the Ford GoBike system currently has over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. On June 28, 2017, the system officially launched as Ford GoBike in a partnership with Ford Motor Company.
The final (cleaned) dataset has 2300000+ bike rides that happen in 2019 in the San Francisco Bay Area and has 11 columns to be explored. The dataset contained features about how long trip took, start/end datetime, start/end station name and users types. 

See the original data [here](https://www.lyft.com/bikes/bay-wheels/system-data).

## Summary of Findings

In the exploration, I collect the data programmatically from the Bay Wheels website and gather all the data for the year 2019.
Then I explore the dataset, accessing each variable and marking all problems found for future correction.
The corrections in the cleaning part, involves adjustments in the type of columns, treating null values ​​and also creating new variables.
After processing and cleaning the data, step to make visualization/exploration divided into three to make univariate, bivariate and multivariate.
In the case of univariate I explore the variables individually, observing mainly their distribution of both categorical and numerical variables. Here I already had the insight that most trips are short-lived, indicating a pattern of trips between work, school and home.
I also noticed that there is a schedule within the day that most trips take place, that were at peak times and that are on weekdays, being less on weekends.
I also noticed that there are months of the year that there are more trips than other months, mainly in the month of March where it has the highest peak and the month of December that has the least use.
I also found that most users are subscribers to the service, few are single.
In the bivariate and multivariate stages, I delve deeper into the correlation between the variables based on what I had already discovered in the previous stages.

## Key Insights for Presentation

In my presentation, I focused on the pattern of users with subscription use mostly for moving between home, school and work, while single users use more for fun through a graph of trip duration distribution.
Then show how the distribution is between the types of users through a pie chart.
I was showing the relationship of trips times, which show users "Subscriber" with short trips, indicating travel journeys between places (home, works, schools), while single users have longer trips, probably for leisure.
In addition to the trips time, I also analyzed the trips periods and it became evident that users "Subscriber" travel more frequently during peak times during the weekdays, reinforcing the use for moving between work, home and school, while the individual has a usage profile more in the afternoon and on weekends.