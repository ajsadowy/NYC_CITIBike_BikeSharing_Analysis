# NYC_CITIBike_BikeSharing_Analysis   
   
# Can CITIBike Sharing Operation in NYC work for Des Moines?   
   
## Overview   
The goal for this analysis is to provide visual representation of data for NYC Bike Sharing program 
in the hopes of convince potential investors to back a new bike sharing program in Des Moines. To create 
the visualizations, we utilized data provided by [Citi Bike System Data](https://s3.amazonaws.com/tripdata/index.html), 
revised the data to a new csv file with JupyterNotebook, and created the visuals with Tableau.   

### Public Tableau Link
[NYC CitiBike Challenge](https://public.tableau.com/views/NYCBikeShareChallenge201908DataFile/CheckoutTimesforUsers?:language=en-US&:display_count=n&:origin=viz_share_link)   

## Data Visuals   
### User Checkout Times   
![Pic](https://github.com/ajsadowy/NYC_CITIBike_BikeSharing_Analysis/blob/main/IMAGES/Checkout%20Times%20for%20Users.png)   
Here we see almost all trips are less than 60 minutes with most trips being around 10 minutes.   
### Checkout Times based on Gender   
![Pic](https://github.com/ajsadowy/NYC_CITIBike_BikeSharing_Analysis/blob/main/IMAGES/Checkout%20Times%20by%20Gender.png)   
Here we see with further investigations that most riders are male.   
### Trips on Weekdays on Each Hour   
![Pic](https://github.com/ajsadowy/NYC_CITIBike_BikeSharing_Analysis/blob/main/IMAGES/Trips%20by%20Weekday%20per%20Hour.png)   
Most rides occur during the weekdays and at prime commute hours of the 9 to 5 work/school hours.   
### Trips on Weekdays on Each Hour (Seperated by Gender)   
![Pic](https://github.com/ajsadowy/NYC_CITIBike_BikeSharing_Analysis/blob/main/IMAGES/Trips%20by%20Gender%20(Weekday%20per%20Hour).png)  
Again showing mostly men use the service and the usage occurs on the weekdays at prime commuting hours of the day.   
### Trips On Weekdays (Seperated by Gender and Usertype)   
![Pic](https://github.com/ajsadowy/NYC_CITIBike_BikeSharing_Analysis/blob/main/IMAGES/User%20Trips%20by%20Gender%20by%20Weekday.png)   
Here we see thatnon subscribers to the Bike Sharing program use the program than nonsubscribed customers. This may show that subscribers see the benefits of using the program and subscribing for their frequent trips.  
### Top End Point Locations   
![Pic](https://github.com/ajsadowy/NYC_CITIBike_BikeSharing_Analysis/blob/main/IMAGES/Top%20Ending%20Locations.png)   
Seeing most endpoints of trips being near business centers of midtown, this adds further evidence of our theory most people use the bike sharing program to commute.   

## Summary   
Conclusions:   
* Most trips were around 10 minutes long.   
* Most trips are probably for commuting to work.   
* Mostly men and subscribed customers use the service.   
   
If the same strategy is to be used in Des Moines, IA then focusing on providing an alternative method of commuting would be a great start in building up subscribers. This market of riders is probably the same in most cities. If a soft start to the project can be started we can compare that initial data to see if the trends for the city match without risking a large initial investment capital.   
   
The additional data that would be best to look into is geographical information. Specifically using an elevation map of the two cities might useful to see if the two cities are comparable. NYC mostly know for its flat and gridlike roads might make biking an easy and therefore preferable method of transportation.   
   
Another bit of information that would be useful is year round data that can show how seasonal conditions may affect the rider usage and make accurate predictions.
