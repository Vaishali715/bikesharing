# Bikesharing
Using tableau to analyze bikeshare data in NewYork city.

## Overview of the analysis:
The purpose of this analysis is to see if the bike rental business is worth investing in for a different city(which the customer is requesting). One of the key factors we need to look at is tripduration. Finding out how long the trips are in the month of August, will give us a good analysis on when the bikes are rented, how long they are rented and what times are the most popular times to rent a bike. Before we do any of this there needs to be a change made in the csv to change the datatype of the column to dateTime and this was done using Pandas, as it is easy to change the datatype with help of Pandas instead of doing directly in tableau. Once the changes were made, new CSV was imported into tableau with the converted tripduration column.

## Results:
Using tableau we created different visulizations using the total number of trips, the types of users and the trip duration. Here's what we found:

There was a total of 2,344,224 trips in the month of August.

From the total trips 1,900,359 users subscribe to the company and 443,865 users are customers.

There is a peak number of users who rent their bike for 5-6 hour trips.

The largest number of individuals happen to be male, the women users dont have as large of a peak and unknown users do not have a peak for tripduration.

If you look at the trips per weekday(by hour) you can see that Thursday between 5pm-7pm is the most popular time to ride a bike.

To see all of my visualizations please click the link below:

[link to dashboard](https://public.tableau.com/profile/vaishali.rangari#!/)

## Summary:
Once I have completed my visualizations in tableau the one thing that stood out to me was Thursday is the most popular day to take a bike ride. It would be a good idea for our customer to start the bikeshare business in a different city because whether people are biking to get to work or just doing it for fun there are lots of users/ customers who will buy in. Although I think we have enough evidence to convince our customer to do this even if we are only looking at one month, there are some other visulizations that can further back this claim. If we were to look at the colder months in the city to see how many riders we have in November/December so that the customer can prepare for those months, One other visualization I would like to make is the average distance between customers home location and the bike renting location which would allow the customer to adjust for potential biker locations.