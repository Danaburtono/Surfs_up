# Surfs_up
## Overview of the Analysis

The purpose of our analysis is to see temperature statistics for June and December to see if running a surf/ice cream shop is a sustainable year around. To manage the data from the resource provided a few things need to happen to the data: we must query it once for June and another for Dec, convert each to a list, then into a dataframe, to finally receive aggregate metrics on it. Once our dataframe is created we can get our aggregate statistics by using the .describe() method. Before beginning any analysis it's important to view the data to see how it's organized. 

![Screen Shot 2022-08-20 at 4 50 49 PM](https://user-images.githubusercontent.com/107026442/185852755-1c5e0dab-65ab-4ea9-8efe-ef03ac9878d5.png)

## Resources: 
SQLite
SQLAlchemy
Jupyter Notebook

## Results:

The results of the Surfs Up Analysis determined the following:<br/>
<img width="167" alt="Screen Shot 2022-08-21 at 12 09 19 AM" src="https://user-images.githubusercontent.com/107026442/185852865-4a582e5c-4c55-4460-a3bb-719da7c83c2e.png">
<img width="198" alt="Screen Shot 2022-08-21 at 12 09 29 AM" src="https://user-images.githubusercontent.com/107026442/185852896-f3cf05bb-ef9d-4a93-8734-feb09adcfa01.png"><br/>

* Based on temperature markers. there were 1,700 recordings counted in the month of June over the course of seven years, the average temperature is calculated at 75 degrees, minimum of 64 degrees, and a maximum of 85 degrees.

* Based on temperature markers. there were 1,517 recordings counted in the month of December over the course of seven years, the average temperature is calculated at 71 degrees, minimum of 56 degrees, and a maximum of 83 degrees.

* A standard deviation (or σ) derived from the equation above is a measure of how dispersed the data is in relation to the mean. Low standard deviation means data are clustered around the mean, and high standard deviation indicates data are more spread out. A standard deviation close to zero indicates that data points are close to the mean. June's standard deviation is 3.26 and December's is 3.75. These are relatively low distributions so we can consider that the mean for both months is representative of the actual temperature during June and December months. 

<img width="182" alt="Screen Shot 2022-08-21 at 12 49 46 AM" src="https://user-images.githubusercontent.com/107026442/185852943-f62b8e2e-416d-4b01-b425-63b37dae263f.png"> <img width="300" alt="Screen Shot 2022-08-21 at 12 47 41 AM" src="https://user-images.githubusercontent.com/107026442/185852958-61332131-8e58-48b0-9ae0-c28276fe8353.png">

## Summary:

The island of O'ahu is an ideal location for an ice cream/ surf shop that would have business year-round. After running the queries for temperature the result showed that temperature is relatively the same all your round. Two additional queries would be to analyze precipitation in June and December. Monthly rainfall in O'ahu for June is .136360 and December .216819. These numbers are quite different, we can assume June is the driest month of the year and December is the wettest. Further analysis is necessary to determine if O'ahu is the ideal location for the shop.

<img width="178" alt="Screen Shot 2022-08-21 at 11 04 34 PM" src="https://user-images.githubusercontent.com/107026442/185853740-f4542cd2-76e4-44e9-bb75-ba254b2332af.png">
<img width="204" alt="Screen Shot 2022-08-21 at 11 04 51 PM" src="https://user-images.githubusercontent.com/107026442/185853755-b84007fa-15d3-49a0-ab17-dc5a83a58868.png">



