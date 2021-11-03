
### Class 12 Notes

# Article EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS
* 1st thing; download Chart.js. and then copy the Chart.min.js out of the unzipped folder and into the directory. 
* Then create a new html page and import the script:
<!-- * <!DOCTYPE html>
* <html lang="en">
*    <head>
*       <meta charset="utf-8" />
*      <title>Chart.js demo</title>
*      <script src='Chart.min.js'></script>
*   </head>
*   <body>
*  </body>
* </html> -->
* To draw a line chart, create a canvas element in HTML in which Chart.js can draw our chart. 
* So add this to the body of our HTML page: <canvas id="buyers" width="600" height="400"></canvas>
*

# Basic usage of canvas
* At first sight a <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes. 
* Indeed, the <canvas> element has only two attributes, width and height. These are both optional and can also be set using DOM properties. 
* When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. 
* The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: 
* if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.
