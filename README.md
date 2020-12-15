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

So, *does* "America Run On Dunkin'"? Those living in the Northeast (where the majority of Dunkin's are located) would most likely respond: yes, America does run on Dunkin'. However, there are six states in the northwest that do not have a single Dunkin' Donuts store. From a physical store location standpoint: no, America does not run on Dunkin'. However, their coffee is packaged and sold at Target, Walgreens, Kroger, and other major supermarkets, as well as online at [www.dunkindonuts.com](https://www.dunkindonuts.com/en/menu/brew-at-home/packaged-coffee). It can even be purchased on Amazon. While the ability to walk into a Dunkin' Donuts store and order a coffee is limited by geography, it's still possible to have a home brewed cup almost anywhere in the world. As with most things, geographic location heavily sways opinion, the answer to "Does America Run on Dunkin'?" is geographically based. The location I like to ponder that question, is geographically adjacent a hot cup of Dunkin' Donuts coffee.   


