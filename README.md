# AirBnB Analysis

## Introduction:

Airbnb began in 2008 when two designers who had space to share hosted three travellers looking for a place to stay. Now, millions of Hosts and guests have created free Airbnb accounts to enjoy each other's unique view of the world.           From cozy cottages to elegant penthouses,Hosts are happy to share their places. Whether its a work trip, weekend getaway, family vacation, or a longer stay, there are millions of amazing places to visit.
On the business front, Airbnb for Work has everything needed to do your job on the road, from top-rated places and collaborative spaces to team-building Experiences and administrative tools that make managing travel easier than ever.

## Project Views:

This project aims to analyze Airbnb data using MongoDB Atlas, perform data cleaning and preparation, develop interactive geospatial visualizations, and create dynamic plots to gain insights into pricing variations,availability patterns, and location-based trends.
The dataset is available in MongoDB Atlas as sample_airbnb. Anyone can create the Atlas account and access this database collection for data explorations and visualizations.

## Technologies used:

Python scripting, MongoDB Atlas, Exporting CSV file, Handling large dataset, Data Preprocessing, Exploratory data analysis, Visualization using Plotly, Streamlit Web Application, Dashboard creation using PowerBI.

## Packages for import:

- import streamlit as st
- import pandas as pd
- import pymongo
- import plotly.express as px
- from collections import Counter
- import matplotlib.pyplot as plt
- import seaborn as sns
  
## Visualizations:

Explore visualizations created from this dataset using tools like Power BI and Streamlit.

### Power BI Visualizations:
- Card chart for displaying total properties, hosts, reviews.
- Map chart displaying Total properties available in each Country.
- Treemap showing rooms per properties.
- pie chart gives visuals about Price varies for room types.
- Line chart provides the Average price of property in each country.

### Streamlit Visualizations:

- Finding Outliers in Price variations (Box Plot Chart)
- Distribution of Property Types in Each Country (Stacked Bar Chart)
- Distribution of Cancellation Policies (Donut Chart)
- Number of Reviews vs. Average Review Scores (Bubble Chart)
- Map Visualization of Properties (Choropleth Map or Scatter Geo Map)
- Frequency of Amenities (Horizontal Bar Chart)

## Analysis and Findings:

- Based on the above analysis, the type of the property plays major role in accommodation. Mostly, people are tending to stay in Apartment and House due to various factors. Compare to other countries, Condominium stay rises in United States.
- As per the current data, Turkey holds the highest price of around 48k and Portugal having the minimum of 9 for accomodations.
- In all the countries, the people would prefer cancellation policies for accommodation bookings and it would be in moderate,flexible and even strict_14 days with grace period mode.
- BoxPlot chart helps to find the price variations and their outliers. In this dataset,the price varies  from minimum to maximun of 50k. Here, the maximum price lying in between of 0-20k but we can see one outlier which is present in the price of around 50k. So, this is the outlier in this particular dataset.
- Reviews and ratings are playing the important role in accommodation bookings.If the reviews and ratings are high, the bookings will be high.
- All over the world, people would expect some basic amenities while booking the room for stay. In Airbnb, most hotels, apartments provide basic amenities like kitchen, Wi-Fi, TV, dryer, Office setup, Parking, Elevators, Microwave, Fire Extinguisher etc.
- Increase in amenities would tend to increase in price also.

## Credits

The dataset was collected and made available in MongoDB Atlas as sample_airbnb. Thank you  Guvi team for this project.

### Thank you All!

