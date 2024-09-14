# Hail Data collection and analysis

## Source Data
Comes from this site at this URL:
https://www.ncdc.noaa.gov/stormevents/listevents.jsp?eventType=(C)+Hail&beginDate_mm=05&beginDate_dd=01&beginDate_yyyy=1999&endDate_mm=05&endDate_dd=31&endDate_yyyy=2024&county=TARRANT%3A439&hailfilter=1.00&tornfilter=0&windfilter=000&sort=DT&submitbutton=Search&statefips=48%2CTEXAS

Query Params specify target county, dates, and hail size, specifically:
* Start Date: May 1st, 1999
* End Date: May 31st, 2024
* County: Tarrant
* Hail minimum size: 1.00 inch

## CSV
Their page lets you download the CSV which includes lat, long for start and end. Now we need to massage that into something we can view... maybe Google Maps data points?

## Google MyMaps
Yeah Google makes this easy, they read the CSV directly. Very nice of them.

Site: https://www.google.com/maps/d/u/0/
Map: https://www.google.com/maps/d/u/0/edit?mid=13HbVT5m6clmIu14LuwC4AfxVYt99iuo&usp=sharing