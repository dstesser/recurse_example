# recurse_example

In 2019, I installed air temperature sensors in the tropics of Ecuador to investigate the impacts of human activity on ecosystems and biodiversity. Measurements were collected from rainforest sites and agricultural sites over a period of two years. 

Sensors were installed at 4 different heights at each site, from the ground to the canopy, to develop vertical air temperature profiles. The data were logged every five minutes.

The ‘airtemp_testdata.csv’ contains sample data from the oil palm agriculture site. In this example, we include one-month of data collected by two sensors placed in the ground and canopy. 

***How it works***
This program will read the csv of sample air temperature data and resample the time series data into 30-minute intervals for analysis of diurnal air temperature evolution.

We plot the data as a function of height and time of day. This exercise is in preparation for subsequent analysis with air temperature collections from adjacent tropical forest sites.

Heights are in meter units. Air temperatures in degrees Celsius.
