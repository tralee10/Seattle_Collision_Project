# Visualizing Seattle Traffic Collisions

**Seattle Collision Map** - Visualizing Car Crashes in Seattle for Better Road Safety.

### Application URL
https://tralee10.github.io/Seattle_Collision_Project/index.html

## Project Overview
This interactive web map provides a detailed visualization of car crashes in Seattle, leveraging publicly available datasets to present a comprehensive overview of traffic incidents. By offering insights into crash trends, severity, and contributing factors, the project aims to improve public awareness and assist in data-driven urban planning decisions.

The map specifically focuses on crash data from the years 2016 and 2020 to highlight changes in traffic patterns before and after the COVID-19 pandemic. Users can interact with the map to explore these trends, utilizing various filtering tools and visualization techniques to gain deeper insights into traffic safety issues.

### Key Objectives
This project is designed to achieve the following goals:

* **Increase Public Awareness**: By making crash data accessible and interactive, the project helps Seattle residents better understand road safety risks in their area.
* **Support Data-Driven Urban Planning**: City planners and transportation officials can utilize the insights derived from the data to enhance infrastructure and implement safety measures.
* **Improve Road Safety for Drivers and Commuters**: By identifying high-risk intersections and common crash causes, the project allows drivers to make informed decisions about their routes and behaviors.

The interactive map provides a variety of functionalities, including:

* Crash location visualization with interactive pop-ups displaying crash details.
* User-controlled filters for customizing the displayed data.
* Heatmaps and clustering to highlight high-risk areas.
* A data summary panel showcasing key statistics, trends, and safety insights.

### Target Audience
The Seattle Collision Map is designed for a diverse set of users who benefit from its insights:

* **Seattle Residents**: Allows individuals to assess traffic risks near their homes, workplaces, and frequently traveled routes.
* **City Planners & Transportation Officials**: Provides a data-driven approach to improving road safety infrastructure, such as redesigning intersections and implementing new traffic regulations.
* **Drivers & Commuters**: Helps motorists and cyclists make informed decisions about their routes, potentially reducing their exposure to hazardous areas.
* **Researchers & Data Analysts**: Offers valuable data for further studies on urban mobility, accident patterns, and public safety.



## Features & Functionality

This web application is built using Mapbox to ensure a smooth and interactive user experience.

### Interactive Web Map:

* **Crash Point Visualization**: Accidents are displayed on the map with color-coded markers that indicate severity levels, allowing users to identify high-risk locations at a glance.
* **Pop-up Details**: Clicking on a crash marker provides detailed information, including the date, severity, type of collision, and specific location.

### User-Controlled Filters:

* **Dot-Density Map & Heatmap Toggle**: Users can switch between a dot-density representation of crashes and a heatmap that highlights accident hotspots.
* **Time Slider**: Allows users to compare crash data between 2016 and 2020 to observe changes over time.
* **Crash Type Filter**: Users can filter crashes based on the type of incident, such as vehicle-only accidents, pedestrian-involved crashes, or cyclist collisions.
* **Severity Filter**: Allows filtering of crashes based on severity, distinguishing between minor, serious, and fatal incidents.

### Heatmaps & Clustering:

* **Accident-Prone Areas**: The heatmap visualizes locations with a high concentration of crashes, making it easier to identify dangerous intersections and road segments.
* **Pattern Recognition**: Helps reveal trends in crash frequency, aiding in the development of targeted road safety interventions.

### Data Summary Panel:

* **Real-Time Statistics**: Provides key insights into the data, such as the most common causes of crashes, the intersections with the highest number of incidents, and year-over-year trends.
* **High-Risk Intersections**: Identifies locations with frequent accidents, which can inform infrastructure improvements and policy changes.
* **Crash Trends Over Time**: Displays graphical representations of accident frequency, severity, and contributing factors, helping users understand how traffic safety has evolved.

### References Button:

**Data Sources & Documentation**: A dedicated button allows users to view a pop-up that lists all data sources, methodologies, and references used in the project.


## Screenshots

The following images illustrate the key features of the Seattle Collision Map:

### Dot-density Map
![image](https://github.com/user-attachments/assets/69bcc84b-0955-4469-96fb-e71f85077b95)

### Heatmap
![image](https://github.com/user-attachments/assets/7becac01-792f-4332-93b6-51726b46203c)

### Sidebar (Switch Map Button, Time Slider, Filters, Summary Statistics)
![image](https://github.com/user-attachments/assets/1c310033-1ee4-476d-bc8d-035cf535bc42)

### Pop-up Details
![image](https://github.com/user-attachments/assets/f3368d31-d796-442a-91a6-0efe4f15becd)


## Favicon
![favicon_sea_car](https://github.com/user-attachments/assets/19f2ef80-dd44-444c-a53a-6d3895fe8849)




## Data Sources

### Available Datasets

This project utilizes publicly available datasets:

* **Seattle GeoData Portal** – General dataset collection related to Seattle traffic collisions. 

(https://data-seattlecitygis.opendata.arcgis.com/search?collection=Dataset&layout=grid&q=Collisions)

* **Washington Traffic Safety Commission** - Focuses on fatal crashes, providing additional context on severe accidents, speed limits, pedestrian involvement, and primary causes. 

(https://wtsc.wa.gov/dashboards/fatal-crash-map/)

* **Seattle GeoData Portal (Vehicle Collisions Data)** - Contains records of vehicle-related collisions, including crash details such as severity, involved vehicles, and contributing factors. 

(https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::sdot-collisions-vehicles/about)

* **Seattle GeoData Portal (Persons Collisions Data)** - Provides data on collisions involving pedestrians and cyclists, including demographics and injuries. 

(https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::sdot-collisions-persons/about)


### Data Processing

* **Cleaning & Preprocessing**: Removed irrelevant columns, handled missing data, and standardized attribute formats.
* **Filtering**: Focused on crash incidents that were relevant to our analysis, particularly those occurring in 2016 and 2020.
* Cleaned datasets are stored in the cleanedData/ folder.



## Applied Libraries & Technical Implemations

* **JavaScript, HTML, CSS** - Provides the structure and styling for the web application.
* **Mapbox GL JS** - Handles rendering of the interactive map and geospatial visualizations.
* **GeoJSON** - Used for storing and displaying spatial data.
* **Chart.js** - Displays statistical insights in an intuitive graphical format.
* **Turf.js** - Performs spatial analysis tasks such as clustering and filtering.



## Acknowledgements

### Inspirations & References
This project drew inspiration from:

* **Fatal Crash Map** by the Washington Traffic Safety Commission.

(https://wtsc.wa.gov/dashboards/fatal-crash-map/)

* **Seattle Collision Data Visualization** by Tim Ganter.

(https://seattlecollisions.timganter.io/collisions)

### Imagery
Imagery provided by:

**Visit The USA**: Guide To USA Holidays & Travel Around America

(https://www.visittheusa.com/destination/seattle)

### AI-Use Disclosure

* ChatGPT was used to help debug JavaScript code.
* ChatGPT was used to create the favicon.

AI tools were not used to 


## Contributors

Travis Lee, Jeremy Tan, Billy To, Jerry Xhu

