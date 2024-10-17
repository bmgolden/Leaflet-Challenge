# Leaflet-Challenge
Earthquake Map Using Real Time Geological Data

Module 15 Read ME

This module was another great adaptation of concepts presented to us in class, as we were required to use D3 and the Leaflet library to construct an interactive, real-time map that presents earthquake data using the United States Geological Survey (USGS). I used Chat GPT to aid with constructing the body of the code, as it was extremely complex and intricate while practicing incorporating AI into my future workflow. 

The initial part of the code was dedicated to using D3 to read the data from the provided URL, while simultaneously creating functions to determine the size and color of the circle, using real-time data, based on the magnitude and depth of the earthquake respectively. The next function used in the code was used to assign each distinct feature, that exists within the data: place(defined by latitude and longitude, time, magnitude, and depth of the separate occurrences. The final part of this initial portion was used to apply the characteristics defined in the previous function to the earthquakes using methods such as the radius, fill color, weight, and opacity. Finally, coinciding with the preliminary part I sent all of the defined functions to the create map function to culminate individualizing each happening. 

The next portion of the assignment outlined each respective layer, such as the satellite and greyscale base layers. After outlining the base layers I defined the base map, and the overlay map in sequential order to hold the layers for later use. The next, most important part was substantiating the map itself using the let my map function in Leaflet, by defining the center coordinates, zoom, and the layers I described previously. I then added the layers to the map to finish the construction of each component. 

The final section of the code dealt with the creation and implementation of the legend used to define the earthquake depth. First, I defined the legend and its location, and then added the necessary styling such as the background color, border, and border-radius. The final aspect was looping through each interval to generate a unique label and style. Finally, the code was culminated by adding the legend to the map. 
