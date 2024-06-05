# EV_V2G_Flexibility
This repository contains the input data used in the paper 'EVs' Potential for Smoothing Daily Load Profile Considering Mobility Needs and Solar Output.

"Chainlist.txt" contains personal vehicle-based trip chains derived from the CMAP 2017 travel survey. Each trip chain includes a number of trips, with each trip having the following attributes: Origin, Destination, Start time, End time, and Distance. Locations are provided at the census tract resolution. Times are rounded to 15-minute intervals starting from midnight, ranging from 0 (midnight) to 95 (11:45 PM). Distances are measured in miles.

"Chain_weight.txt" includes the scaling-up factor for each trip chain.

"Home_trips.txt" indicates which trips are heading home.

"Centroidswithstations.csv" shows which census tracts in Chicago have at least one public charging station.

"City-demand-weights.csv" contains time-based weight factors to adjust city electric energy demand in the CMAP region.

"Solar_weight.csv" provides time-based discount factors for a sunny day.

"PCloudy-solar-weight.csv" provides time-based discount factors for a partly cloudy day.

