# Bikesharing

## Overview of the statistical analysis
Our client is interested in starting a bike sharing company in Des Moines, similar to Citibike in New York City. In order to convince investors that the program would work, an analysis was conducted with data from August 2019 in New York City based off the current Citibike ride-share company.

[link to dashboard](https://public.tableau.com/app/profile/mark2407/viz/Mod14CitibikeChallenge/NYCCitibikeChallenge?publish=yes "link to dashboard")

## Data and Software
Data:
Citibike Data: https://ride.citibikenyc.com/system-data (Data from August 2019 was used)

Software:
Tableau, Python, and Pandas

## Results

### Deliverable 1- Convert Tripduration to a Datetime Format
The data gathered from Citibike originally had the trip duration column in an integer format. In order for our data to be used and displayed correctly, I used Python and Pandas functions to convert the datetime format from an integer to a datetime datatype. After successfully converting the data, the entire dataframe was converted into a CSV and uploaded into Tableau for further analysis.

### Deliverable 2- Create Visualizations and Explanations for Data

### Top Starting Locations

I started with a map of the top starting locations for Citibike riders in New York. I felt like this gives a good initial point to the viewer to see that a majority of the starting locations are concentrated to mid and lower Manahattan.

<img width="1276" alt="Top starting locations" src="https://user-images.githubusercontent.com/103767830/190680860-c0ede6d8-a95f-4fda-a457-fd18b07def4f.png">

### Top Ending Locations

To compare the top starting locations with the top ending locations, I added the top ending locations map next. This shows that, a lot like the top starting locations, the top ending locations are nearby, indicating that most riders are taking short trips.

<img width="1276" alt="Top ending locations" src="https://user-images.githubusercontent.com/103767830/190680887-79c81769-e886-4b47-a8cd-0747375e70c0.png">

### Checkout Times for Users

The next slide in my story is the line graph of total riders and their trip duration. This line graph clearly indicates that all rides are relatively short, with a majority of them lasting about 30 minutes or less.

<img width="1273" alt="Checkout times for users" src="https://user-images.githubusercontent.com/103767830/190680952-5a3e4c41-80f4-41fc-b157-82d63815d0cd.png">

### Trips by Weekday per Hour

I used a heatmap next that shows the hours of the week where ridership is highest and lowest. This heatmap makes it easy to see that ridership is highest during the weekday morning and evening rush hours. It also shows that ridership is consistently high during the daytime hours of the weekend. Ridership is lowest during all nighttime hours.

<img width="1276" alt="Trips by Weekday per Hour" src="https://user-images.githubusercontent.com/103767830/190681001-498f36db-44c7-45e9-a4df-f1ed320b90b6.png">

### User Trips by Gender by Weekday

The next heatmap compares Customer ridership to Subscriber ridership based on gender and days of the week. This clearly shows that Customer ridership is low for all genders and days. In the Subscribers category, male subscribers are the top users out of all genders with rideship peaking on Thursday and Friday.

<img width="1276" alt="User Trips by Gender by Weekday" src="https://user-images.githubusercontent.com/103767830/190681028-c609b636-b4d6-427c-9149-d8bcdb873a4a.png">

### Trips by Gender (Weekday per Hour)

The next heatmap compares female, male, and unknown gender rideship to hours of the week. Again, male riders prove to be top demographic of all users, correlating with peak hours.

<img width="1276" alt="Trips by Gender (Weekday per Hour)" src="https://user-images.githubusercontent.com/103767830/190681048-542d9d2f-cbca-4084-ad53-40c3318a8753.png">

### Checkout Times for Genders

And finally, when looking at trip durations by gender, males make the most. But males and females both take close to the same duration of trips, around 30 minutes or less.

<img width="1273" alt="Checkout times for genders" src="https://user-images.githubusercontent.com/103767830/190681074-882f164e-ab47-4f53-9bf3-a54adf961e2a.png">

