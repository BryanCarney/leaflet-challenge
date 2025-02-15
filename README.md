# leaflet-challenge

# Solved 

For my submission, I chose to submit a single file because I initially started with a base map featuring a "satellite" view, alongside the required street view. As I was developing the functionality to toggle between these two map views for displaying earthquake data, I realized that it would be more efficient to include a third map view— a topographic map—since the code for toggling between the first two views was already in place. At that point, I decided to incorporate the tectonic plates into the views as well, as they are highly relevant and added value by enabling interesting exploratory analysis.    

![image](https://github.com/user-attachments/assets/59e3f52f-7002-43d9-afa5-e151912e666f)

# Files 

### Solved files 

[JavaScript Solved File - logic.js](https://github.com/BryanCarney/leaflet-challenge/blob/main/static/js/logic.js)

[HTML File - index.html](https://github.com/BryanCarney/leaflet-challenge/blob/main/index.html)

[CSS File - style.css](https://github.com/BryanCarney/leaflet-challenge/blob/main/static/css/style.css)

### Background

The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them to visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. In this challenge, you have been tasked with developing a way to visualize USGS data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

### Instructions
The instructions for this activity are broken into two parts:

# Part 1: Create the Earthquake Visualization
![image](https://github.com/user-attachments/assets/a4ee6f82-1a4e-40f1-90cd-c8d2fbdfb4d2)

Your first task is to visualize an earthquake dataset. Complete the following steps:

1. Get your dataset. To do so, follow these steps:

    • The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON FeedLinks](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php). page and choose a dataset to visualize. The following image is an example screenshot of what appears when you visit this link:

![image](https://github.com/user-attachments/assets/f0a4502f-d308-462c-bd00-7899bbe106c4)

  • When you click a dataset (such as "All Earthquakes from the Past 7 Days"), you will be given a JSON representation of that data. Use the URL of this JSON to pull in the data for the visualization. The following image is a sampling of earthquake data in JSON format:

![image](https://github.com/user-attachments/assets/dfe694ca-d09a-48f8-8894-024532dbcac0)

2. Import and visualize the data by doing the following:

      • Using Leaflet, create a map that plots all the earthquakes from your dataset based on their longitude and latitude.
      
      •Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.
    
      > Hint: The depth of the earth can be found as the third coordinate for each earthquake.
      
      • Include popups that provide additional information about the earthquake when its associated marker is clicked.
      
      • Create a legend that will provide context for your map data.
      
      • Your visualization should look something like the preceding map.

# Part 2: Gather and Plot More Data (Optional with no extra points earning)

Plot a second dataset on your map to illustrate the relationship between tectonic plates and seismic activity. You will need to pull in this dataset and visualize it alongside your original data. Data on tectonic plates can be found at [https://github.com/fraxen/tectonicplates](https://github.com/fraxen/tectonicplatesLinks) to an external site..

This part is completely optional; you can complete this part as a way to challenge yourself and boost your new skills.

The following image is an example screenshot of what you should produce:

![image](https://github.com/user-attachments/assets/3ffdb9de-0a98-4d1d-bf85-a61ed652cbc6)

Perform the following tasks:

  • Plot the tectonic plates dataset on the map in addition to the earthquakes.
  
  • Add other base maps to choose from.
  
  • Put each dataset into separate overlays that can be turned on and off independently.
  
  • Add layer controls to your map.

### Requirements

These requirements apply only to "Part 1: Create the Earthquake Visualization" as "Part 2" is optional with no extra points earning.
