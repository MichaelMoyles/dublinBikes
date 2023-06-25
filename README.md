# dublinBike
A journey planner Flask application that presents users with a map of every dublinBikes station in Dublin and the live availability data for each station. The user can input a location and find their closest bike station with either available bikes or available stands to return a bike, depending on their situation. Data was scraped from JCDecaux's bike station data: https://developer.jcdecaux.com/#/opendata/vls?page=getstarted 

The user can also input a time, date, and station for a future journey, and will be presented with the predicted availability for that station at that time, calculated using a predictive model trained on bike availability and weather forecast data scraped from the web and stored in a database.
