Overview.md

Mission
Building a code library that will enable developers to generate bar charts on their web pages.

Tips
* Make lots of small commits with git.
* Have smaller easier functions.
* Have a simple API draw your bar chart.

Obstacles
Setting up ESLint in VS Code.
What is jQuery and how do I use a DOM in js?
How do I demo the page without a server?
How can I get a simple API to draw my Bar Chart when I need to make the chart configs myself?

Getting started
* Create a new GitHub repo, then clone it to your computer.
* Use ESLint for VSCode.
* Have page run directly from your file system. 

Considerations
* Think about how you would need to structure your data to associate a label to each value
* jQuery will access and manipulate the DOM in order to draw the charts.
* Using multi-value data compared to a single bar chart.


Display Requirements
The UI. 
* Make the charts look presentable and try CSS transitions and animations.
Numerical Value Positions
* In the Top, Centre or Bottom of bar (while they can fit)
* Bar sizes are dependent on the data that gets passed into it.
X and Y axis
* X-axis labels and Y-axis ticks.
width and height
* Bar width should be dependent on the total amount of values passed.
* Bar height should be dependent on the values of the data.
  (Scroll bar?)

drawBarChart(data, options, element);
* data; is arrays of numbers e.g. [1, 2, 3, 4, 5]
* options; is an object e.g. object.height, object.width.
* element; is the DOM or jQuery element that the chart will get rendered into?

Customizable Functions
Title
* Title name, font size
* Title font color
Bars
* Bar Color, per value label
* Label Color, per label
Values
* Allow the user to pass multiple values for each bar.
Bar Orientation
* Space between bars
* Bar Chart axis, horizontal and vertical.