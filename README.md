# PyBer Analysis

## Overview
The purpose of the new analysis is to use my Python skills and knowledge of Pandas to create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, to create a multiple-line graph that shows the total weekly fares for each city type. This analysis will allow PyBer stakeholders to make good business decisions because it will provide them with more detailed information on the ride-sharing company. Data is the lifeblood of a company so the more data, the better. 

## Results 

### PyBer Summary 
<img width="636" alt="Screen Shot 2022-04-24 at 11 43 39 AM" src="https://user-images.githubusercontent.com/95447175/164991546-47728256-385b-457f-8058-ff45ded18f6d.png">

#### Urban Cities
Urban cities have the highest Total Rides, Total Drivers and Total Fares, which is to be expected, as a lot of people use ride-sharing companies in big cities such as San Francisco and New York. However, it is a bit surprising to find that the Average Fare per Ride and Average Fare per Driver are the lowest in Urban cities. This is probably due to smaller distances driven per ride. 

#### Suburban Cities 
Suburban cities have about 40% of the total rides of Urban Cities, and only 20% of the drivers compared to Urban cities. The Average Fare per Ride is almost $7 higher and the Average Fare per Driver is about $23 higher. I can see how this makes sense because I have taken a ride-share in Suburban cities and it was significantly more expensive than taking a ride in an urban city. 

#### Rural Cities 
  Rural cities have the least amount of Total Rides, Total Drivers and Total Fares, while having the highest Average Fare per Ride and Average Fare per driver. This makes sense because there are longer distances to drive and fewer drivers available in Rural cities. 

### January-April Fare per Week
<img width="1282" alt="Screen Shot 2022-04-24 at 11 46 37 AM" src="https://user-images.githubusercontent.com/95447175/164991674-b4a7ec0b-35f3-4358-b867-e869c67f3cd8.png">
Over the course of this time series, one can see that Total Fares are highest for Rural cities, and the Surban cities are almost in between Urban and Rural cities in terms of the Fares. 

- Between January and February, total Fares increase by about 500 for both Urban and Suburban cities, while increasing very slightly for Rural cities
- Between February and March, there is a notable spike at the end of February for all cities
- Between March and April, there are a couple of ups and downs for Urban cities, while Suburban and Rural cities stay relatively flat 

## Business Recommendations
My three business recommendations to the the CEO of PyBer for addressing any disparities among the city types are as follows:
1. Look into what is causing the uprick in Total Fares in the month of January for Urban and Suburban cities, and see whether it's possible to get a bigger increase in Rural fares as well. 
2. Look into what causes a significant uptick in Fares for all cities at the end of February, there may be special events happening across the country so it could make sense to hire more drivers in anticipation, to make sure that there are enough drivers for the requested rides. 
3. Look into what is causing a slowdown from March to April, when all the city types experience a dip in Total Fares. It could make sense to run a promotion campaign to get more people to take more rides. 
