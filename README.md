# Population_analytics_Project

## World Population Statistics Analysis

## Overview & Aim
In this project, our group provides World Population statistics analysis through an interactive Dashboard. Aiming to provide users an intuitive platform for exploring population analytics. 

## Description
  This Project uses Python Flask-powered API, HTML/CSS, JavaScript, SQLite databases to take a deep dive into the analytics of the World Population. An HTML website is created using Flask API and the SQLite databases in order to show obtained data in a number of ways. A world map was created with dynamic features such as scrolling, zoom, and a clickable name pop-up. Below this map is an interactive drop down menu which contains the top 10 most populous countries. When a selection is made from the drop down, the "Population Info" panel offers information about that country which include, the countries populaiton, yearly percentage change, yearly change, median age, fertility rate, the world population percentage share, and the world population. In addition, the line chart and bar chart change on selection, showcasing the chosen countries Fertility Rate by Year and Population Growth by Year from 1955 to 2023. Finally a pie chart depicting the World Population share by percentage of the top 10 countries and all other countries as "Rest of the World".

## Summary of Contents
### Front End
 
 - Javascript is responsible for client-side interactivity and dynamic behaviour.
 - Visualizations: Chloropleth World Map used Leaflet.js, charts used Plot.js
 - D3.json to fetch required data for the visualizations 
 - Bootstrap and CSS was used for standard layout design of final webpage
### Data, Connection & Back End
 - A SQLite database is used to store approximately 400 records of data
 - A Python Flask API connects the back end to the front end 
 - SQLAlchemy provides the connection from the Database to the Javascipt frile using the `create_engine` function
 - API endpoints through Flask routes are created for the front end to call, located in `/Populations/app.py` 

### Visualizations
 - An interactive World map with dynamic features such as zoom & scroll
 - A Bar plot & line chart displaying fertility rate and population growth for the top 10 most populous countries
 - A Pie chart showcasing population share as a percentage for the top 10 most populous countries along with the rest of the world. 
 - Built with Leaflet.js (world map) and Plot.js (charts)








https://github.com/JP-Butler/Population_analytics_project/assets/129707393/08e5abc3-54b9-4cf8-a421-35073d72d4b2






## Acknowledgements
 - JavaScript
 - Visual Studio
 - HTML code: index.html
 - https://www.worldometers.info/world-population/#top20
 - https://github.com/topics/worldometer-api
 - https://worldpopulationreview.com
 - https://data.worldbank.org
 - Aid from Instructor, Learning Assistant, and Teaching Assistants
 - https://getbootstrap.com/docs/5.3/getting-started/introduction/
 - https://tedboy.github.io/flask/generated/flask.jsonify.html
 - Module 10-Advanced SQL; day 3, activities - Flask, jsonify, sqlalchemy, sqlite
 - Module 11-Data Collection, day 1 - CSS
 - Module 14
 - Module 15- day 2, activities - cholorpleth, geoJSON, HTML, JS
 - https://leafletjs.com/
 - https://codepen.io/infowind/pen/yrMgVr
 - ChatGPT

