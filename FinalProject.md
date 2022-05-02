## Project Description
As a result of the decennial census in 2020, states are redrawing their congressional and state legislative districts. Subsequently, the partisan and demographic makeup of districts are shifting. This project aims to predict the likelihood of voting in the “new” Pennsylvania House District 33, currently represented by Carrie DelRosso (R). DelRosso flipped the seat from Democratic to Republican in 2020, but decided not to run for re-election, mainly due to the new district boundaries. 

Both the old and new district 33 is located slightly northeast of Pittsburgh. The district encompasses Oakmont, New Kensington, Indiana, Frazer, and Harrison. The new district extends farther south into Sharpsburg, and does not extend as west as the previous district. Since current data is only available for the old district as the 2022 Primary election is the first election using the new map, campaigns are using makeshift maps to make decisions regarding canvassing and Get Out The Vote (GOTV) efforts. 

Therefore, this project will use individual voter history data provided by the Secretary of State of Pennsylvania and available demographic data to predict the likelihood of voting. This data will then be aggregated to the precinct-level, since precinct boundaries are unchanged, before being cut along the new state house district boundary. The final product will be available exclusively for use by the Mandy Steele for State Representative campaign.

The final product will be an interactive map using ArcGIS Insights. This map will allow the campaign to determine which precincts have a high concentration of Democratic-registered voters, and the likelihood of them voting in the upcoming primary election. 


## Time and Cost estimates

### Data collection:
-Voter file from the Secretary of State of Pennsylvania $20 for file, 15 min / $25

-Shapefiles for the 2020 Pennsylvania House of Representatives Districts: 15 min / $25

-Shapefiles for the 2022 Pennsylvania House of Representatives Districts 15 min / $25

-Voter precinct shapefile for Allegheny County

Time: 1 Hour

Cost: $120 ($100 for labor, $20 for voter file)

### Clean Data
-Convert raw Allegheny County voter data from .txt to .csv: 30 min / $50

-Filter voter history to be only those who participated in any election since the 2002 mid-term primary: 1 hour / $100

-Match precincts inside districts 21, 24, 30, 32, 33, and 54. These districts are all adjacent or near to district 33, and all precincts within the 2022 district will likely be in from the aforementioned districts: 6 hours / $600

-Match precincts to the 2022 map: 4 hours / $400

-Filter data to be only voters in precincts residing in Districts 33, 32, 24, 21, 28, 11, 60 under the 2020 boundaries: 3 hours / $300

-Remove unnecessary columns from the data: 3 hours / $300

-Upload 2020 and 2022 district boundaries to ArcGIS Pro: 1 hour / $100

-Create feature class/layer for the 7 districts in question (two feature classes, one for 2020, the other for 2022): 1 hour / $100

-Create feature class/layer for just district 33 (two: one for 2020, one for 2022): 1 hour / $100

-OPTIONAL: If precinct data is for the state, create feature class that is Allegheny County ONLY: 30 min / $50

-Filter data to be Democrat-registered voters only: 30 min / $50

Time: 21.5 hours 

Cost: $2,150

### Analysis
-Create an aggregate predictive model to estimate likelihood of voting based on past election participation and available demographic information for an precinct: 2 hours / $200

Time: 2 hours

Cost: $200


### Projected project total
Time: 24.5 hours

Cost: $2,470

## [Final process log with time and costs](https://docs.google.com/document/d/1lk12yBhMUz5ghLMzOUrQSlcxujabKyksOZXh7Jla0mw/edit?usp=sharing)


[Back: Custom Google Map for SisTersPGH](https://snizan.github.io/GISPortfolio/Homework1)

[Return Home](https://snizan.github.io/GISPortfolio)
