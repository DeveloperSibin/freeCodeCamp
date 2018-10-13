---
title: CSS Grid Layout
---
## CSS Grid Layout
CSS Grid Layout is the most powerful layout system available in CSS.
It is a 2-dimensional system, meaning it can handle both columns and rows, unlike flexbox which is largely a 1-dimensional system.
Though Grid Layout isn't fully supported by all browsers, it's the most advanced and conveniet way to make page layouts.

#### Making a container as grid-container:
Inorder to make a class as grid container simply set the display property to grid. For example:
````
.grid-container {

  display: grid;

}
````

#### Grid Gap:
Inorder to make a add gap between the elements in the grid we can use any of the three property:
1. grid-row-gap
````
.grid-container {

  display: grid;
  grid-row-gap: 20px;

}
````
2. grid-column-gap
````
.grid-container {

  display: grid;
  grid-column-gap: 20px;

}
````
3. grid-gap
````
.grid-container {

  display: grid;
  grid-gap: 20px;

}
````

#### More Information:
For more information, read <a href="http://chris.house/blog/a-complete-guide-css-grid-layout/" target="_blank">
A Complete Guide to CSS Grid Layout</a> by Chris House.

More info about browser support can be read at <a href="https://caniuse.com/#feat=css-grid" target="_blank">https://caniuse.com</a>.
