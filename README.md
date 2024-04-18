# citibike_NY

Using citybike_trips public data available in BigQuery, find out in 3 parts

Part 1:
Create Generation buckets based on the BirthYear
Make a bucket for any missing years
Convert trip distance from seconds to hours
Convert lat/lon for start & stop stations into GEO points
Filter out lat/lon where value is 0 or NULL
Filter NULL birth_year 
Filter to year 2014

Part 2:
Calculate trip distance in metres & kilometres
Calculate distance per hour

Part 3:
Caculate the following by generational type:
Total number of riders
Average ride time
Average trip distance
Average kilometres per hour
