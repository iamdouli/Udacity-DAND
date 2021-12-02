# Ford GoBike Data Exploration

## Dataset

The dataset used for this exploratory analysis consists of monthly individual trip data from January to December 2019.  
We gathered the data directly from [here](https://s3.amazonaws.com/baywheels-data/index.html),
with feature documentation available [here](https://www.lyft.com/bikes/bay-wheels/system-data).

## Summary of Findings

In the exploratory Analysis phase, we found that there was any relationship between the duration of the bike rides and the distance traveled, and the Bike share system is mostly used by Subscribers then Customers.  The riding habit varies a lot between subscribers and customers, Subscribers  use the bike sharing system for work commute, thus most trips were on work days (Monday to Friday) and especially during commute hours in the morning and afternoon, whereas customers tend to ride in the afternoon or early evenings over weekends.

Additionally, weekday and commute time greatly influences the likelihood of a trip being a subscriber. Particularly, if a bike ride is on a weekday, the trip is more likely to be made by a subscriber than a customer. Similarly, a trip during the commute hours is more likely to be from a subscriber than not. With this information, we say that during weekdays and commute hours, there demand will be at a consistent level due to the subscribers tending to be the most frequent users.


## Key Insights for Presentation  

* The Bike sharing system is used by two main categories of users: Subscribers and Customers.
* The average ride duration for both user types is about 10 minutes.
* The average ride distance travel for both users 1500 meters.
* Subscriber users tend to use the bike sharing system on work days Monday to Friday,especially during commute hours in the morning and afternoon.
* Customer users tend to use the bike sharing system outside commute hours.
* The user behaviour of the Bike sharing system can be used to divide the users in different segments like: workers, students, tourists.
  
