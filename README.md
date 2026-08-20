# Cab-Demand-Prediction

Data: Rides data in San Francisco between the period 2023-01-01 AND 2026-07-31.
This is dummy data generated using Gemini. 
 
Rides Data: The data is in "sf_cab_requests_2023_2026_1M.csv" file
 
Zone type data: We gathered information on different zones in San Francisco from "https://data.sfgov.org/api/geospatial/3i4a-hu95?method=export&format=GeoJSON"

Weather Data: We can gathered hourly weather data from "https://open-meteo.com/"

Using Uber's Geo Spatial indexing system, we divided the City into Hexagons of roughly 2sqmiles each.
We used Resolution = 7.


What does the script do?
- The script analyzes Rides data, answers a few business questions.
- It predicts the demand for cabs across different Hexagons in the SF over the next 1 hour

 Note:
This script is a mix of hand written code and a few snippets generated using Gemini
