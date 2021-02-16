This project was divided up into tasks for legibility and to avoid rerunning time consuming tasks.  Converting addresses to geocoding took hours using free tools.
The order to run the python files is: Evictions Processing, Census Data Prep, Prep Data for Tableau and then Evictions Modeling.  
Because the intermediary files are included, there is no need to rerun all the files, especially Evictions Processing.  Due to github file size limits, Prep Data for Tableau will need to be run to get the geojson files used in the Tableau project at this link: https://public.tableau.com/profile/adam.parente#!/vizhome/NYCEvictionsbyCensusTract2017-2020/EvictionsDashboard?publish=yes
Note that there are two final geojson outputs.  One where the unit of analysis is the census tract (no_dates) and one where the unit of analysis is census tract months (date).

Another key point to make is that as part of parsing the census data, many variables were culled to make the analysis more parsimonious.  
For those inclined to look at alternative features, one can use the Census Data Prep file as a template to pick new variables for their own analysis.

