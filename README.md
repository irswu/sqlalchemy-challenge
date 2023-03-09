# sqlalchemy-challenge

 This is a climate analysis about Honolulu, Hawaii, which includes two parts: analyzing and exploring the Climate Data, and design the climate app.
 
 In the first part of the analysis, I got the previous 12 months of precipitation data by querying the previous 12 months of data, and then plotted the results.
 
 Then I design a query to find the most-active stations (i.e. the stations that have the most rows). Then within the most-acitve stations, I designed a query to get the previous 12 months of temperature observation (TOBS) data and then ploted the results as a histogram.
 
 
 After I developed the queries, I designed a Flask API based on the queries. I created three API Static Routes that would output the jsonified precipitation, stations, and temperature data for the last year in the database. Then I created two API Dynamic Route that accepts the start date or start and end date as a parameter from the URL and returns the min, max, and average temperatures calculated from the given start date to the end of the dataset.
