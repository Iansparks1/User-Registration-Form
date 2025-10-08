# User-Registration-Form
A fully semantic HTML5 user registration form built to demonstrate best practices in accessibility, form structure, and SEO optimization.

# Project Overview
This repository contains a fully functional,semantically structured HTML form designed for user registration.It demonstrates best practices in semantic HTML5 and  form organization without relying on CSS styling.

# Objective
To implement a structured HTML form based on provided specifications, showcasing semantic markup and accessible interactions.The form is grouped into logical sections to enhance usability and assistive technology compatibility.

# File structure
The repository is organized to reflect a clean, minimal setup focused on semantic HTML implementation and documentation clarity:

semantic-html-form/
├── index.html   # Main HTML form implementation
└── README.md    # Project overview, structure, and usage instructions

# Implementation notes
Semantic elements used:  (main, section, form, fieldset, legend, label, input, select, textarea, button).
Inputs are grouped meaningfully using  (fieldset) and described with  (legend). 
All form controls are explicitly labeled using (for) and (id) attributes.
 
## Styles

This project now includes a `styles.css` file with a modern, responsive design for the registration form. The stylesheet was added to improve usability on both desktop and mobile devices and demonstrates the following features:

- CSS custom properties (variables) for color management (primary colors, neutral colors, status colors and accents).
- A centered `.form-container` with max-width (600px), padding, rounded corners and subtle box-shadow for elevation.
- A responsive two-column `.form-grid` layout for wider screens that collapses to a single column on small screens (below 700px).
- Touch-friendly sizing: interactive elements (buttons, file upload labels, inputs) use a minimum height of 44px for comfortable tapping.
- Accessible focus styles and visible focus rings for keyboard users.
- Input styling that includes consistent padding, border-radius, hover, focus and disabled states.
- Styled form controls: text inputs, selects, textareas, color input, range slider, radio buttons, checkboxes and file upload button.
- Button styles: primary (`.btn.btn-submit`) and reset (`.btn.btn-reset`) with hover/active transitions and subtle transforms.
- Demonstrations of pseudo-classes (`:hover`, `:focus`, `:active`, `:checked`) and pseudo-elements (`::before`, `::after`, `::placeholder`).

## Usage notes
- Wrap your form markup in a container with the class `.form-container` to get the centered card layout.
- Use `.form-grid` to split fields into two columns on wide screens. Add `.full-width` to elements that should span both columns (for example large textareas).
- Apply `.btn`, `.btn-submit`, and `.btn-reset` classes to buttons so they inherit the provided styling and touch sizing.

## Testing
- Open `index.html` in a browser and resize the window or use the browser's device emulator (DevTools) to verify the grid collapses to a single column on smaller widths.
- Check keyboard navigation (Tab) to ensure focus outlines are visible.
- Test on a phone or tablet to confirm inputs and buttons are comfortably tappable.



