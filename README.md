# Big-Data-Analytics-Project
BDDA Project

# Project 1 - Big Data & Data Analytics Project on Airlines Delay Dataset using Python

By Dhruv Khosla,Yogesh Sachdeva and Akhil Sharma 

# Objectives of the Project:
1. Exploration & Visualizion the data
2. To examine if data has any structure
3. To do the Feature Engineering of data
4. To create the Data Pipelining
5. Perform the Hyperparameter tuning

# About Dataset
The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics (BTS) tracks the on-time performance of domestic flights operated by large air carriers. Summary information on the number of on-time, delayed, canceled and diverted flights appears in DOT's monthly Air Travel Consumer Report, published about 30 days after the month's end, as well as in summary tables posted on this website. BTS began collecting details on the causes of flight delays in June 2003. Summary statistics and raw data are made available to the public at the time the Air Travel Consumer Report is released.

# This dataset is composed by the following variables:
Year 2008
Month 1-12
DayofMonth 1-31
DayOfWeek 1 (Monday) - 7 (Sunday)
DepTime actual departure time (local, hhmm)
CRSDepTime scheduled departure time (local, hhmm)
ArrTime actual arrival time (local, hhmm)
CRSArrTime scheduled arrival time (local, hhmm)
UniqueCarrier unique carrier code
FlightNum flight number
TailNum plane tail number: aircraft registration, unique aircraft identifier
ActualElapsedTime in minutes
CRSElapsedTime in minutes
AirTime in minutes
ArrDelay arrival delay, in minutes: A flight is counted as "on time" if it operated less than 15 minutes later the scheduled time shown in the carriers' Computerized Reservations Systems (CRS).
DepDelay departure delay, in minutes
Origin origin IATA airport code
Dest destination IATA airport code
Distance in miles
TaxiIn taxi in time, in minutes
TaxiOut taxi out time in minutes
Cancelled *was the flight cancelled
CancellationCode reason for cancellation (A = carrier, B = weather, C = NAS, D = security)
Diverted 1 = yes, 0 = no
CarrierDelay in minutes: Carrier delay is within the control of the air carrier. Examples of occurrences that may determine carrier delay are: aircraft cleaning, aircraft damage, awaiting the arrival of connecting passengers or crew, baggage, bird strike, cargo loading, catering, computer, outage-carrier equipment, crew legality (pilot or attendant rest), damage by hazardous goods, engineering inspection, fueling, handling disabled passengers, late crew, lavatory servicing, maintenance, oversales, potable water servicing, removal of unruly passenger, slow boarding or seating, stowing carry-on baggage, weight and balance delays.
WeatherDelay in minutes: Weather delay is caused by extreme or hazardous weather conditions that are forecasted or manifest themselves on point of departure, enroute, or on point of arrival.
NASDelay in minutes: Delay that is within the control of the National Airspace System (NAS) may include: non-extreme weather conditions, airport operations, heavy traffic volume, air traffic control, etc.
SecurityDelay in minutes: Security delay is caused by evacuation of a terminal or concourse, re-boarding of aircraft because of security breach, inoperative screening equipment and/or long lines in excess of 29 minutes at screening areas.
LateAircraftDelay in minutes: Arrival delay at an airport due to the late arrival of the same aircraft at a previous airport. The ripple effect of an earlier delay at downstream airports is referred to as delay propagation.
Project - 2 : Big Data & Data Analytics Project on Avocado Price Prediction
By Yogesh Sachdeva, Akhil Sharma and Dhruv Khosla

# Introduction
In this project we tried to explore and visualize the historical data of Avocado Prices dataset using python to test and train our machine leanring model.

# Objectives of the Project:
1. Exploration & Visualizion the data
2. To examine if data has any structure
3. To do the Feature Engineering of data
4. To create the Data Pipelining
5. Perform the Hyperparameter tuning

# About Dataset
In this study, we tried to see if we can predict the Avocado’s Average Price based on different features. The features are different (Total Bags,Date,Type,Year,Region…).

The variables of the dataset are the following: Categorical: ‘region’,’type’ Date: ‘Date’ Numerical:’Total Volume’, ‘4046’, ‘4225’, ‘4770’, ‘Total Bags’, ‘Small Bags’,’Large Bags’,’XLarge Bags’,’Year’ Target:‘AveragePrice’.

This dataset is composed by the following variables:
Data Loading and Description This data was downloaded and provided by INSAID, from the Hass Avocado Board website in May of 2018 & compiled into a single CSV.

Represents weekly 2018 retail scan data for National retail volume (units) and price.

The dataset comprises of 18249 observations of 14 columns. Below is a table showing names of all the columns and their description.

The unclear numerical variables terminology is explained in the next section:

Features Description ‘Unamed: 0’ Its just a useless index feature that will be removed later ‘Total Volume’ Total sales volume of avocados ‘4046’ Total sales volume of Small/Medium Hass Avocado ‘4225’ Total sales volume of Large Hass Avocado ‘4770’ Total sales volume of Extra Large Hass Avocado ‘Total Bags’ Total number of Bags sold ‘Small Bags’ Total number of Small Bags sold ‘Large Bags’ Total number of Large Bags sold ‘XLarge Bags’ Total number of XLarge Bags sold
