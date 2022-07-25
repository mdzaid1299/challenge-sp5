## Modernizr

## Context

Responsive Design patterns are used to make a web page responsive across various devices of varying screen sizes.Most design patterns will use breakpoints to adapt for different screen sizes. A Breakpoint is the point at which a different CSS will be applied, usually through a media query, to optimize the design for the user’s viewport. A good example of a breakpoint would be one where your layout has to change from two columns to four columns from one device to another.

For full-width multi-column layouts, column drop simply stacks the columns vertically as the window width becomes too narrow for the content.

Eventually this results in all of the columns being stacked vertically. Choosing breakpoints for this layout pattern is dependent on the content and changes for each design.

## Problem Statement

Create a Web Page which resembles the images below following Column drop pattern using Bootstrap framework.

### Desktop Image

![](./Desktop-Image.png)
### Tab Image

![](./Tab-Image.png)
### Mobile Image

![](./Mobile-Image.png)


### Details

All the assets required can be found in the `./assets` folder

### Tasks

- The `index.html` file contains the code for web page that needs to be transformed into responsive web page.​
- Bootstrap framework CSS classes should be used to style the page for responsiveness.​
- The responsiveness has to be implemented based on Column Drop Layout pattern​
- This pattern starts with multi-column layout and ends up with single column, dropping columns along the way as screen sizes get narrower.​
- The custom styles can be added to `style.css` located in the css folder of the boilerplate code.​