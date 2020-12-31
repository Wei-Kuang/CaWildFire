# California Fire: Project Overview 
This is an overview of the number of wild fire incident and acres burned along seasons and years. The goal of this project is to answer whether there is an trend of California wild fire over the years?


## The peak of California wild fire was between July and Octorber.
<img src="image/FireSta_output.gif" height="400">
<img src="image/Density_over_years.png" height="400">


## Total acres burned by year
1. The Harris Fire (South California) was in 2007. 
2. The Paradise wildfire (North California) was in 2018. 
3. Then, California's August Complex fire (North California) was in 2020.
<img src="image/totalacresburned_by_year.png" height="380"> 


## The wildfire season might start earlier, compared to 2006-2009
The chances of fire incidents in June-May (peachpuff color) 10% more after 2009.
<img src="image/StackBarplot.png"  height="500">


## Which area tends are likely to have wild fire?
North California tends to have larger fire. Most fire happens  at mountain area. The central valley is relatively safer. Note: complete latitude and longitude were only available from 2013 to present. 
<img src="image/FireMap.png"  height="500">


#### Code and Resources Used 
**Data:** CAL FIRE (https://www.fire.ca.gov/incidents/). The dataset is listed in the bottom of the page.  
**Packages:** dplyr, rjson, tidyverse, ggplot2, gganimate, gifski, transformr
