# Does America Run On Dunkin'?
### Exploring Dunkin' Donuts Locations

In April, 2006 Dunkin Donuts unveiled a new slogan "America Runs On Dunkin'". Hearing this makes you believe they have stores across the United States. What sort of trends can be seen by exploring, analyzing and mapping Dunkin' Donuts store locations? Can we empirically conclude that America in fact does run on Dunkin'? This repository attempts to answer these questions. 

#### Data Sources

* [Dunkin' Donuts data](https://www.kaggle.com/jpbulman/usa-dunkin-donuts-stores?select=dunkinDonuts.json)
* [Roadways data](https://catalog.data.gov/dataset/tiger-line-shapefile-2016-nation-u-s-primary-roads-national-shapefile)
* [State data](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html)
* [Population data](https://www.census.gov/data/tables/time-series/demo/popest/2010s-state-total.html)

#### Data Analysis and Data Processing

Data analysis was performed within Jupyter Notebooks using Pandas, Geopandas and Matplotlib. Dunkin' Donuts data was compiled into JSON from the Dunkin' Donuts website 03/17/2020. The JSON file was serialized into a GeoJSON within the serialize notebook. The Dunkin Donuts GeoJSON, the state and roadway shapefiles and the population CSV were loaded into the exploring_dunkin_donuts notebook for data exploration, visualization, merging and cleaning. The cleaned data was then exported for web mapping purposes. Please explore the serialize and exploring_dunkin_donuts notebooks for detailed processes and data munging explanations. 

#### Conclusion

So, does "America Run On Dunkin'"?


