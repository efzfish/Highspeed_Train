# Highspeed_Train
Network analysis for high speed trains in China

[Directory]
---------------------
```
 /data:           data used
 /report:         pdf report and ppt presentation
 /result_images:  visualization of the results
 highspee.ipynb:  main notebook including all codes and visualization
 dic_tz.ipynb:    temporary file for complementary data
```

[Introduction]
---------------------
In this project, we used the population data and the information about the setting of HSR stations and tracks to perform a network analysis on the high-speed rail (HSR) system. Our goal was to build a gravity model of the network so that we could estimate the passenger volume based solely on the information we had.

[Method]
---------------------
Following steps were conducted to build our model. First, train stations were added as nodes in the network. Node attributes included the position of the station and the 2010 population of the administrative district which stations were located in. Next, edges were added to the graph according to the track network. The distances of edges were defined as the geodesic distance between the two cities. Then, a gravity model for estimating passenger volume could be made based on the population, distance and the track network.

[Result]
---------------------
The following figure visualize the overall HSR network with passenger volume predicted.
![Alt text](/result_images/modelshp.png?raw=true "Optional Title")
