# citibike_NY

This <a href="https://www.youtube.com/watch?v=gDD-GttqAjU&list=PLPQFqkp_HvOBzx61F3SY5zNXN0TYMoT9g&t=40s">challenge</a> was found on Couch2Coders YouTube channel using citybike_trips public data in Bigquery. It is splitted into three parts before pulling everything together using CTE.

<b>Part 1:</b>
<ul>
  <li>Create Generation buckets based on the birth year</li>
  <li>Make a bucket for any missing years</li>
  <li>Convert trip distance from seconds to hours</li>
  <li>Convert lat/lon for start & stop stations into GEO points</li>
  <li>Filter out lat/lon where value is 0 or NULL</li>
  <li>Filter NULL birth_year</li> 
  <li>Filter to year 2014</li>
</ul>

<b>Part 2:</b>
<ul>
  <li>Calculate trip distance in metres & kilometres</li>
  <li>Calculate distance per hour</li>
</ul>

<b>Part 3:</b>

Caculate the following by generational type:
<ul>
  <li>Total number of riders</li>
  <li>Average ride time</li>
  <li>Average trip distance</li>
  <li>Average kilometres per hour</li>
</ul>
