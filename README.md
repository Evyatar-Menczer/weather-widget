# Historical Weather Widget

The Historical Weather Widget is a web component that displays average temperature data for the past month based on user-provided city names or coordinates.

## Features

- Users can enter a city name or coordinates to fetch historical weather data for the past month.
- The widget displays average temperatures for each day of the week.
- Color-coded temperature backgrounds provide visual cues for temperature ranges.
- Two search modes: search by city name or search by geographic coordinates.
- Responsive design.

## Getting Started

1. Add a `<div>` element with the ID where the widget will be displayed.
2. Include the following script tag in your HTML ```<body></body>```:  
   ```<script id="scr" type="module" src="https://Evyatar-Menczer.github.io/weather-widget/scripts/weather-widget.js" div-id={DIV_ID}></script>```  
  Replace ```{DIV_ID}``` with the div id to inject. If no id is specified, a div will be created.  
3. Use the provided methods to interact with the widget and fetch historical weather data.

## Notes
* The user's current location averages data is logged into the console.
* The free weather API I found is in a delay of 5 days.
* You might wonder why there are images and descriptions if I display an average temperature.
Well, I sampled all the weather codes for a given day, and I display the most frequent weather code (weather code eventually translates to image and description)





