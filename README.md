# UFO Sightings

## Project Overview

This project displays data on UFO sightings in HTML. The data is stored in a JavaScript array and the table was created using JavaScript version ES6+. CSS and Bootstrap were used to alter the aesthetics of the site.

The JavaScript data array can be found [here.](https://github.com/skgolden13/UFOs/blob/main/js/data.js).<br>
The JavaScript app used to create the table can be found [here.](https://github.com/skgolden13/UFOs/blob/main/js/app.js)<br>
The CSS file can be found [here.](https://github.com/skgolden13/UFOs/blob/main/static/css/style.css)<br>
The HTML file to open the site can be found [here.](https://github.com/skgolden13/UFOs/blob/main/index.html)<br>

## How to Perform a Search

The initial landing page for the website can be seen below as Figure 1.

<p align="center">
  <img width="900" alt="Initial_Site" src="https://github.com/skgolden13/UFOs/blob/main/images/Initial_Site.PNG"><br>
  <b>Figure 1:</b> Initial Landing Page
</p>

To filter the data, the date should be entered in the format: dd/mm/yyyy. The city, state, country, and shape should be entered in lower case. For example:
- Cities such as "Grants Pass" should be entered as "grants pass." 
- State and country codes should be entered as "ca" or "us" respectively.
- Shapes should be entered as "triangle."

After typing in a filter, hit enter or click outside of the input box to apply the filter. To clear the filters, click "UFO Sightings" in the upper left-hand corner of the site.

A sample filtered search can be found below in Figure 2.

<p align="center">
  <img width="900" alt="Filtered_Site" src="https://github.com/skgolden13/UFOs/blob/main/images/Filtered_Site.PNG"><br>
  <b>Figure 2:</b> Filtered Table for triangular UFOs in Grant's Pass, Oregon, USA on January 1<sup>st</sup>, 2010.
</p>

## Drawbacks and Recommendations

One major drawback is in how the data is organized in the JavaScript file. The durations are listed in multiple different formats and many of the shapes given are more abstract, such as "light" or "fireball." A link to a news article or blog post where the sighting was originally reported would also be helpful for more details than given in the comments section.

Two recommendations for further improvements on this website include:
- The ability to filter by a date range as opposed to a single date.
  - This can help a user conduct broader searches as opposed to being limited to a single date at a time.
- A function that can catch mistakes in the inputs for filters to make the site more user friendly.
  - Catching inputs such as "Grants Pass" or "grantspass" and correcting them to "grants pass" would make the site more accessible to users.
