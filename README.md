# Javascript-and-HTML

## Overview
This project comprises a dataset of reported UFO sightings and application written in JavaScript, plus a webpage written in HTML.  The webpage was designed to display the information in an interactive way, allowing users to filter the data by inputing various search criteria by integration of the JS application.  

### Purpose
The purpose of this project was to provide an easily useable means for organizing and displaying the UFO sightings data via webpage where the hypothetical client would be able to filter the data dynamically using multiple simultaneous variables such as city, country, state, and UFO shape.  

## Results
The webpage displays as can be seen in the screenshot below:
![WEBPAGE](https://github.com/AC-Melamed/Javascript-and-HTML/blob/main/Images/Screenshot%202023-02-21%20084508.png)

Unfortunately, for unknown reasons the data table does not display and the filter inputs do not return visible results.  Otherwise, the web page appears as desired.    

## Summary
Aside from the failure in this case to produce a functional version of the proposed webpage, there are additional considerations to make in terms of drawbacks and possible improvements to the current design.

### Drawbacks:
Even if the webapge was properly displaying the data table, the full array of variables contained within the dataset is not transparent to the user before filter inputs are provided.  This means that, when prompted to filter the data by shape for example, the user could easily input a shape not represented in the dataset.  This drawback applies also to each of the other available filters.  

### Reccomendations:
The first reccomendation for improving this project would be to implement a drop-down menu for each filter, thereby resolving the drawback described above.  Alteratively, a static list could be provided somewhere on the webpage where the user could reference it for filter inputs.  A second reccommendation, unrelated to any particular problems encountered but advisable nevertheless, would be to provide a toggle for sorting the returned data results by ascending/descending datea and/or duration.  
