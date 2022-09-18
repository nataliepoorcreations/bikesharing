# bikesharing

# Overview

For this analysis, I used Pandas to change the "tripduration" column from an integer to a datetime datatype. Then, using the converted datatype, I created a set of visualizations to:

* Show the length of time that bikes are checked out for all riders and genders
* Show the number of bike trips for all riders and genders for each hour of each day of the week
* Show the number of bike trips for each type of user and gender for each day of the week.


# Results

## Deliverable 1: Change Trip Duration to a Datetime Format
Using Python and Pandas functions, I converted the "tripduration" column from an integer to a datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After I converted the "tripduration" column to a datetime dataytpe, I exported the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.


<img width="997" alt="converted vallue in tripduration" src="https://user-images.githubusercontent.com/106033535/190920925-96afad35-4ae0-4992-b648-5fcb2accc933.png">


<img width="370" alt="Screen Shot 2022-09-18 at 1 38 20 PM" src="https://user-images.githubusercontent.com/106033535/190920932-9243a8dc-be05-432d-8844-b3a3a218068f.png">



## Deliverable 2: Create Visualizations for the Trip Analysis 
Using Tableau, create visualizations that show:
* How long bikes are checked out for all riders and genders.
* How many trips are taken by the hour for each day of the week, for all riders and genders.
* A breakdown of what days of the week a user might be more likely to check out a bike, by type of user and gender.



* Checkout Times for Users Viz
In this visualization, I graphed the length of time that bikes are checked out for all riders.

<img width="1037" alt="Checkout Times for Users" src="https://user-images.githubusercontent.com/106033535/190921014-258e45d3-eda4-448b-8f0a-fd0402a905e5.png">



* Checkout Times by Gender Viz
In this visualization, I graphed the length of time that bikes are checked out for each gender.

<img width="1064" alt="Checkout Times by Gender" src="https://user-images.githubusercontent.com/106033535/190921039-3342f232-9222-4aaf-abfa-ca660834d9ef.png">



* Trips by Weekday for Each Hour Viz
In this visualization, I graphed the number of bike trips by weekday for each hour of the day as a heatmap.

<img width="551" alt="Trips by Weekday for Each Hour" src="https://user-images.githubusercontent.com/106033535/190921062-2a619d17-0173-4a31-9cf0-ebaa10072263.png">



* Trips by Gender (Weekday per Hour) Viz
In this visualization, I graphed the number of bike trips by gender for each hour of each day of the week as a heatmap.

<img width="1222" alt="Trips by Gender (Weekday per Hour)" src="https://user-images.githubusercontent.com/106033535/190921082-ba84434b-5f29-44f6-ae7e-7099e4341799.png">



* User Trips by Gender by Weekday Viz
In this visualization, I created a heatmap that shows the number of bike trips broken down by gender for each day of the week by each Usertype.

<img width="1034" alt="Trips by Gender by Weekday" src="https://user-images.githubusercontent.com/106033535/190921148-fcbcb6b2-a095-4802-b65f-056989cbd309.png">


* Top Starting Location
In this visualization, we have a map where the bikes operate which shows the top starting locations of the bike trips. This map helps figure out which areas require more bikes and how much more depepding on different neighborhoods and the type of location.

<img width="956" alt="Top Starting Location" src="https://user-images.githubusercontent.com/106033535/190921592-4bcf30a8-3708-4289-8ee4-70c71ade8cc4.png">



* Average Trip Duration by Gender
In this visualization, I created a graph so show average trip duration based on gender. 

<img width="956" alt="Average Trip Duration by Gender" src="https://user-images.githubusercontent.com/106033535/190921618-54d02979-21e2-4ff9-a524-e3bb9d4b057b.png">



## Deliverable 3: Create a Story and Report for the Final Presentation
For this part of the Challenge, I created a story in Tableau and wrote a report that describes the key outcomes of the NYC Citibike analysis I did in the module and in Deliverable 2.

Please follow the link to find the The Tableau story created for this analysis: [link to dashboard](https://public.tableau.com/views/BikeSharingProject_16633819493280/BikeSharingStory?:language=en-US&:display_count=n&:origin=viz_share_link)

# Summary
The overall story highlights many important considerations for the potential bike-sharing program in NYC. Some of the highlights are listed below:

* We can see from the checkout times graph that most bikes are checked out during early hours of the day and most customers are female. Heatmap also supports this point by showing the usage of female bikers.
* We can see from the usertype by gender heatmap that most bike users are female subscribers.
* The average trip duration graphs shows that younger people are using bikes for longer periods of time.
* The final story point with the top starting locations give a good idea about what types of locations needs more bikes. Commercial areas and areas where the tourist traffic is higher needs significantly more bikes than residential areas.

Two additional visualizations that I would perform with the given dataset:

* A visualization that shows the total number of rides each bike has accumulated could be a useful tool to determine which ones are due for maintenance.
* Addind a top ending locations graph could help determine whether the bikes are going to be displaced too far from the starting locations creating scarcity at different starting locations.
