# Chile-Earthquake-Visualizer
This project is a web scraper to display the earthquakes in Chile.

Program Windows RAR ZIP File:
https://drive.google.com/drive/folders/1Y5j1jn1fcuUHFrGZGQmSe-xRtlkixHI4?usp=sharing

Program folder:


Technologies used:
• React
• Google Maps API
• Sass
• Express
• Node

How it works-:
It uses a simple web scraper that fetches data from "https://earthquake.usgs.gov/fdsnws/event/1/query?format=geojson&starttime=2024-07-03T00:00:00&endtime=2024-07-03T23:59:59" and the API from USGS. On top of that, it uses an Express API to filter earthquakes by date and source and converts the collected data into a GeoJSON Object.
