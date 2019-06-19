# Udacity_Ford_Gobike_Visualization
Ford GoBike is the Bay Area's bike share system. Bay Area Bike Share was introduced in 2013 as a pilot program for the region, with 700 bikes and 70 stations across San Francisco and San Jose. Once expansion is complete, Ford GoBike will grow to 7,000 bikes across San Francisco, the East Bay and San Jose. 

Dataset: https://s3.amazonaws.com/fordgobike-data/index.html


## Preliminary Exploratory & Wrangling 
In this section, we perform the preliminary data wrangling to create new columns and filter the dataset based on the correct and valid value. We add the age, area and duration trip in minutes column as well as filter the dataset according to the value of these three newly created columns. 

After that, we perform univariate, bivariate and multivariate Exploratory Analysis for the dataset with these variables below: 
1. Area  
2. User type  
3. Start Hours 
4. Start Year Months 
5. Start Weekdays
6. Trip Duration

## Explanatory Analysis
After filtering the data based on the area, trip duration and the age as well as performing the Exploratory Data Analysis, we will answer the following questions based on our new dataset of the Ford Go Bike Ride, we intended to answer the following big questions:  

1. Which timing of the following rides is busiest during the days, months and hours? 
2. How does the duration trip trend look like? 
3. Is there any particular effect of the operational area? 
4. Whether subscriber have different trend than normal customer from 2017-2018? 

## Conclusion 
After filtering the data of the Ford Go Bike ride from 2017-2018 and answering the questions, we find out that the primary usage of the Ford Go Bike is the go-to-work transportation which is proven by the weekdays usage is higher than weekend usage individually and the most crowded hours are 8am and 5pm (going to work and going home time). The usage downtrend of December 2017 and 2018 also might be caused by the holiday season which reduced the number of worker going to work. From the number of subscriber, we can also indicate that many who rides the bike daily are workers. This can be proven by the fact which the subscriber ride is heavily leaned toward working days rather than weekends as well as the fact that subscriber busy hours are 8am and 5pm which fit the profile for worker profile. 

For people who wanted to know the crowdest moment so they can rent a bike successfully, they can avoid the weekdays 8am and 5pm as well as renting it during holidays month like December. For the operational areas, San Fransisco is the one with the most ride while both East Bay and San Jose are less crowded (though might still be better to avoid 8am and 5pm weekdays in both areas as well as 6pm in East Bay weekdays) 
