# Natours

Natours is the first project of the course Advanced CSS ans SASS by Jonas Schmedtmann. Here is **[link to the course](https://www.udemy.com/course/advanced-css-and-sass/)**

Natours is a webpage for a fictional company that offers tours in nature such as the sea, forest, snow, etc.

## Goals:

The goal of this project was to make an only-content webpage using HTML and SASS to display the info of the company with the style and animations wanted (neither Flexbox nor CSS Grid was used).  
My personal goals for this project was to support and expand my CSS knoledge as well as having a first contact point with SASS (SCSS to be more precise).

All the code I've made is in the **Starter folder**.

## Skills Learned:

* Custom sections shapes with clip-path property
* Custom grid layout with floats
* Full screen navigation menu with hidden checkbox trick
* Animations with ::before & ::after pseudo-elements
* Two sided elements with diferent content on the sides
* Pure CSS Pop-up
* Background video
* Custom inputs and checkboxes
* Advanced & custom responsive design with media queries

## Sections:

### Navigation:
Fixed position navigation button.
Animation when clicked to full screen Navigation menu. And simple hover animation on each of the elements of the list.

### Header:

The text has an initial animation.  
In the header section we use the clip-path property to give it the angle in the bottom.  
The button has a hover animation achieved with the ::after pseudo-element

### About:

The title of the section has a simple animation to make more interactive, ass well as a linear gradient as color
The images on the right have a hover effect that changes the z-axis and scales up of the image that is hovered as well ass scaling down the rest of the images (with the :not pseudo-class)

### Features:

In this section we use a linear gradient as the icons colors as well as a simple animation when each feature is hovered.

### Tours:

Here we have 3 cards with 2 sides using the backface-visibility property that flips when hovered. 
For tablets and touch phones, since there is no hover, the back of the cards is allways shown.

There is also a popup that shows once the "Book now!" button is pressed.

### Stories:

This section has a video as the background.
We've used the clip-path property again in the photos of the stories. So the text follows the curve of the circle.

### Book:

Fully customized form inputs and checkboxes.

### Footer:

Not much to write on this one. We have a linear gradient as the color of the logo

## Considerations:

If you are considering in taking the course linked above you will see there are some minor diferences between what the instructor does and I have, that's because I think it looks better the way I did (Squared buttons, no margin on the sides, ...)
There is no javascript in this repo, all is done by HTML and CSS (SASS).

There are lot of comments in the code that are meant as notes to the procedures done.


All tips, improvements or comments are welcome! :blush:
