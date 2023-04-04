# Reading - Class 12

These notes will cover JavaScript canvas and Chart.js

## JavaScript Canvas

1. **What does the `<canvas>` allow a developer to acheive?** It allows developers to create and render 2D graphics using JavaScript.

2. **What is the importance of the closing `</canvas>` tag?** Any content between the opening and closing tags will be fallback content and therefore will only display if the browser does not support `<canvas>`. If we forget the closing tag then everything after the opening `<canvas>` tag will be interpreted as fallback content.

3. **Explain what the `getContext()` method does.** It defines the *context* of how our shape should be rendered, meaning it determines whether our shapes should be rendered in 2D, 3D (webGL), or as a bitmap. [source](https://developer.mozilla.org/en-US/docs/Web/API/HTMLCanvasElement/getContext)

## Chart.js

1. **What is Chart.js and how it can be brought into your project?** Chart.js is an open-source library that developers can use to create various types of data charts with.  We can install it thru various means, one that might be familiar is with `npm install chart.js` and can then be imported into your JavaScript files and linked into your HTML with a `<script>` tag.

2. **List 3 different Chart types you can create using Chart.js.** We can make Bar Charts, Pie Charts, and Scatter Charts with Chart.js

## Animated Charts with Chart.js

1. **What are some advantages to displaying data via a chart over a table?** Using a chart can sometimes better visually represent the information whereas using a table leaves a lot of the visualization up to the person. We can also animate charts using JavaScript which might make the data being represented a lot more impactful.

2. **How could Chart.js aid your previously created applications visually?** With the Salmon Cookies project we could have used a chart to visualize the differences in sales between each store location or show how each individual stores sales vary from hour to hour and better visualize when peak hours were.

## Things I Want To Know More About:
- I would love to see a demo of how to install chart.js and import its features into a javascript file; I think I would be able to follow a guide but a demo I think would help cement the process in my head.
