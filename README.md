Hello Guys!
I'm super excited to share with you a project I've been working on - a fully responsive webpage built from scratch using HTML, CSS, and JavaScript!
This is a carousel/slider with navigation arrows and thumbnail previews.
You can use this project to develop your skills in HTMl, CSS, and JavaScript.
It'll be useful for your assessments.

General Explaination:

In HTML page:

- A container <div class="carousel"> holds the carousel.
- Inside, there are:
    - A list of items |<div class="list">| with images and text content.
    - A thumbnail preview section |<div class="thumbnail">| with smaller images.
    - Navigation arrows |<div class="arrows">| to move through the carousel.

CSS:

- Styles for the carousel, including layout, colors, fonts, and animations.
- Defining keyframes for animations (e.g., showContent, showImage, showThumbnail).

JavaScript:

- Selecting DOM elements (e.g., nextDom, prevDom, carouselDom).
- Attaching event listeners to navigation arrows to call the showSlider function.
- Defining the showSlider function, which:
    - Moves the first item to the end (or vice versa) when navigating.
    - Adds/removes classes for animations and navigation.
    - Resets timeouts for automatic navigation.

How it works:

1. The user clicks the next/prev arrow.
2. The showSlider function is called with the direction (next/prev).
3. The function moves the first item to the end (or vice versa) and adds/removes classes for animations.
4. The carousel animates to the new position.
5. The function resets timeouts for automatic navigation (if enabled).
