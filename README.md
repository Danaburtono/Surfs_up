# surfs_up
## Overview of the analysis

The purpose of our analysis is to see temperature statistics for June and December to see if running a surf/ice cream shop is a sustainable year around. To manage the data from the resource provided a few things need to happen to the data: we must query it once for June and another for Dec, convert each to a list, then into a dataframe, to finally receive aggregate metrics on it. Once our dataframe is created we can get our aggregate statistics by using the .describe() method. Before beginning any analysis it's important to view the data to see how it's organized. 

Insert pic 


## Resources: 
SQLite
SQLAlchemy
Jupyter Notebook

## Results:

The results of the Surfs Up Analysis determined the following:

*Based on temperature markers. there were 1,700 recordings counted in the month of June over the course of seven years, the average temperature is calculated at 75 degrees, minimum of 64 degrees, and a maximum of 85 degrees.

*Based on temperature markers. there were 1,517 recordings counted in the month of December over the course of seven years, the average temperature is calculated at 71 degrees, minimum of 56 degrees, and a maximum of 83 degrees.

inser standard dev. image

*A standard deviation (or σ) derived from the equation above is a measure of how dispersed the data is in relation to the mean. Low standard deviation means data are clustered around the mean, and high standard deviation indicates data are more spread out. A standard deviation close to zero indicates that data points are close to the mean. June's standard deviation is 3.26 and December's is 3.75. These are relatively low distributions so we can consider that the mean for both months is representative of the actual temperature during June and December months. 

inser june and december tables

## Summary:

The island of O'ahu is an ideal location for an ice cream/ surf shop that would have business year-round. After running the queries for temperature the result showed that temperature is relatively the same all your round. Two additional queries would be to analyze precipitation in June and December. Monthly rainfall in O'ahu for June is .136360 and December .216819. These numbers are quite different, we can assume June is the driest month of the year and December is the wettest. Further analysis is necessary to determine if O'ahu is the ideal location for the shop.

Insert-