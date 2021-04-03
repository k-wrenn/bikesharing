# bikesharing

## Project Overview
The purpose of this analysis was to examine CitiBike data from August 2019 in New York City to discover patterns and trends for potential investors in a similar bike sharing program in Des Moines, IA.

## Resources
Data Source: 2019-09-citibike-tripdata

Software: Tableau Public 2021.1, Jupyter Notebook, Python 3.7.9

## Analysis
First, let's examine the top checkout locations:
![Start](https://github.com/k-wrenn/bikesharing/blob/main/Images/Starting_location.PNG)

In the map above, the darker and larger the circle, the more checkouts occured at that CitiBike location. A majority of bike checkouts occur in the Lower Manhattan area. 

Now, let's look at the peak hours of bike usage:
![Peak](https://github.com/k-wrenn/bikesharing/blob/main/Images/Peak_hours.PNG)

The heaviest usage is at 5:00 p.m., with over 220,000 users at that time, followed closely by 6:00 p.m., with approximately 215,000 users.

Next, a heatmap was created that looked at bike usage by day of week and time of day. Again, the darker the color the heaver the usage:

![per_hour](https://github.com/k-wrenn/bikesharing/blob/main/Images/Weekday_per_hour.PNG) 

As we can see, there is heavy bike usage at 8:00 a.m., 5:00 p.m., and 6:00 p.m. Monday through Friday but especially on Thursdays at 5:00 p.m. and 6:00 p.m. This would suggest that most people are using the CitiBike as transport to and from work.

Then, the above heatmap was further broken down by gender, weekday, and time of day:

![hour_gender](https://github.com/k-wrenn/bikesharing/blob/main/Images/Weekday_per_hour_gender.PNG)

This map shows that both males and females use the bicycles more during the start and end of the work day during the work week, but men use the bikes more heavily during these peak hours, as indicated by the darker red.

Another heatmap was created that shows the breakdown by usertype (customer vs. subscriber) as well as weekday and gender:

![Usertype](https://github.com/k-wrenn/bikesharing/blob/main/Images/Usertype_gender_weekday.PNG)

Here, we can see that subscribers, especially males, are more likely to use the bikesharing system on weekdays, whereas short-term customers, likely tourists, are more likely to use the bicycles on weekends than the subscriber usertype.

Now, we'll examine trip duration amongst all users:

![Checkout_time_users](https://github.com/k-wrenn/bikesharing/blob/main/Images/Checkout_Time_Users.PNG)

There is a very noticeable peak at the 5 minute mark, meaning most users take short rides.

Trip duration was also separated out by gender below:

![Chekcout_time_gender](https://github.com/k-wrenn/bikesharing/blob/main/Images/Checkout_Time_Gender.PNG)

As illustrated above, a 5 minute bike ride seems to be the peak trip duration amongst genders as well, there is no one gender skewing the first trip duration graph. This graph also further re-iterates that males use the CitiBike program the most.


A link to the full Tableau workbook can be found here: [NYC CitiBike](https://public.tableau.com/profile/kylie2306#!/vizhome/BikeSharing_16173285143220/NYCCitiBikeAnalysis?publish=yes)
## Summary

Based off of the results above, males use CitiBikes more than females in every aspect we examined. The most popular time to use CitiBikes, regardless of gender, are weekdays before and after work hours and users are most often using them for short, 5 minute, rides.

For further analysis, however, it may beneficial to compare the demographics of Des Moines to that of New York City. NYC is very densley populated and has many tourists. If demographics are too dissimilar, find a city with similar demographics to that of Des Moines and perform an analysis on that city's CitiBike program and its success. 

It would also be beneficial to perform all the above analyses during a winter month to see how winter weather affects usage. With Des Moines being in the midwest, winters can be brutal, often times with below freezing tempuratures, which may cause a drastic drop in bicycle usage. Harsh winter weather may also cause more wear and tear on the bicycles requiring more repairs per bike. Does the use of the bicycles during the warmer months offset the loss of use and cost of repairs during the winter months? If not, Des Moines may not be an ideal market for CitiBike.
