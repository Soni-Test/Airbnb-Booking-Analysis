# EDA on Airbnb Booking Analysis

<a href="https://colab.research.google.com/drive/1xNite-Zr_WbLYPwa5JtjlkbVUsQytfzT#scrollTo=71Y1DDDdLFnH" target="_parent"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Interactive Demo"/></a>

<p align="center">
   <img width="800" height="400" src="https://user-images.githubusercontent.com/107030716/223732096-03ec0c8b-4b35-4f1d-83d9-1a694627297f.png">
</p>



## Summary

Airbnb, Inc. is an American company that operates an online marketplace for lodging, primarily homestays for vacation rentals, and tourism activities. Based in San Francisco, California, the platform is accessible via website and mobile app. Airbnb does not own any of the listed properties; instead, it profits by receiving commission from each booking. The company was founded in 2008 by Brian Chesky, Nathan Blecharczyk, and Joe Gebbia. Airbnb is a shortened version of its original name, AirBedandBreakfast.com. Source: (https://en.wikipedia.org/wiki/Airbnb)

Since 2008, guests and hosts have used Airbnb to expand on traveling possibilities and present a more unique, personalized way of experiencing the world. Today, Airbnb became one of a kind service that is used and recognized by the whole world. Data analysis on millions of listings provided through Airbnb is a crucial factor for the company. These millions of listings generate a lot of data - data that can be analyzed and used for security, business decisions, understanding of customers' and providers' (hosts) behavior and performance on the platform, guiding marketing initiatives, implementation of innovative additional services and much more.



# Business Problem
- The objective of this capstone is to do EDA on the given dataset and find out the insights from it.
# Understanding the problem statement
- This is the most important part of any analysis as we must understand the needs of a customer/business owner for what task they require analysis on and work as per their requirements. The main motive was to analyze the given dataset to provide the company with the information that will help to analyze their business and take strategically important decisions to further grow their business to new heights.
# Know your Data
Dealing with a huge data set is a time-consuming part. In this dataset, we are provided with 16 features and around 49k data instances. To understand the dataset we are working on, initially, we find the important columns and the data using “head()” and “info()”. To minimize the workload and efforts we must have to distribute data and analyze the content first.
# Handling missing values
- Removing the unnecessary part while handling missing values and data cleaning. During the analysis, we found that there are four columns with null values. To minimize the errors, we replaced the numeric columns having null values with 0 using the “fillna()” function.
# Univariate and Multivariate analysis
- To find out the most frequently searched words, we first removed all the stop-words using the nltk dictionary and then using wordcloud we tried to display frequently searched words in an image view. Then we analyzed the hosts based on the number of properties owned by them and based on the area and Airbnb listings. Then we analyzed room types based on area, and the price of the room using price categorization as well.

- Based on the price categorization, we tried to find out the sentiment of the people across the different neighborhood groups, where we found that most of the people preferred affordable rooms over cheap and expensive in Manhattan and Brooklyn whereas, for the bookings in Queens and Bronx, the relation was reversed.
- We used longitude and latitude to demonstrate the geographical distribution of properties across the places.
- We tried to get the correlation between different variables for which we plotted a correlation plot as well. All the analysis was accompanied by graphical representation.
- We tried to plot a distribution plot for different neighborhood groups in terms of prices. This distribution and density of prices were in line with the predictions. Manhattan proved to be the costliest as compared to other groups. Moreover, it proved to be the place with the highest number of bookings. </br> 


# Conclusion
After the analysis, we concluded that this analysis will help the company to decide in which areas they are leading or lagging, where they need improvisation, and what necessary changes they need for better functionality of their business. As the analysis was done based on price category, different locations, hosts, and room types, the company will be able to decide which type of room is preferred in what area and strategize accordingly for the betterment of their customer satisfaction and business growth.


### Acknowledgements 

##### © Copyright 
![image](https://user-images.githubusercontent.com/107030716/198835325-f3e1f465-d56d-4af2-9847-75ec15f1c311.png)


