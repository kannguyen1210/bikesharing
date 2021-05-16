# bikesharing

# Overview
For this analysis, I’ll use Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, I’ll create a set of visualizations to:

1. Show the length of time that bikes are checked out for all riders and genders
2. Show the number of bike trips for all riders and genders for each hour of each day of the week
3. Show the number of bike trips for each type of user and gender for each day of the week.

Finally, I’ll add these new visualizations to the two you created in this module to create a Tableau Story

# Results
For an interactive experience, please find the Tableau story [here](https://public.tableau.com/profile/giang.nguyen5384#!/vizhome/challenge_16212028461750/NYCCitibike).

## 1. August Peak Hours
![alt text](/images/August_Peak_Hours.png)

From this visualization, we can see that the peak hours are 7-8 am and 4-7 pm which is when people go to work or head back home. Also the activity is low from 2-4 am which we can use this time for bike maintenance without disrupting services.

## 2. Top Sharing Locations
![alt text](/images/Top_Sharing_Location.png)
From this visualization, we can see that the Manhattan area is the most busy, which means we should put more bikes and stops at this location to maximize our profit.

## 3. Checkout Times for Users
![alt text](/images/Checkout_Times_for_Users.png)
From this visualization, we can see that our services are highly used for short period of time hence it is very suitable for when our users need to get to a destination nearby that is too far to walk but too short for a metro ride.

## 4. Checkout Times by Gender
![alt text](/images/Checkout_Times_by_Gender.png)
As for this visualization, we can see that men tend to use our service much longer than the rest. This tells us that we need to advertise for woman and other genders more to boost our sales and brand recognition for this segment.

## 5. Trips by Weekday for Each Hour
![alt text](/images/Trips_by_Weekday_for_Each_Hour.png)
From this heatmap, we can see that our service is being used heavily during weekday at rush hours. However, just for Wednesday, the usage drops significantly compare to the rest of weekday, we need to dwelve more into this anomaly to find out why and come up with a remedy strategy if needed.

## 6. Trips by Gender (Weekday per Hour)
![alt text](/images/Trips_by_Gender.png)
For this heatmap, it reinforces our previous findings with #5 and we can conclude that the drop in usage on Wednesday is non distinct between genders.

## 7. User trips by Gender by weekday
![alt text](/images/Trips_by_Gender_by_Weekday.png)
For this heatmap, we can see that our subscribers use our services very frequently on weekdays, especially among men and that our customer usage are quite evenly distributed across weekdays.

# Summary
Overall, these visualization gives us a lot of excitement as we have identified that our services serves a much needed demand for commuting during rush hours. With these findings, we can look into strategy to boost our sales by marketing campaign that targets rush hours or office commuters as they are a great fit as our customers for rush hours commuting.