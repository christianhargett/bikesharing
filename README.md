[Link to Tableau dashboard](https://public.tableau.com/profile/christian.hargett#!/vizhome/citibike_challenge_16028056973160/NYCStory?publish=yes)

# bikesharing

## Overview

Citi Bike is a bike sharing app that allows people in NYC to rent out bikes by the trip. After visiting NYC with our friend, Kate, we decide that we want to bring the bike sharing market to Des Moines. Kate knows an angel investor that is prepared to hear our pitch, but first we must put together an analysis in order to better understand the bikeshare market in NYC. In order to do this, we will look at bikeshare data for the month of August. We will use Tableau in order to better understand the trends in the bikeshare data.

## Results

After analyzing the bikeshare data for the month of August, 2019, we have been able to identify key trends that will help us bring the bikeshare market to Des Moines. 
![](https://github.com/christianhargett/bikesharing/blob/main/Summary_stats.png)

We can tell that the sheer volume of rides in the month of August is substantial. At 2.3 million rides, effectively 28% of NYC's population used Citi Bike's bikesharing service in the month of August. This is a staggering number, and if we are able to capture the same percentage of market share in Des Moines then we will certainly be successful.

Additional trends that we are seeing is that the majority of bikeshare users are subscribed to Citi Bike's services. This information is helpful and it tells us that we need to heavily market our subscription services when we bring the bikeshare market to Des Moines. 

Another data point is that the male gender makes up vast majority of bikeshare users. With this information we know that we should focus on marketing towards other genders in order to gain more non-male users. 

Lastly, we can derive from the graphic that the peak hours for bikeshare usage is late morning as well as late afternoon. This is important because if we implement bikesharing in Des Moines, we know for a fact that we need to have bikes available during those times. If any bikes were to be out of commission, perhaps for maintenance, then we know that the best times for that are early in the morning (1 am - 4 am). 

We were also able to plot out total checkout times by user, as well as checkout times by gender.
![](https://github.com/christianhargett/bikesharing/blob/main/Checkout_time_by_user.png)

![](https://github.com/christianhargett/bikesharing/blob/main/Checkout_times_by_gender.png)

These graphs tell us:

When looking at the overall trips by weekday by hour, we arrive at the below graphic:

![](https://github.com/christianhargett/bikesharing/blob/main/Trips_by_weekday_per_hour.png)

With this heatmap we can determine a few things:
- During the week, the busiest times are mid-morning and the afternoon. We can likely infer that this high volume is driven by commuters using bikeshare to get to and from work.
- The busiest days of the week are Saturday and Sunday. On these days, users are most active from 10 am - 7 pm. 
- The least busiest time is 1 am - 4 am on any week day. This aids us in scheduling maintenance hours for the bikes.

We have created a similar graphic, however we have broken it down by gender:

![](https://github.com/christianhargett/bikesharing/blob/main/Trips_by_gender_weekday_per_hour.png)

This heatmap shows similar trends to the one above it, however this new heatmap accentuates the trend of Citi Bike capturing more male users than non-male users.

Our final graphic breaks down user trips by gender by weekday:

![](https://github.com/christianhargett/bikesharing/blob/main/User_trips_by_gender_by_weekday.png)

With this heatmap we are able to determine the busiest days by gender as well as by user type. As expected, the most common user is a male who is subscribed to Citi Bike's services. The most common days that these types of users use the bikeshare app are Thursday, Friday, Tuesday, and Monday (in that order). 

## Summary

After analyzing trends in Tableau with the data provided, we are much more confident in our abilities to bring bikesharing to Des Moines. We have been able to determine the most common days of the week that users will tend to use the app, as well as the most common hours on those specific days. With this information we will be able to tweak our supply chain of bikes so that we provide the optimal amount of bikes for users. We can also determine the best times of the day/week to perform maintenance on these bikes. We were also able to determine the most common user of bikeshare (a male who is subscribed to the bikeshare service). With this information we know that we should heavily market our subscription services to potential-users, considering those types of users make up the vast majority of Citi Bike's users in NYC. We can also determine that we need to make an effort to market to non-male users in order to increase overall market share. 

Additional trends that we might consider looking into before delivering our final pitch to investors are location data and start data. For instance, I would be interested in mapping out the most common start points for users at specific times of the day. I would do this by plotting out the most common start points on a map and analyzing why those are the most common start points. With this data we would be able to predict where in the city that user are most likely to hop on a bike at any given time. 

Another plot I would be interested in seeing is average trip duration by birth year. With this information we would be able to see how long each age group generally spends riding the bike per trip. I would go about doing this by creating bins of trip duration (ie. 5-10 mins is one bin, 10-15 mins is another bin, etc.) and plotting out trip counts within those bins by age group on a bar chart. With this data, we could then look into the reasons why certain age groups spend longer/shorter amounts of time on the bike. Once we determine those drivers, the company could look into improvements that would cause each age group to spend longer amounts of time on the bike (ie. better bike seats, higher quality gears, increased app functionality, etc.)



