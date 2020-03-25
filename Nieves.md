## 1. Nieves et a. use the random forest machine learning method to predict what value globally?  Describe in detail how random forest works.
   
The random forest method produces values from its decision trees from the data that is given through a process called bagging.
These trees consists of predictions the method produces, with a third of those values serving as an "out of bag" value, which is used
to calculate the model's overall error. The data (in the context of Nieves) is used in the model to create a layer in which population
counts are dasymmetrically redistributed.

## 2. What is a dasymmetric population allocation? 
Which geospatial covariates proved to be the most important when predicting global values of where humans reside?

Dasymmetric population allocation is the distribution of population numbers based on their densities/proportions. 
Based on the data from the model, dasymetric allocation distributes counts from the census data onto an area of grid cells based on the 
covariates that were presented in that area. The geospatial covariates that were most important were ones that related to urban and 
sub-urban extents, as they were most indicative where people resided.
