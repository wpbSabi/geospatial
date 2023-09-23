# 1 in 500 in the US have died from COVID, 1 in 1700 in the world have (as of September 18th, 2021)

These python-geopandas-choropleth maps tell the story, and the data tables are shared below.

Using geopandas in python, the following USA and world maps are colored by the deaths per population.

*Deaths as of September 2021 (Images by Author using Geopandas)*
*The repository has since been updated with data from November 6, 2021*

## Why did I make this chart Now?
For each person living in the US, 1 in 500 have now died of covid. I wanted to understand the differences of the death rate around the US and the world. When I couldn’t find this particular data readily available in exactly this way, I decided to share my findings.

And to reiterate, 1 in 500 people total have died. Not 1 in 500 *infected*. 1 in 500 of *all residents*.

## Data Sources overview

### US data sources

1 in 496 people have died from COVID as of September 18th, 2021 — 1/(668,442 deaths / 331,449,281 population)

* Covid deaths from John Hopkins — https://data.cdc.gov/Case-Surveillance/United-States-COVID-19-Cases-and-Deaths-by-State-o/9mfq-cb36 (filter on latest date by state)

* 2020 US Census for population — https://www.census.gov/data/tables/2020/dec/2020-apportionment-data.html

* Shapefile— https://gadm.org/download_country_v3.html

### World data sources

1 in 1670 people have died from COVID as of September 18, 2021 — (1/(4,666,334 deaths / 7,794,540,359 population))

* Covid deaths and population from WHO— https://covid19.who.int/table?tableChartType=heat (Data cleanup: Remove the extra comma at the end of the 2nd row)

* Shapefile — https://datacatalog.worldbank.org/search/dataset/0038272

## US Map and Table

![USA](https://github.com/wpbSabi/geospatial/blob/main/one_in_covid_deaths/images/USA_one_in_x_covid_deaths.png)

To see the data represented in the US image:
https://github.com/wpbSabi/geospatial/blob/main/one_in_covid_deaths/data/data_US_2021_09_18.csv

## World Map and Table

![World](https://github.com/wpbSabi/geospatial/blob/main/one_in_covid_deaths/images/World_one_in_x_covid_deaths.png)

To see the data represented in the World image:
https://github.com/wpbSabi/geospatial/blob/main/one_in_covid_deaths/data/data_WORLD_2021_09_18.csv

## Reflection

The coronavirus and COVID-19 pandemic have been part of our lives for almost two years. These visualizations are a high-level view to reflect on where we are today and the number of deaths that have accumulated.