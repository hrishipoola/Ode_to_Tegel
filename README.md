# Ode_to_Tegel

On November 8, 2020, Tegel (TXL) saw its last flight take off, closing its doors after 47 years in operation to make way for Berlin's newly opened Brandenburg Airport (BER). I've got many fond memories of TXL, watching the flight board tiles switch, heading for business trips and vacations, and eating at the Terminal B restaurant. TXL's crappiness added to its charm. It's also the only airport I've ever been to with a decentralized security check. A security check at each departure gate meant an unbeatable door-to-gate time.

We found flight traffic stats for both TXL and Schönefeld (SXF) from January 2002 through August 2020 with separate drop-downs for month and year (https://www.berlin-airport.de/en/press/background-information/traffic-statistics/index.php). As a farewell to our beloved TXL, let's scrape the number of commercial arrivals and departures for each month and year, create a dataframe, reshape the dataframe for analysis and plotting, and create visuals using Plotly Express. The purpose of this is to:

- Design a comprehensive scrape by year and month taking into account the quirks of the site's html elements
- Create a dataframe and reshape it using melt and groupby
- Create visuals using Plotly Express plots

From our Plotly express visuals, we can see the historical trend upward in flights, yearly seasonality patterns, dramatic dips in 2006, 2008, and, due to covid, 2020, monthly differences in traffic spreads, which are widest in February, September, and October, and and elevated level of traffic in May, June, July, September, and October of each year.
