# Multipleballmoving
The HTML and JavaScript code provided creates an animated image that moves back and forth horizontally within a container. Here's a brief description of the code:

The HTML structure:

It starts with the usual document structure, including a <head> section and a <body> section.
The HTML document includes a viewport meta tag for responsive design and sets the document's character encoding and title.
Inside the <body>:

There is a <div> element with the id attribute set to "box." This div acts as a container for the animated image.
Inline CSS is used to set the initial dimensions (height and width) and positioning of the "box" div.
JavaScript section:

An array arr is defined, containing two sub-arrays, each with two image file names. These images will be used in the animation.
An <img> element is dynamically created using JavaScript and appended as a child to the "box" div.
Several variables (position, flag, velocity, and direction) are initialized to control the animation.
The moving() function:

This function is responsible for updating the image source, changing the image's position, and controlling the animation direction.
It updates the src attribute of the image element to cycle between the images in the arr array, creating the appearance of animation.
It checks if the image's position exceeds the window's width or goes below zero and reverses the animation direction accordingly.
The position variable is updated based on the direction and velocity.
CSS properties are set to control the image's size and positioning.
setInterval() is used to repeatedly call the moving() function every 1000 milliseconds (1 second), creating a continuous animation loop.

Overall, this code creates a simple animation of an image moving horizontally within a fixed-width container, changing its appearance as it moves. It switches between two sets of images to give the appearance of animation.
