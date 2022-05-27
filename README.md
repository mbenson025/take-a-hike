# Take a Hike

<br>

# Github Repository and Deployed Application:

<br>
<br>
<a href="https://mbenson025.github.io/take-a-hike/">Deployed App Here</a>
<br>
<br>
<a href="https://github.com/mbenson025/take-a-hike">GitHub Repo</a>
<br>
<br>
Group Members: Alberto, Arthur, Mason, Timothy
<br>
<br>
Concept:
As an avid outdoor person, I want a website that gives me high level park information/location/weather information that would allow me to be well-equipped for an ideal hiking trip.
<br>
<br>
Roles:
<br>
<br>
Alberto: Worked on the JavaScript. Focused on the functionality of the Park selection, park display of information (park buttons, carousel, activites), local storage
<br>
Mason: Worked on the JavaScript. Focused on the apis and the functionality of maps, weather, park display of information (about and description), local storage.
<br>
Timothy: Worked on the CSS and HTML. Focused on the styling and layout of the website to be engaging and user intuitive.
<br>
Arthur: Worked on the ReadMe, PowerPoint, and Software Testing. Focused on fleshing out the bugs and errors.
<br>
<br>

## Version 2.0:

<br>
<br>

- Search input field with jQuery autofill for park selection
- Background image and animation to the State drop down list
- Better display for pictures on Carousel with corresponding info
- Additional features included with google maps.
- media query styling for responsiveness fixes on smaller screens

<br>
<br>

## Technologies Used:

nps.gov, openweathermap.org, and google maps APIs, jQuery and ajax. Languages used: HTML5, CSS, JavaScript.

<br>
<br>

## About

<br>
<br>

- Upon deployment, the application presents the user with a dropdown list of states to choose from.
  - Each state brings a list of national parks(nps.org api) to choose from for an ideal hiking trip
  - Choosing a park brings the user to a "landing page" with information associated to the chosen park.
  - An interactive map(google maps api) showing the location of the park allows the user to find out more about the terrain and area.
  - There is also a weather dashboard display(openweathermap.org api) that dynamically changes to show a five day weather forecast based on the coordinates of the park.
  - Park description, pictures, fees and other relevant information is displayed and will change from park to park.
  - Parks are able to be saved with our "favorite park" button to be used as a quick search from the start page.

<br>
<br>

# Challenges

<br>

- Connecting the NPS api to our google maps and openweather apis
- Time management- deciding which features/issues should be prioritized
- LocalStorage- using multiple values per object was a challenge
- Page display-Swapping between different pages meant having to show/hide different elements

  <br>
  <br>
  <br>

# Demo:

<br>
<img src="./assets/img/HikeTaker.gif" alt="gif of app demonstration" title="App Demo">
<br>
<br>

# Screenshots:

<br>
Search Screen lets you select parks by state via dropdown selection
<img src="./assets/img/takeahikess1.jpg" alt="title page" title="Search Screen">
<br>
<br>
Park list added after state selection
<img src="./assets/img/takeahikess2.jpg" alt="park list" title="Parks by State">
<br>
<br>
Park Landing Page opens with location display via Google Maps
<img src="./assets/img/takeahikess3.jpg" alt="google map" title="Map of Each Park">
<br>
<br>
Park information from api to National Park Service website
<img src="./assets/img/takeahikess4.jpg" alt="description information" title="Park Details">
<br>
<br>
Dynamic 5 day weather forecast for chosen park using an openweathermap.org api
<img src="./assets/img/takeahikeweather.jpg" alt="cards showing forecast" title="5 Day Weather Forecast">
<br>
<br>
List of park activities
<img src="./assets/img/takeahikess5.jpg" alt="activities" title="List of Activities">
<br>
<br>

## Contact:

<br>

Mason Benson - mbenson025@gmail.com

GitHub Profile - https://github.com/mbenson025

<br>

<br>

## License:

<br>

MIT License

Copyright (c) 2022 Mason Benson

Licensed under the [MIT](LICENSE) license.
