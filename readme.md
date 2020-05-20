# (Dataset Exploration Title)
## by (your name here)


## Dataset Ford GoBike

Ford GoBike is a publicly available dataset that will enable different folks with different skillsets to play around with. Data is downloaded from https://s3.amazonaws.com/fordgobike-data/index.html For the current analysis, 2018 data is downloaded Brief description about the data Each trip is anonymized and includes:

Trip Duration (seconds)
Start Time and Date
End Time and Date
Start Station ID
Start Station Name
Start Station Latitude
Start Station Longitude
End Station ID
End Station Name
End Station Latitude
End Station Longitude
Bike ID
User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)



## Summary of Findings

> Subscribers are more than the Customers
> The customers using App is more as compared to a clippper card
> 91.88% users does not share for trips
> Subscribers tend to take shorter rides than customers. Most subscriber rides are 10 minutes or less,
while the duration of customer rides tends to vary more i.e. has a wider spread.


## Key Insights for Presentation

>> When is the service often used? 
-> Mostly maximum number of rides were taken on Thursday and Friday and very less number of trips taken from Saturday and Sunday.
   As expected the rides duration increases and are relatively more on weekends.
>> What is the average ride across different cities? 
-> For Customers, the most popular cities are touristy areas such as San Francisco Ferry Building,Embarcadero at Sansome St , Powell St BART, etc.
   For Subscribers, the top stations are at San Francisco Caltrain (a major commute hub), Markey St at 10th
   and other "downtown" areas.
>> What is the average ride across month of the year?
-> It is clear from the the chart that the count of the bike rides sees an demand increase in the month of February, where the count gets gets decreased by    almost 40% in the month April-May from rest of the year

>> What is the average duration of each ride? 
-> 97% of all rides are less than 45min
   The distribution for ride duration is highly skewed to the right. When plotted on a log-scale, ride duration follows an approximately log-normal       distribution, with a median duration of 9 minutes and most rides taking between 3 and 30 minutes.
   97% of all rides last 45 minutes or less.
>> What are the characteristics of Customers vs. Subscribers? 
-> Subscribers tend to take more rides than customers. 
   Subscribers tend to take shorter rides than customers. Most subscriber rides are 10 minutes or less,
   while the duration of customer rides tends to vary more i.e. has a wider spread.
>> Which are the famous starting and destination station? 
-> Most popluar start station is Market Street 10 st. 
   Most popular end station is San Francisco Caltrain
>> What time of the day do users use this service?
-> Most of the start hour is usually from 8 and from 17

Whereas, Subscribers use the service less, but, rent it out for a much longer duration each trip
Customers tke more number of trips, but they rent it out for a shorter duration each trip
The service is used more during weekdays than weekends
Majority of Subscriber rides are taken on Tue and Web
Whereas customers rides on Friday is less A majority of the trips range between 0 and 30 min
The behaviour of subscribers in term of ride duration is almost constant throughout the year i.e. between 15 to 20 minutes.
Whereas the ride duration for each one time customer increases in the holiday seasons.