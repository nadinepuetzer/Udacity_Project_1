# Udacity_Project_1
# Writing a Data Scientist Blog Post
Follow the link to my blog post here: https://medium.com/@nadine.puetzer1/did-you-know-the-best-time-to-visit-seattle-6feaf6809446

## My Motivation
I'm planning a trip to seattle but I have no preferred season or appartment yet. With the help of the open source data set from AirBnB I want to understand, in which season most people visit Seattle. Secondly, I want to book a cheep house, that costs at least 50$ per night and is available for 13 consecutive nights.

## My Questions
1) Do people favour specific seasons?  
2) Which season is cheepest?
3) Which of that cheep houses are available for 2 weeks at least?

## My selected data set
Seattle Airbnb Open Data (https://www.kaggle.com/datasets/airbnb/seattle?resource=download&select=calendar.csv)

The following Airbnb activity is included in this Seattle dataset:

Listings, including full descriptions and average review score
Reviews, including unique id for each reviewer and detailed comments
Calendar, including listing id and the price and availability for that day

# Overview about used libraries and files in this repo
- data: folder which includes the .csv files calendar.csv, listings.csv, reviews.csv
- Seattle_Airbnb.ipynb: Jupyther Notebook to 
    1) Prepare data (Gathering necessary data to answer my questions, handling categorical and missing data, providing insight into the methods I chose and why I chose them)
    2) Analyze, Model, and Visualize (Providing a clear connection between my business questions and how the data answers them)

## Result summary
As a result I got a list of 218 houses, that I can visit in the most favoured season, in winter, for a price less than 50$ per night and are available for at least 13 consecutive nights.

## Acknowledgments
This dataset is part of Airbnb Inside, and the original source can be found here: http://insideairbnb.com/get-the-data/ .
