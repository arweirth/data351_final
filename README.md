# DATA 351 FINAL PROJECT
## Alex Weirth, Meelad Doroodchi, Charlie Weibe

Included is the SQL file for the creation of our data base "SQL_code" alongside data_dictionary.png which is an image for our draw SQL of the database.

Analysis Queries:

Labled in our SQL_code file are the queries for our analysis question of "Are GDP and population related to a country’s performance in the Olympics?"

1. Query #1 gives a table of countries occurences of earning a medal in 2014 alongside their gdp and population for 2014 which we then visualized in R by using a scatterplot where each point is the occurence of a medal win with the respective countries gdp on the y axis and population on the x axis. A linear regression line was also fitted

2. Query #2 creates 3 temporary tables of medal occurences for each income category and then joins them together so we have a frequency table of counts of each type of medal for each income category. These were then visualized as a barchart in python with mathplotlib, the resulting graph is titled medal_dist.png
