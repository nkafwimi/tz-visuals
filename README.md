# tz-visuals
Mapping out publicly available data for different sectors in Tanzania using d3 choropleth maps 

The template included here is in progress and uses gaming data around the world. It is built off using d3, javascript, html and css. 

## Technology (used on template: Q5)
- D3 Version 5 (included in the lib folder)
- Chrome v92.0 (or higher): the browser for grading your code
- Python http server (for local testing)

## Data

1. Each row in ratings-by-country.csv represents about a game's information for a country, in the form of <Game,Country,Number of Users,Average Rating>, where
- Game: the name of a game, e.g., Catan.
- Country: a country in the world, e.g., United States of America.
- Number of Users: the number of users who have rated Game who are from Country.
- Average Rating: the mean rating given to Game by users who are from Country.
This dataset has been preprocessed and filtered to include only those games that have been rated
by more than 1000 users in the world.

2. The world_countries.json file is a geoJSON, containing a single geometry collection: countries. You
can find examples of map generation using geoJSON here.

