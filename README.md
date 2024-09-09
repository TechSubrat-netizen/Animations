# Loading Page Animation
This project consists of a simple animated loading screen created using HTML and CSS. The page features a set of circular shapes that scale up and down in size, creating a smooth loading effect. Each circle has a different color and animation delay, creating a visual sequence.

## Features
1. Circular Animation: Seven circles are animated to scale up and down to simulate a loading process.
2. Responsive Design: The page is centered using Flexbox, and the content is responsive to various screen sizes.
3. Custom Colors: Each circle is assigned a unique color and delay to give a lively feel to the loading animation.
4. Smooth Animation: Using CSS keyframes, the animation alternates between scaling effects.

 ## Project Structure

The project consists of only two files: an HTML file and embedded CSS styles.

 ### HTML File
1. Defines the structure of the page with a container that holds seven child elements (circles).
2. Includes meta tags for responsiveness and character encoding.
### CSS (Embedded)
1. Uses Flexbox to center the .container both horizontally and vertically.
2. .child elements are styled to be circles (border-radius: 50%) and assigned individual colors.
3. The keyframes defined in @keyframes loading scale each circle from 1.5 to 1.0, producing the loading animation.
4. The duration and delay for each circle’s animation are set individually to create a staggered animation effect.
### Key CSS Classes
1. .container: Holds the circle elements and uses Flexbox for centering.
2. .child: Defines the common styles for all the circles, including size, shape, and animation.
3. Individual classes (.one, .two, .three, etc.) are used to apply specific colors and animation properties for each circle.
### Animation Logic
The animation is defined using keyframes:

1. 0%: Circle scales to 1.5.
2. 100%: Circle scales back to 1.0.
Each circle has its own animation duration and delay, providing a staggered animation effect.

### Usage
To use this loading screen:

1. Copy the HTML and CSS code into your project.
2. Open the HTML file in any browser to see the animated loading screen.
3. Customize the colors, animation timings, and number of circles as needed for your project.
### Browser Compatibility
This loading screen works on all modern browsers that support CSS animations and Flexbox.

### Conclusion
This loading page provides a simple and customizable way to display a loading animation using pure CSS. You can easily integrate it into your web applications or modify the styles to suit your design needs.

