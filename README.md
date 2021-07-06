# UFOs (The Truth is out there)

**Project Overview**
---
Dana pick the subject UFO sightings to write her article. The data of UFO sightings is in a javascript file. Dana needs to manipulate the data by adding filters and put all data in a tidy html page.

## Challenge overview

1.Include five total filters in the table:

      Date
      City
      State
      Country
      Shape
To create these additional filters, keep the following points in mind:

- You will need to create a new function that will replace your handleClick(); function. This function saves the element, value, and the id of the filter that was changed.
      - Create an if-else statement to add filter data from input, or clear the filter if no input data exists.
- Additionally, create a function named filterTable(); that will perform the following actions:
      - Set the filtered data to the table.
      - Loop through all of the filters and keep any data that matches the filter values.
      - Rebuild the table by calling the buildTable(); function created earlier.
- Finally, using d3.selectAll();, attach an event listener to pick up changes that are made to each filter.

**Summary**
---

The website has been finished, and the article is ready to go.
The purpose of the challenge is to be able to filter the UFO sighting data by date, city, state, country, and shape in a visually organized html. 

The technologies used were javascript, bootstrap, and html. The raw data (data.js) and filter functionality (app.js) were written with javascript. The app.js pulls and filters the raw data. The bootstrap contains CSS- and JavaScript-based design templates for typography, forms, buttons, navigation and other interface components, which is where the type of style comes from. The html is where all the data is organized and the filter input is entered. 

**Goals**
---

1. Create, update, and deploy JavaScript functions to provide additional table filters.
2. Update and deploy forEach (for loop) to loop through the filters and update them with user input.
3. Update and populate the dynamic filters and table using JavaScript and HTML.

**Recommendation**

1. Let find UFOs API to do dynamic search instead of the static JSON data file
2. Let scrape some UFOs news from websites and update the home page instead of static text news
3. Table data display needs to be modified so it can look great in small mobile phone.

**Languages**
---

1. Javascript ES6 standard
2. D3.js
3. Boostrap 4 (Mobile first) instead of Boostrap 3 (Desktop first)
4. CSS3 
5. HTML5

**Software**
---

1. Visual Studion Code

**Resources**
--
1. app.js <-- the javascript (Controller)
2. index.html<-- the html (Viewer)
3. data.js<-- the data (Model)
4. style.css(static/css/style.css) <-- the UI styles
