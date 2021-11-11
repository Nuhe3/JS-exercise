-Project: Softhouse

-Description:
This is a little application that based on users location retrives air pollution data.
It uses a collection of data from OpenWeatherMap rest API source. 
This includes data on the air quality index, your location, and concentration of eight pollutants in air:
	-Carbon Monoxide
	-Nitrogen Dioxide
	-Ozone
	-Sulphur Dioxide
	-Fine particles matter
	-Coarse particulate matter
	-Ammonia
-The data is presented on the application front-end. When the user opens the application it will ask for premission to use users location. 
-If user allows it, the data will be presented. If not, then the user can manually type in the coordinates (Latitude, Longitude) and press the button 'search'.
-When the data is presented the application automaticaly saves it into JSON and downloads it in .txt format on disk.

