# Bikesharing Analysis: 

An analysis of NYC CitiBike bikesharing data from August 2019, using Tableau

[Link to Dashboard](https://public.tableau.com/app/profile/molly.dorman/viz/NYCCitiBikeAnalysisChallnge14/Story1 "link to dashboard")

- - - -

## Analysis Overview

For this challenge, we worked with Tableau’s data visualization software in order to build a business proposal for a bike-sharing company. The purpose of the proposal is to convince investors that a new bike-sharing program in Des Moines would be a successful business venture.

We learned how to import, style, and portray data accurately. Then, we created worksheets, dashboards, and stories to visualize key data from a New York Citi Bike dataset, as a point of comparison for what a bike sharing program in a new location could look like. 

- - - - 
## Results

### Customer Overview

#### Type and Gender of Customers

The vast majority of customers are subscribers, which suggests they may be local riders who use the bikes for regular commuting or transportation. 

The majority of riders are also males, which highlights an opportunity to understand how CitiBike can target more advertising towards female clients. 

![Type + Gender of Customer](https://user-images.githubusercontent.com/103781847/180619816-71f3d5c5-c212-48da-9723-f98cad161f4e.png)

#### Number of Trips by Gender

Subscribed males make up the majority of rides taken and Thursdays are the most popular days for those riders. 

![Trips by Gender](https://user-images.githubusercontent.com/103781847/180619823-46c8ae17-cd12-45f5-a621-a7b93f5f72b8.png)

### Trip Duration/Checkout Times

#### Checkout Times

Most rides are short, with 6 minute rides being the most frequent. Ride duration starts to really flatten out around the 20 minute mark, with few rides lasting longer than that.

![Checkout Times](https://user-images.githubusercontent.com/103781847/180619851-cc53328b-5e15-4801-8971-1799ef97f9a7.png)

#### Checkout Times by Gender

Checkout times by gender closely mirror overall checkout times, with female clients riding slightly longer than male clients. 

![Checkout Times by Gender](https://user-images.githubusercontent.com/103781847/180619858-2bfd2813-3ad3-4d2c-b984-886fa1005c29.png)

### Usage Heatmaps

#### Trips by Weekday and Hour

Weekday riding is most popular between 7-9am and 5-7pm, suggesting that the service is popular amongst commuters, while riding is more evenly distributed throughout the day on weekends. 

![Trips by Day + Hour](https://user-images.githubusercontent.com/103781847/180619865-abe875e4-b3c3-43c7-a4b2-1457a3913a23.png)

#### Trips by Weekday and Hour, Segmented by Gender

When we segment the heatmaps by gender, the patterns closely follow the overall busy and slow hours as a whole. There are no discernable patterns by gender, other than women making up a much smaller proportion of rides than men.

![Trip Heatmaps by Gender](https://user-images.githubusercontent.com/103781847/180619873-53220bde-75b5-4e26-b4f4-3d8484891d05.png)

### Top Starting and Ending Locations

The top starting and ending locations are heavily concentrated in Manhattan, which makes sense as this is an area many commute to for work. It also has a high population density and presumably less parking than when you travel further outside the city, so a bikeshare program would be a preferable option to driving in heavy traffic. 

![Top Starting + Ending Locations](https://user-images.githubusercontent.com/103781847/180619905-fd641154-a701-4530-9a84-76d226c44eff.png)

- - - - 

## Summary

The highlevel takeaways from this data are as follows:
1. Males overwhelmingly make up the majority of users, as do subscribed users.
2. Most trips are quick, lasting 30 minutes or less.
3. Mornings and evenings are popular times for bike usage, across both male and female riders.
4. Usage is most popular in the city center (Manhattan in this case).

Suggested additional visuals:
1. Look at the total number of rides for each month of the year to track seasonal trends.
2. Segment the number of rides by rider type more specifically (ie: tourist vs commuter/local riders). This would require pulling additional data about the riders. 

- - - -

### Tools, Languages + Data Used

#### Tools/Languages: 

1. Tableau Public
2. Jupyter Notebook
3. Pandas

#### Data:

* "201908-citibike-tripdata.csv.zip" from "https://s3.amazonaws.com/tripdata/index.html" 

- - - -
