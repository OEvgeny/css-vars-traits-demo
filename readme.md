# Versatile Component Styling with CSS Variables


This is my take on using CSS variables to create versatile styling for web components. It uses three types of classes:

- `file-input`: a component class that defines the basic structure and functionality of a file input element.

- `*-var`: a trait class that provides variables with optional defaults along with necessary modifications for the css properties, such as colors, fonts, borders, etc.

- `primary, accent, thick ...`: modifier classes that change the values of the variables provided by the trait class, allowing for different variations of the component
