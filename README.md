# Tableau_Bikesharing

[link to dashboard](https://public.tableau.com/profile/jason.toledo#!/vizhome/NYCCitiBikeAnalysis_16024527261300/NYCCitiBikeStory?publish=yes "Link to Dashboard")

## Overview

The purpose of this analysis in Tableau was to take raw data from the NYC Citi Bike site and transform it into a series of data visualizations to understand the breakdown of the days of the week and users who use the service. I was tasked with converting the tripduration column from an integer value to a datetime value using Python via Jupyter Notebook then using the file for the analysis. Once the visualizations were built, I put them together into a comprehensive story in Tableau.


## Results

The results were interesting and to give a breakdown of how each viz provided information:

- NYC Peak Hours in August: The peak hours with the most trips were 5pm and 6pm

- Gender Breakdown: Male users dominate female users by approximately 7:1 and unknown gender users by about 3:1. Users identified as male make up more than half of all users.

- Checkout Times by Users: This viz showed there were the most users during 5/6

- Checkout Times by Gender: The trip duration among males was definitely higher than females and unknown gender users

- Trips by Gender: We can see that during the week, 8am and 5-6pm were the most popular times and on the weekends the time was more evenly distributed among all users

- Trips by Weekday: We can see that Thursday has the most usage in both the morning and the evening and Saturday has much more usage than Sunday

- Trips by Usertype: This viz shows the huge difference between subscribers and occasional users. Again, the theme is males dominate the users. Also, can clearly see that the unknown gender users do not have may subscribers have much more casual users.

My favorite visualization made in this challenge was the "Checkout times by Gender" viz https://github.com/jasonatoledo/Tableau_Bikesharing/blob/main/checkout_times_by_gender.png.


## Summary

Overall, the results show usage is more heavily male-dominated with the peak hours matching typical work start and end times. The highest usage day of the week is Thursday. The weekends have more steady usage throughout the day. Subscribers make up a big part of the total usage compared to casual users. Two additonal visualizations that could be helpful for future analysis would be 1) A histogram to show the difference between subscribers and occasional customers and 2) A scatterplot to show the relationship between subscribers and gender.
