# California Fire: Project Overview 
This is an overview of the number of wild fire incident and acres burned along seasons and years. The goal of this project is to answer whether there is an trend of California wild fire over the years?

#### Code and Resources Used 
**Data:** CAL FIRE (https://www.fire.ca.gov/incidents/). The dataset is listed in the bottom of the page.  
**Packages:** dplyr, rjson, tidyverse, ggplot2, gganimate, gifski, transformr


## Is there an trend of California wild fire over the years?

#### The peak of California wild fire was between July and Octorber.
<img src="image/FireSta_output.gif" height="400">
<img src="image/Density_over_years.png" height="400">


#### Total acres burned by year
The Paradise wildfire was in 2018. Then, California's August Complex fire wildfire was in 2020.
<img src="image/totalacresburned_by_year.png" height="380"> 


#### The chances of fire incidents in June-May from 2010 to 2019 was 10% more, compared to 2006-2009 
<img src="image/StackBarplot.png"  height="500">


#### Which area tends are likely to have wild fire?
North California tends to have larger fire. Most fire happens  at mountain area. The central valley is relatively safer. Note: complete latitude and longitude were only available from 2013 to present. 

<img src="image/FireMap.png"  height="700">
