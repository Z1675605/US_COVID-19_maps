# US_COVID-19_maps
### GEOG 458 Lab 3 Maps

In this lab I create two thematic maps which map COVID-19 within the United States. My first map is a choropleth map that gathers the rate of infection per thousand by county, my second map is a dot density map which gathers the numbers of cases per each county. Each map has an interacive feature that engages the user to spend more time learning about COVID statistics.

## Map 1: [United States COVID-19 Rates per County](https://z1675605.github.io/US_COVID-19_maps/map1.html)
![Map 1, choropleth map of the US COVID rates](/img/map1.JPG)

In this map I created a hover based interation where the user can hover over each county and learn the rate of cases per thousand. I decided to use a gradient that darkens as the number of cases rise which can be determined by looking at the legend for each category. The data used is from the [US CENSUS](https://data.census.gov/cedsci/table?g=0100000US%24050000&d=ACS%205-Year%20Estimates%20Data%20Profiles&tid=ACSDP5Y2018.DP05&hidePreview=true).

## Map 2: [United States COVID-19 Cases Tracker](https://z1675605.github.io/US_COVID-19_maps/map2.html)
![Map 2, dot density map of the US COVID cases](/img/map2.JPG)

In this map I created a click based interaction where the user can click on each dot to learn more about the cases and deaths per county. Each dot increases the intensity of the red color based on the amount of cases in the county, see the legend for exact details. The data used is from the [NY TIMES](https://github.com/nytimes/covid-19-data/blob/43d32dde2f87bd4dafbb7d23f5d9e878124018b8/live/us-counties.csv) github page.
