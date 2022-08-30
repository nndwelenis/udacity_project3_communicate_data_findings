# Communicate Data Findings
## by Nndweleni Sundani


## Dataset

This dataset contains information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset includes 183412 observations, and 12 features for February 2019 only. FordGoBike is a bikeshare system which allows users to use bikes available throughought the FordGoBike stations. The bikes are available for use at any time of the day or night everyday. Users can choose to be a subscriber (member) or they can just be a customer for a particular ride. The dataset received needed some pleliminary wrangling before i could proceed to perform some useful visualizations which aims to answers the key questions for this project. Pleliminary data wrangling included the removal of null values, modification of incorrect data types, creation of new columns (member_age, age_group, start_dayofweek, trip_start_hour, and trip_start_hour).


## Summary of Findings

The main variable of interest was the duration of rides. Therefore the rest of my exploration was centered around finding and analysing factors that have an effect on the trips durations. I started exploring my data looking at the frequency of each variable in isolation, and this provided useful insight whereby i was able to see the contribution made by each variable. I plotted the distribution of duration of rides on a log-scale and it resulted in a graph which resembles a normal distribution with a peak number of riders riding for durations between 8 minutes and 11 minutes, and very few riders riding for just above 30 minutes. 

While exploring my data further (comparing variables in pairs), what stood out for me was the fact that the two User types had significant differences when it comes to the duration of trips. I observed that Customers users tend to ride for longer durations. The trip start hour and the trip days of the week were other variables which indicated some relationship with the trip durations and this was also investigated further along with the main variable of interest.

I went further, and compared three variables at the same time in order to look deeper and verify the relationships that exists which relates to the duration of trips. I verified that Customers do actually spend more time riding a bike than Subscribers in the whole week (reaching a peak on weekends). Having plotted a point-plot graph, i was able to verify that, on average customers have a longer trip duration than Subscribers, and it further showed that their trip duration significantly improved from the morning and reaches its peak in the afternoon (13:00), while the average duration of subscribers tend to stay constant for the most part of the day. The majority of Customers are likely to be tourists or occasional users and therefore would not nesessarily need to subscribe to the service. 
 

## Key Insights for Presentation

For the presentation, i focus on the influence that user type has on the trip duration and also include other related/important variables such as trip start hour, and days of the week. 