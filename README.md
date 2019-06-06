# police_activity_analysis
Analysis of the effect of gender, time of day, weather, and other factors on police activity based on Datacamp course.

Police data was obtained from Stanford Open Policing Project on Kaggle (https://www.kaggle.com/stanford-open-policing/stanford-open-policing-project-bundle-2), and weather data from the weather station USW00014765 in Providence was obtained from National Centers for Environmental Information (https://www.ncdc.noaa.gov/cdo-web/datasets/GHCND/stations/GHCND:USW00014765/detail).

Some conclusions that were obtained from the data include:
* Male and female proportions for getting a speeding ticket are about the same (~95% ticketed if stopped for speeding)
* The search and frisk rates after getting stopped is higher for males than for females (~1.5-2x), regardless of violation type
* The arrest rate is higher during the night, highest from around 8 pm and 5 am (average rate of 3.5% increases to 6% after midnight)
* The number of drug-related stops have increased over time even though the number of searches conducted has decreased (increase in proportion of searches that are drug-related)
* The most average time stopped by police correlates with 'Call for Service' incidents, while the least average time stopped is for relatively simpler violations such as 'Seatbelt' and 'Speeding' (around 10 min or less)
* Arrest rates increase as weather gets worse for most violations
