# Bike Sharing Data Visualization

<a href='https://public.tableau.com/app/profile/vienna.rynerson/viz/NYCCitiBikeAnalysis_16569108498070/NYCCitiBike'>Tableau NYC Citi Bike Analysis Story</a>

## Overview of the analysis: 

Citi Bikes have been a successful transportation option in New York City for the last decade. From the daily commute to out of town visitors, biking has shown itself to be a great way to get to where you need to be or explore the city. The analysis on data from August 2019 in New York will help the client to convince investors that a bike-sharing program will be beneficial to the city of Des Moines, Iowa. 

## Results: 
Description of each visualization.

### Top Starting Locations

![start_locations](https://user-images.githubusercontent.com/98570777/177094832-798c6cf0-8d86-4d73-b4db-7b00f8fc3718.png)
</br>
This map shows the areas where the bikes were first checked out. There is a saturated area on the mid- and lower- east and west sides of Manhattan.

### Top Ending Locations

![end_location](https://user-images.githubusercontent.com/98570777/177095041-a2d11439-db28-4a37-81d1-7f2001c07d9a.png)
</br>
This map shows the areas where the biker completed their ride and dropped their bike off. There is a saturated area on the mid- and lower- east and west sides of Manhattan.

### Bike Checkout Duration

![bike_checkout_duration](https://user-images.githubusercontent.com/98570777/177095082-722939b5-ecf5-4df4-b599-6024aaaa4bdd.png)
</br>
This line graph shows the trip duration for the number of bikes checked out. The y-axis shows the number of bikes. The upper x-axis shows the hour elapsed and the lower x-axis shows the minutes elapsed since the ride started. There is a peak at 146,752 bikes riding for 5 minutes.

### Bike Checkout Duration by Sex

![bike_checkout_duration_sex](https://user-images.githubusercontent.com/98570777/177095172-36e7aebe-f123-45e8-9e77-eb9d0e4ce2bb.png)
</br>
This line graph shows the trip duration for the number of bikes checked out by sex: male, female or not reported. The y-axis shows the number of bikes. The upper x-axis shows the hour elapsed and the lower x-axis shows the minutes elapsed since the ride started. There is a peak at 108,087 males riding for 5 minutes, and another peak at 34,151 females riding for 6 minutes. For the unreported riders, there is a small peak at 7,389 rides with 11 minutes elapsed.

### Trips by Weekday per Hour

![trips_weekday_hr](https://user-images.githubusercontent.com/98570777/177095262-8fd4e416-4a69-46fb-b2fd-d1fe19e32dcb.png)
</br>
This heat map shows the number of riders per day of the week and time. There is a peak of 44,905 riders on Thursday at 6pm.

### Trips by Sex (Weekday per Hour)

![trip_sex_weekday_hr](https://user-images.githubusercontent.com/98570777/177096062-7e863e5b-dea7-4dcb-98cd-3b27db15727d.png)
</br>
This heat map shows the number of riders, broken down by sex: male, female, and not reported, against time and day. There are two high volume riding hours at 5 and 6 pm on Thursday among male and female bike riders. Male riders exceed female riders by about 20,000.  

### User Type Trips by Sex and Weekday

![user_type_trips_sex_weekday](https://user-images.githubusercontent.com/98570777/177095426-e7b5a5d8-dc47-44f3-ad8a-17223de0a559.png)
</br>
This heat map shows the number of riders by sex and then divides the data into user type. The user types are customer and subscriber, which correspond to a pay-per-ride model or a monthly/yearly subscription model, respectively. The subscribing riders have the most use on Thursdays, and the pay-per-ride customers have the most rides on Saturdays.

## Summary: 

The most concentrated areas of start and end locations were mid- and lower- east and west sides of Manhattan. This could be due to the tourist attractions, i.e. Times Square, Empire State building, museums and hotels. This could also be due to the office buildings nearby.

The highest amount of riders, male and female, borrow Citi Bikes for 5 and 6 minutes, respectively. Generally speaking, if you are in New York, the destination is not too far away; most people can ride a mile easily in 5 or 6 minutes.

The subscribers to the Citi Bike service tend to have the most amount of riders riding on Thursdays. This could mean they are commuters, so they live locally and use this service often enough to subscribe monthly or yearly. The subways could be too full of people rushing to get home from their 4 day work week, so New Yorkers opt for above ground transportation.

The non-subscribing customers have their highest amount of riders on Saturdays. These could be tourists and people that are wanting to see the city, but do not want to walk far or try to navigate the subway system. Or they want to take advantage of the nice August weather. (The dataset used is from August.) 

This data could help the city of Des Moines create their own bicycle sharing model. The citizens of Des Moines could reduce their carbon footprint from daily commuters, promote healthier lifestyles, and generate jobs for bike maintenance. 

An additional visualization that would have enhanced the visualizaiton story is a bar chart showing the peak hours of riding during the week. This would be similar to the heatmaps, but just another way for people to easily see the peak times. Another visualization that could have been included was a chart showing the start/end locations against time and day of week to visualize commuter vs tourist data.