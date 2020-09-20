# Are you excited for today's read? then go on
## Today I will introduce you to a new HTML5 element
## Also you will see how charts are creadted with JavaScript
# You know what is a chart....
Yes you are right it's how we display data visually as they convey data in simpler form

## To create charts with JavaScript 
1. You need to download this plugin [Charts.js](https://github.com/chartjs/Chart.js/releases/latest) 
- It's a massive plugin for drawing **Pie charts**, **Line charts** and **Bar charts**, which uses the HTML `<canvas>` element to draw graph onto the page.
2. Create the *canvas* element for in the HTML page. that looks similar to this:
`<canvas id="buyers" width="600" height="400"></canvas>`
3. In order to return the context of the canvas 
put this script in the foot of the HTML body
-  This one for creating a line chart (*the data is largly the same for other types of charts*)
>` <script>`
    var buyers = document.getElementById('buyers').getContext('2d'); <br>
    new Chart(buyers).Line(buyerData);
`</script>`
4. Inside this script you will add your data

### A Question: What is the node that is used when rendering a Chart?
~~canvas~~
It creates a fixed-size drawing surface that exposes one or more rendering contexts.

### As you see above we used the a method called getContext() with the canvas element ('buyers')
To obtain the rendering context and its drawing functions.

## Another use of canvas element
### Is to draw shapes and paths.

 ![](https://mdn.mozillademos.org/files/252/Canvas_smiley.png)


### It's possible to draw text also with canvas element
- `fillText(text, x, y [, maxWidth]) `
Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- `strokeText(text, x, y [, maxWidth])`
Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.

### How to style text in canvas?
There are many styling properties for this 
- `font = value` for setting the font type and size. by default it uses the CSS value of 10px and sans-serif
- `text align = value`
- `text baseline = value`

## To remind you 
Shapes or text drawn by canvas element could be filled or outlined.


