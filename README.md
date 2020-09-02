# **Dataset**

[Provided URL](https://s3.amazonaws.com/baywheels-data/index.html)


# **Ford GoBike Trip Data Analysis**

In this part of project, our goal is to conduct an exploratory data analysis on Ford GoBike Trip dataset. We will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part is structured, going from simple univariate relationships up through multivariate relationships, but it does not need to be clean or perfect. This part of the project is gives opportunity to ask questions on data and make discoveries.

 The original Bay Wheels's trip dataset contains 176799 rides and 14 features.

 - Trip Duration (in seconds)
 - Start Time and Date
 - End Time and Date
 - Start Station ID
 - Start Station Name
 - Start Station Latitude
 - Start Station Longitude
 - End Station ID
 - End Station Name
 - End Station Latitude
 - End Station Longitude
 - Bike ID
 - User Type
 - rental_access_method
 
 # **Summary of Findings**
 
 - I have changed the data type of start_time, end_time to Datetime. Because it is good for plotting and proper structure of data.
- Apparently, the customers are more willing to take long trips than subscribers.
- Besides, if you look at the rental accessing method deeper, you will realize that people who use the app take long trips than a clipper. 
- Customers use the app more often than clippers. Subscribers use the app and clipper very often and trip duration is also the same. 
- Interestingly subscribers take bikes not quite often. Whereas customers take bikes very often and trip duration is also very long

