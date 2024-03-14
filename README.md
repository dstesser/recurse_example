# recurse_example

This program will read a csv of sample air temperature data that I collected from an oil palm plantation in Ecuador during a tropical fieldwork investigation.

The four sets of air temperature data were collected in 5-minute intervals by field sensors placed at four different vertical heights between 0 and 6 meters. The air temperature sensors began data collection prior to field installation. The sensor batteries allowed data collection for a two-year period, however the sensors fail after heavy precipitation events. Therefore the data requires cleaning before processing and analysis.

This example program will clean the data to include the first month of collections after field installation. The program then resamples the data to 30-minute intervals and assembles a diurnal air temperature evolution record for each of the four vertical heights. This analysis is in preperation for subsequent comparison with air temperature collections from adjacent tropical forest sites to guide conservation policy recommendations
