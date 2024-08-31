# GEOSPATIAL VISUALIZATION OF VOLCANIC ACTIVITY
## By: Can "Jon" Ayter, Amanda Derdiger, Andrew Koller, and Natalia Mitchell

## Introduction
Our project develops an interactive web-based platform to visualize volcanic activity worldwide, leveraging dynamic maps to present data on the Volcanic Explosivity Index (VEI), casualties, and economic damages associated with volcanic events. Incorporating advanced features such as a dropdown menu for seamless navigation between different data visualizations and an MP4 video as the background enhances user engagement. This platform serves as an educational and analytical tool, offering insights into the impact of volcanoes over time through an immersive user experience.

## Data
Our dataset is sourced from Kaggle and contains information on volcanic events, including:

* Year of eruption
* Latitude and Longitude
* Volcanic Explosivity Index (VEI)
* Total Deaths
* Total Damage (in millions of dollars)
* Total Houses Destroyed

## Process
* Data Cleaning and Preparation
* Selected columns of interest from the original dataset
* Dropped rows with missing values in critical fields (Latitude, Longitude, VEI, Year)
* Filled missing values with 0 for Total Deaths, Total Damage, and Total Houses Destroyed

## Visualization Development

### Timeline Visualization
* Created a bar graph showing the number of eruptions per year
* Identified and handled potential outliers in the dataset

### History Map
* Developed an interactive map using Folium
* Color-coded markers based on the year of eruption
* Added a color legend for easy interpretation

### VEI Map
* Created a map with color-gradient markers based on VEI
* Implemented a color scale to represent VEI intensity

### Casualties Map
* Developed a map showing casualties from volcanic events
* Used color-coding to represent different levels of casualties

### Economic Damages Map
* Created a map highlighting the top 10 events with the most economic damage
* Implemented a heatmap layer to visualize the intensity of damages

## Visualizations
### Timeline of Volcanic Events
* Bar graph showing eruptions per year from 1519 to 2024
* Saved as 'timeline_visualization.png'

### History of Volcanic Events Map
* Interactive Folium map with color-coded markers by year
* Saved as 'history_map.html'

### VEI (Volcanic Explosivity Index) Map
* Folium map with color-gradient markers representing VEI
* Saved as 'vei_map.html'

### Casualties by Volcanic Event Map
* Map showing casualties with color-coded markers
* Saved as 'death_map.html'

### Economic Damages by Volcanic Event Map
* Map highlighting top 10 events with most economic damage
* Includes heatmap layer for damage intensity
* Saved as 'damages_map.html'

## Tools Used
* Python
* Pandas for data manipulation
* Matplotlib for static visualizations
* Folium for interactive maps
* Branca for color scales

## How to View the Project
* Clone the repository
* Install required dependencies (Pandas, Matplotlib, Folium, Branca)
* Run the Jupyter Notebook to generate visualizations
* Open the HTML files in a web browser to view interactive maps

## Future Work
* Implement real-time data integration for current volcanic activities
* Enhance user interactivity with filtering options
* Develop predictive models for volcanic eruption risk assessment

## About the Authors
* [Can "Jon" Ayter](https://github.com/canayter)
* [Amanda Derdiger](https://github.com/aderdiger)
* [Andrew Koller](https://github.com/AEKoller)
* [Natalia Mitchell](https://github.com/nmitchell1219) 

