# Seattle Collision Map

Visualizing Car Crashes in Seattle for Better Road Safety

### Application URL
https://tralee10.github.io/Seattle_Collision_Project/index.html

## Project Overview
Our group is developing an interactive web map that visualizes car crashes in Seattle using publicly available datasets. This tool provides insights into traffic incidents, allowing users to explore different trends through interactive filtering and visualizations.

### Key Objectives
* Increase public awareness of traffic hazards.
* Help city planners make data-driven urban planning decisions.
* Enable drivers and commuters to navigate more safely.
* The interactive map will feature crash locations, pop-up details, user-controlled filters, and statistical insights on contributing factors, high-risk intersections, and accident trends.

### Target Audience
This project is designed for:

* Seattle Residents – To identify high-risk areas and make informed decisions about where to live or commute.
* City Planners & Transportation Officials – To improve road safety infrastructure by analyzing accident patterns.
* Drivers & Commuters – To avoid hazardous areas and plan safer routes.



## Features & Functionality

Built using Mapbox for smooth visualization.

### Interactive Web Map:

* Crash point visualization (color-coded by severity)
* Pop-up details: Displays key crash information (i.e. date, severity, type, address).

### User-Controlled Filters:

Filter crash data by year, type (vehicle, pedestrian, cyclist), severity, and contributing factors.

### Heatmaps & Clustering:

Highlights accident-prone locations to identify traffic hazards or for pattern recognition.

### Data Summary Panel:

Provides real-time statistics, such as:

* Most common crash causes.
* High-risk intersections.
* Trends over time.

### References Button:

Opens a pop-up displaying data sources and references.


## Screenshots

## Favicon
![favicon_sea_car](https://github.com/user-attachments/assets/19f2ef80-dd44-444c-a53a-6d3895fe8849)




## Data

### Available Datasets

* Seattle GeoData Portal – General dataset collection related to Seattle traffic collisions. 

(https://data-seattlecitygis.opendata.arcgis.com/search?collection=Dataset&layout=grid&q=Collisions)

* Washington Traffic Safety Commission - Focuses on fatal crashes, providing additional context on severe accidents, speed limits, pedestrian involvement, and primary causes. 

(https://wtsc.wa.gov/dashboards/fatal-crash-map/)

* Seattle GeoData Portal (Vehicle Collisions Data) - Contains records of vehicle-related collisions, including crash details such as severity, involved vehicles, and contributing factors. 

(https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::sdot-collisions-vehicles/about)

* Seattle GeoData Portal (Persons Collisions Data) - Provides data on collisions involving pedestrians and cyclists, including demographics and injuries. 

(https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::sdot-collisions-persons/about)


### Data Processing

* Cleaned datasets by removing irrelevant columns, handling missing data, and standardizing attributes.
* Filtered data to focus on relevant crash incidents.
* Cleaned datasets are stored in the cleanedData/ folder.

### Applied Libraries & Technical Implemations

* **JavaScript, HTML, CSS -** Frontend interactivity.
* **Mapbox GL JS -** Renders the interactive web map.
* **GeoJSON -** Stores and visualizes spatial data.
* **Char.js -** Displays statistical insights.
* **Turf.js -** Used for spatial analysis (e.g. clustering and filtering).



## Acknowledgements

### Inspirations & References
This project is inspired by:

* **Fatal Crash Map** by the Washington Traffic Safety Commission.
* **Seattle Collision Data Visualization** by Tim Ganter.

### AI-Use Disclosure

ChatGPT was used to create the favicon.



## Contributors

Travis Lee, Jeremy Tan, Billy To, Jerry Xhu

