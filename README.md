## Overview

In this project, we'll look at purchasing data for clients of a wholesale distributor and attempt to use purchasing behavior to identify a way to predict what group each client belongs to. The characteristics of the grouping is unknown, we simply want to see if we can put similar observations (in this case, clients) into the same group. We'll then compare these predicted groupings to the true channels (High Value, Mid Value, Low Value) each client belongs to.

Many companies today collect vast amounts of data on customers and clientele, and have a strong desire to understand the meaningful relationships hidden in their customer base. 

## Data

This dataset contains a supermarket data in Turkish Language. There are more than 600.000 sales rows, contains
52.000+ unique Turkish customername,gender,age,birthdate etc.
9.000+ Categorized and subcategorized items with category1,category2,category3,category4
81 Stores
1200+ Salesman
Geographic location information (Latitude, longitude)
The data contains 3 month sales.

All the data was artificial. Sales created randomly according to population of the cities. Also all customernames are artificial too.

data = https://www.kaggle.com/omercolakoglu/turkish-market-sales-dataset-with-9000items

## Techniques

For this project we'll attempt to predict which client  we've segmented Life Time Value the data using clustering techniques.
