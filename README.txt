Weather Dashboard Project
Overview
This project provides a weather dashboard that allows users to search for a city's weather and view a five-day forecast. It includes two main pages:

Index Page (index.html):

This page allows users to search for weather information for a specific city.
It displays the current weather and a chart-based forecast for the next five days.
The chart is generated using Chart.js.
Table Page (tablepage.html):

This page displays the five-day weather forecast in a table format.
It includes a simple weather chatbot feature for interacting with users.
Files Included
index.html: Main landing page where users can search for weather data by city.
tablepage.html: Table view of the five-day weather forecast, including a chatbot.
app.js: JavaScript file that handles API calls, manages the weather data, and renders the forecast charts and tables.
style.css: Styling for the pages, including layout, fonts, and responsive design.
assets/: Folder containing any images or additional assets used by the project.
Setup Instructions
Open index.html in a browser to start the weather dashboard.
Use the search bar on the page to input the name of a city. The page will fetch and display current weather information and a five-day forecast.
To view the forecast in a tabular format, navigate to tablepage.html.
The chatbot on tablepage.html can assist with basic weather-related questions.
Dependencies
Chart.js: Used for rendering weather forecast charts on index.html.
Google Fonts (Poppins): Used for styling the text.
How It Works
Search Functionality:

Users can enter a city name in the search bar.
The application fetches the current weather and five-day forecast using an external weather API.
Chart Display:

Weather forecast data is displayed in a chart on the index.html page using Chart.js.
Table Display:

The tablepage.html file provides a tabular view of the weather data.
Chatbot:

A basic chatbot feature is integrated into tablepage.html, which can respond to simple weather-related queries.