# day9-class-assignment
This project showcases a simple web page with dropdown controls to change various CSS properties such as text color, background color, padding, font size, and font weight. It's a demonstration of how these properties can be controlled using HTML, CSS, and JavaScript.
Whenever a selection is made in a dropdown, the JavaScript code attached to the page detects the change and applies the selected value as a new CSS property to the target div.
## JavaScript Functionality
The core JavaScript functionality that enables the real-time styling changes is achieved through event listeners and DOM manipulation:
- Event listeners are attached to each select element using their respective IDs.
- When a selection changes (triggered by the 'change' event), the event listener calls the `updateStyle` function.
- The `updateStyle` function reads the selected value from each dropdown and sets it as a CSS property of the target div.

By combining these event listeners and DOM manipulation, the project creates an interactive interface that demonstrates the dynamic nature of web development.
