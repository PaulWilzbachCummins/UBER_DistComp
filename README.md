# Movement-of-People

locations_maps.ipynb: This notebook contains geospatial visualizations of the density of pickups across the different boroughs in New York City. The heatmaps include the names of the most transited locations (e.g. Airports and churches).

EDA_Holiday.ipynb: Descriptive analysis to see how UBER pick-up counts differ on a daily and monthly basis. It also includes the comparison of UBER pick-ups during the national holiday week.

location_aggregation.ipynb: Exploration of locations in the Uber 2014 data that corresponded to points of interests in New York City as identified by 2017 Open Data, https://data.cityofnewyork.us/City-Government/Points-Of-Interest/rxuy-2muj. Latitude and longitudes were compared between points in both data sets. 2,432 points had an entry in each and were appropriately named, for the other ~500,000 points in the Uber data the point of interest with the minimum haversine distance was found and named according to that position. These locations are broken down by what borough they were located in.

weather_data_preprocessing.Rmd: Preprocessing performed on "NYCweather_hourly_full.csv" to create "weather_rides.csv". Daily summaries were extracted from hourly data and joined to uber daily ride totals. Features corresponding to individual weather types present on a specific day were created from daily weather codes.

Weather_Rides.Rmd: Data visualization for cleaned weather data including weather type frequency, rides per weather type, correlations of numeric predictors of total rides, explorations of temperatures effect on total rides, and linear regression models on the most significant predictors of total rides per day.

/data directory: Contains all data used in this project, including full, uncleaned datasets as well as processed datasets used in the project analysis.
