# Lloyd Response

Perspective Question: In the Lloyd et al. article, the authors introduce a method that uses a number of different openly available 
geospatial datasets in order to produce high resolution, global gridded descriptions of human populations. Describe the geospatial 
datasets the authors are using in their methodology. How is their method an improvement when compared to a conventional census? Are 
you able to describe how the authors use a number of different geospatial layers with their data science method in order to produce 
a high resolution, global gridded description of human population?

In the article, there were four primary datasets being described: topography, slope, country area, and country ID. 
Topography and slope describe simple spatial features such as elevation and slope steepness. Country area grids uses data of 
administrative areas in order to provide a border of the country and country ID is used to assign a number to a country to 
make identification easier. When compared to the conventional census, these datasets can be used along with the census in order
to disaggregate the “population” from the census onto grid cells of a map in order to predict population location and density.
The datasets themselves help as the scale of the map produced is changed, as smaller scales require more detail in order to accurately 
predict population. Some of the datasets are classified as rater datasets, meaning that they contain a group of pixels that has 
coordinates within those pixels. Every dataset contains some form of information that helps in the prediction of population distribution.
Higher elevations and steeper slopes, for example, typically mean that there are fewer people living there. 
Combining even more datasets (that won’t conflict with each other) can lead to even more specific predictions being made because of 
the different information being provided. 
