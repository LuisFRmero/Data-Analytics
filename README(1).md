
# **Cyclistic membership growth analysis**

## **Business Task**

The objective of this analysis is to promote the planning and implementation of a new marketing strategy that focuses on converting casual users into annual members. To do so, it is necessary to analyse data and understand the different characteristics and trends between these types of users. A thorough data analysis exercise was performed, from which relevant insights and visualizations were obtained to provide actionable recommendations.

## **Sources**
All data was obtained from [Lyft Bikes and scooters](https://divvy-tripdata.s3.amazonaws.com/index.html) (divvy bicycle sharing service) daily user registries. Available dates range from 2013 to 2022. These registries can be used royalty-free thanks to a partnership between the City of Chicago and Bikeshare that limits its usage to most non-commercial purposes
All databases share the same structure, including: 

i.	Unique Id

ii.	Type of bike

iii.	Date for beginning and end of ride

iv.	Station id and name for beginning and end of ride

v.	Latitude and longitude of beginning and end of trip


## **Data cleaning**
Power BI was chosen for this analysis as it allows to efficiently combine multiple databases, process them and use them for compelling visualizations. 
The resulting combined database was analyzed and cleaned of errors and incoherent entries that could affect the overall analysis and integrity of results. The following steps broadly explain all processing steps done using Power BI:

i.	Rows with no **station name/id** for the beginning or the end of the trip were removed

ii.	**Total ride length** was obtained by subtracting **end date** and **start date** and converting that amount into minutes. Rows with results less than 1 minute and outliers were removed

## **Analysis**
In order to taggle the business task, the analysis was divided in two different steps. First, a general overview of the current situation of cyclistic. Then, an analysis of each type of user (members and casuals).

•	  The focus of each analysis is to find trends regarding each user type with the different data entries available in the provided registries. Analysis performed were: Total number of rides, total minutes spent in rides, average ride length, seasonality (months, quarters and days of the week), preferred bike type and most popular stations 

## **Key findings:**

•	Between April 2021 and April 2022, there were 4.8 million different rides that lasted on average 19.6 minutes and amounted to 95.1 million minutes. 

•	July is the month with the highest number of trips and contrary to most other months, casual users have the largest contribution to the total number of rides

•	The preferred months for using bike sharing services are June, July and August, which represent summer season. 

•	Clark St & Elm St, Clark St & Lincoln Ave, Kingsbury St & Kinzie St, Michigan Ave & Oak St and Millennium Park are the most used stations for starting and ending a trip


![Image](https://user-images.githubusercontent.com/110510456/182511237-90a54bae-dc2c-4475-885d-0c7929f59fc5.png)

•	Casual users prefer to rent bikes on the weekend (Friday, Saturday and Sunday) while members use them on the weekdays (Monday, Tuesday, Wednesday, Thursday)

•	Casual members take longer trips than members, but members account for the majority of trips (56%)

•	Even with a clear preference on which days of the week each type de user rent bikes, both casual users and members have the largest ride duration on the weekend

•	While both casual users and members prefer classic bikes, only casual users use docked bikes



![Image](https://user-images.githubusercontent.com/110510456/182511314-2c628d57-1312-4611-8a47-fac3f202fdd2.png)



![Image](https://user-images.githubusercontent.com/110510456/182511340-709db936-69e5-4df7-9890-f6294c5d3ba9.png)



![Image](https://user-images.githubusercontent.com/110510456/182511357-9a8df754-0e02-41da-9271-170ce0b60ab6.png)



![Image](https://user-images.githubusercontent.com/110510456/182511368-c852393a-0919-4e8d-a5f3-39695fa5516f.png)









## **Recommendations**

1. As casual riders use this service mostly on Friday, Saturday and Sunday, a new membership type should be created that provides special prices only for weekend rides

2. In order to make memerships more appealing to casual users, members should have reduced prices when traveling from or to the stations preferred by casual riders: Michigan Ave & Oak St, Millennium park, Shedd Aquarium, Streeter Dr & Grand Ave and Theater on the lake

3. Promotions should be given during months where casual riders use the service the most (summer) to incentivize acquiring a membership
