# Online-Food-Ordering
A data science project to determine the best location for the delivery workers of an online food ordering company.

*note: This is the capstone project of the "IBM Data Science Professional Certificate" on Coursera.*

## Business Problem
Used the Foursquare API and London data to cluster neighborhoods and determine the best location for the delivery workers of an online food ordering company.

## Background
Online food ordering is a system to order the restaurants' food through the website or mobile app. Based on the type of this system, a customer can choose a restaurant, scan the menu items, select the desired items and pay it. These websites give customers information about the food, price, duration of the food preparation and so on.

Based on the reports, the online food ordering market have significantly increased all over the world. For instance, 40 percent of Americans having ordered their food online at least once.

There are different types of online food ordering. One of the main ones is managed by online food delivery companies. In this method, these companies receive the costumer order on their website or mobile app and connect the costumer to the restaurant. After that the costumer ordered and payed the food, they can get the food in door. This is done with some delivery workers (normally with motorcycle or bicycle) who working for the online food delivery companies and are supposed to transfer the food from the restaurants to the costumer's house or office. Naturally, these delivery companies work with lots of restaurants.

What is seriously important for the delivery companies is that they should deliver the food as soon as possible, in order to reduce the delivery time, increase customer's satisfaction, and get more orders. Therefore, it is noticeably vital for these companies to arrange their delivery workers to save the time. To do so, the location of the delivery workers should be optimized in order to reduce the distance they have to drive each time.

The idea behind this project is to cluster the neighborhoods of the city (here London is chosen as the case study) to ensure that the workers have to drive less distance in each area. In this project, the data of the restaurants’ location and the population of each area of the city is required.

This project is useful for all the online food delivery companies who would like to increase their performance and profit.

## Data
To answer the business problem, the following data are extracted from the following sources:
* Population of Each Neighborhood
* Number of Restaurants in Each Neighborhood (Foursquare API)
* Coordinates of the Neighborhoods of London

Following data sources will be needed to extract/generate the required information:

* Population of each area will be obtained using **London Borough Profiles Database** (https://data.london.gov.uk/download/london-borough-profiles/c1693b82-68b1-44ee-beb2-3decf17dc1f8/london-borough-profiles.csv)

* Coordinate of London center will be obtained by **parsing the Wikipedia web page: List_of_London_boroughs** (https://en.wikipedia.org/wiki/List_of_London_boroughs)

* Number of restaurants and their type and location in every neighborhood will be obtained using **Foursquare API**


## File structure
1. Raw and modified data can be found in __data/__
2. Code in Jupyter Notebook can be found in __London.ipynb__
3. Final report can be found in __Report.pdf__
4. Presentation can be found in __Presentation.pdf__

